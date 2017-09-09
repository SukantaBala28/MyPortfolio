<template>
	<div class="container">
	    <div class="appmain">
	    	<div class="row" v-for='posts in processedPosts'>
	    		<div class="col-lg-3" v-for='post in posts'>
	    		  <div class="card">
	    		    <a :href="post.url" target="_blank"><img :src="post.image_url" width="280px" height="220px"></a>
	    		    <div class="card-body">
	    		      <h4 class="card-title">{{post.title}}</h4>
	    		      <p class="card-text">{{post.abstract}}</p>
	    		    </div>
	    		  </div>
	    		</div>
	    	</div>
	    </div>
	</div>
</template>

<script>
const NYTBaseUrl = 'https://cdn.rawgit.com/SukantaBala28/Web_Development_Project-1/c12872d/'

function buildUrl (url) {
  return NYTBaseUrl + url + '.json'
}

import axios from 'axios'
export default {
  data () {
    return {
      results: []
    }
  },
  created () {
    this.getPosts('home')
  },
  methods: {
    getPosts (section) {
      let url = buildUrl(section)
      axios.get(url).then((response) => {
        this.results = response.data.results
      }).catch(error => { console.log(error) })
    }
  },
  computed: {
    processedPosts () {
      let posts = this.results

      // Add image_url attribute
      posts.map(post => {
        let imgObj = post.multimedia.find(media => media.format === 'superJumbo')
        post.image_url = imgObj ? imgObj.url : 'http://placehold.it/300x200?text=N/A'
      })

      // Put Array into Chunks
      let i
      let j
      let chunkedArray = []
      let chunk = 4
      for (i = 0, j = 0; i < posts.length; i += chunk, j++) {
        chunkedArray[j] = posts.slice(i, i + chunk)
      }
      return chunkedArray
    }
  }
}
</script>





