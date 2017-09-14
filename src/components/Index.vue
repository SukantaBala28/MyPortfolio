<template>
  <div id="content-section">
    <div id="about" class="aboutme">
      <div class="container">
        <div class="row">
          <div class="col-lg-12 text-center" style="padding-bottom:50px;">
            <h1>ABOUT ME</h1>
            <h5>Think Positive, Be Positive</h5>
          </div>
        </div>
        <div class="row">
          <div class="col-md-8">
            <div class="personal">
              <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Minima maxime quam architecto quo inventore harum ex magni, dicta impedit.Lorem ipsum dolor sit amet, consectetur adipisicing elit. Minima maxime quam architecto quo inventore harum ex magni, dicta impedit.Lorem ipsum dolor sit amet, consectetur adipisicing elit. Minima maxime quam architecto quo inventore harum ex magni, dicta impedit.Lorem ipsum dolor sit amet, consectetur adipisicing elit. Minima maxime quam architecto quo inventore harum ex magni, dicta impedit.</p>
            </div>
          </div>
          <div class="col-md-4">
            <div class="my-image">
              <agile :arrows="false" :speed="1150"
                :timing="'linear'" :fade="true"
                :autoplay="true" :pauseOnHover="false">
                  <div class="slide slide--1"><h1 style="color:red">Slide 1</h1></div>
                  <div class="slide slide--2"><h1>Slide 2</h1></div>
                  <div class="slide slide--3"><h1>Slide 3</h1></div>
              </agile>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div id="services" class="services">
      <div class="container">
        <div class="row">
          <div class="col-lg-12 text-center" style="padding-bottom:50px;">
            <h1>SERVICES</h1>
            <h5>Lorem ipsum dolor sit amet consectetur.</h5>
          </div>
        </div>
        <div class="row text-center">
          <div class="col-md-4">
            <span class="fa-stack fa-4x">
              <i class="fa fa-circle fa-stack-2x text-primary"></i>
              <i class="fa fa-shopping-cart fa-stack-1x fa-inverse"></i>
            </span>
            <h4>E-Commerce</h4>
            <p class="text-muted">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Minima maxime quam architecto quo inventore harum ex magni, dicta impedit.</p>
          </div>
          <div class="col-md-4">
            <span class="fa-stack fa-4x">
              <i class="fa fa-circle fa-stack-2x text-primary"></i>
              <i class="fa fa-laptop fa-stack-1x fa-inverse"></i>
            </span>
            <h4>Responsive Design</h4>
            <p class="text-muted">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Minima maxime quam architecto quo inventore harum ex magni, dicta impedit.</p>
          </div>
          <div class="col-md-4">
            <span class="fa-stack fa-4x">
              <i class="fa fa-circle fa-stack-2x text-primary"></i>
              <i class="fa fa-lock fa-stack-1x fa-inverse"></i>
            </span>
            <h4 class="service-heading">Web Security</h4>
            <p class="text-muted">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Minima maxime quam architecto quo inventore harum ex magni, dicta impedit.</p>
          </div>
        </div>
      </div>
    </div>

    <div id="portfolio" class="portfolio">
      <div class="container">
        <div class="row">
          <div class="col-lg-12 text-center" style="padding-bottom:50px;">
            <h1>PORTFOLIO</h1>
            <h5>Lorem ipsum dolor sit amet consectetur.</h5>
          </div>
        </div>
        <div class="row text-center">
          <div class="col-md-4">
            <span class="fa-stack fa-4x">
              <i class="fa fa-circle fa-stack-2x text-primary"></i>
              <i class="fa fa-shopping-cart fa-stack-1x fa-inverse"></i>
            </span>
            <h4>E-Commerce</h4>
            <p class="text-muted">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Minima maxime quam architecto quo inventore harum ex magni, dicta impedit.</p>
          </div>
          <div class="col-md-4">
            <span class="fa-stack fa-4x">
              <i class="fa fa-circle fa-stack-2x text-primary"></i>
              <i class="fa fa-laptop fa-stack-1x fa-inverse"></i>
            </span>
            <h4>Responsive Design</h4>
            <p class="text-muted">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Minima maxime quam architecto quo inventore harum ex magni, dicta impedit.</p>
          </div>
          <div class="col-md-4">
            <span class="fa-stack fa-4x">
              <i class="fa fa-circle fa-stack-2x text-primary"></i>
              <i class="fa fa-lock fa-stack-1x fa-inverse"></i>
            </span>
            <h4 class="service-heading">Web Security</h4>
            <p class="text-muted">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Minima maxime quam architecto quo inventore harum ex magni, dicta impedit.</p>
          </div>
        </div>
      </div>
    </div>

    <div id="team" class="team">
      <div class="container">
        <div class="row">
          <div class="col-lg-12 text-center" style="padding-bottom:50px;">
            <h1>OUR TEAM</h1>
            <h5>Lorem ipsum dolor sit amet consectetur.</h5>
          </div>
        </div>
        <div class="row text-center">
          <div class="col-md-4">
            <span class="fa-stack fa-4x">
              <i class="fa fa-circle fa-stack-2x text-primary"></i>
              <i class="fa fa-shopping-cart fa-stack-1x fa-inverse"></i>
            </span>
            <h4>E-Commerce</h4>
            <p class="text-muted">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Minima maxime quam architecto quo inventore harum ex magni, dicta impedit.</p>
          </div>
          <div class="col-md-4">
            <span class="fa-stack fa-4x">
              <i class="fa fa-circle fa-stack-2x text-primary"></i>
              <i class="fa fa-laptop fa-stack-1x fa-inverse"></i>
            </span>
            <h4>Responsive Design</h4>
            <p class="text-muted">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Minima maxime quam architecto quo inventore harum ex magni, dicta impedit.</p>
          </div>
          <div class="col-md-4">
            <span class="fa-stack fa-4x">
              <i class="fa fa-circle fa-stack-2x text-primary"></i>
              <i class="fa fa-lock fa-stack-1x fa-inverse"></i>
            </span>
            <h4 class="service-heading">Web Security</h4>
            <p class="text-muted">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Minima maxime quam architecto quo inventore harum ex magni, dicta impedit.</p>
          </div>
        </div>
      </div>
    </div>

    <div id="feedback" class="feedback">
      <div class="container">
        <div class="row">
          <div class="col-lg-12 text-center" style="padding-bottom:50px;">
            <h1>CLIENT FEEDBACK</h1>
            <h5>Lorem ipsum dolor sit amet consectetur.</h5>
          </div>
        </div>
        <div class="row text-center">
          <div class="col-md-4">
            <span class="fa-stack fa-4x">
              <i class="fa fa-circle fa-stack-2x text-primary"></i>
              <i class="fa fa-shopping-cart fa-stack-1x fa-inverse"></i>
            </span>
            <h4>E-Commerce</h4>
            <p class="text-muted">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Minima maxime quam architecto quo inventore harum ex magni, dicta impedit.</p>
          </div>
          <div class="col-md-4">
            <span class="fa-stack fa-4x">
              <i class="fa fa-circle fa-stack-2x text-primary"></i>
              <i class="fa fa-laptop fa-stack-1x fa-inverse"></i>
            </span>
            <h4>Responsive Design</h4>
            <p class="text-muted">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Minima maxime quam architecto quo inventore harum ex magni, dicta impedit.</p>
          </div>
          <div class="col-md-4">
            <span class="fa-stack fa-4x">
              <i class="fa fa-circle fa-stack-2x text-primary"></i>
              <i class="fa fa-lock fa-stack-1x fa-inverse"></i>
            </span>
            <h4 class="service-heading">Web Security</h4>
            <p class="text-muted">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Minima maxime quam architecto quo inventore harum ex magni, dicta impedit.</p>
          </div>
        </div>
      </div>
    </div>

    <div id="contact" class="contactme">
      <div class="container">
        <div class="row">
          <div class="col-lg-12 text-center" style="padding-bottom:50px;">
            <h1>CONTACT WITH ME</h1>
            <span class="fa-stack fa-4x">
              <i class="fa fa-circle fa-stack-2x text-primary"></i>
              <i class="fa fa-handshake-o fa-stack-1x fa-inverse"></i>
            </span>
          </div>
        </div>
        <div class="row">
          <div class="col-lg-12">
            <form id="contactForm" name="sentMessage">
              <div class="row">
                <div class="col-md-6">
                  <div class="form-group">
                    <br/>
                    <img src="../assets/img/contactme.png" class="img-responsive" alt="Contact Image">
                  </div>
                </div>
                <div class="col-md-6">
                  <form>
                    <div class="form-group">
                      <label class="label" for="formGroupExampleInput">Your Name</label>
                      <input type="text" class="form-control" id="formGroupExampleInput" placeholder="Example input">
                    </div>
                    <div class="form-group">
                      <label class="label" for="formGroupExampleInput2">Your Email</label>
                      <input type="text" class="form-control" id="formGroupExampleInput2" placeholder="Another input">
                    </div>
                    <div class="form-group">
                      <label class="label" for="formGroupExampleInput3">Phone No</label>
                      <input type="text" class="form-control" id="formGroupExampleInput2" placeholder="Another input">
                    </div>
                    <div class="form-group">
                      <label class="label" for="formGroupExampleInput4">Your massege</label>
                      <textarea class="form-control" id="exampleTextarea" rows="5"></textarea>
                    </div>
                  </form>
                  <button type="button" class="btn btn-info">Send Message</button>
                </div>
              </div>
            </form>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Vue from 'vue'
import VueAgile from 'vue-agile'
Vue.use(VueAgile)
export default {
}
</script>

<style scoped>
  .aboutme,.services,.portfolio,.team,.feedback,.contactme{
    padding: 100px 0px 100px 0px;
  }
  .contactme{
    background-color: #222;
    background-image: url(../assets/img/map-image.png);
    background-repeat: no-repeat;
    background-position: center;
    color: #fff;
  }
  .label{
    font-weight: bold;
    float: left;
  }
  .btn{
    float:left;
  }

  .personal{
    padding:80px;
    text-align: justify;
    font-style: italic;
  }
</style>

<style lang="scss" scoped>
  .agile {
      &__dots {
          bottom: 0;
          display: block;
          left: 10px;
          position: absolute;
          width: 10px;
      }

      &__dot {
          margin-bottom: 10px;

          button {
              background-color: transparent;
              border: 1px solid #fff;
              margin-top: 10px;

              &:hover {
                  background-color: #fff;
              }
          }

          &--current {
              button {
                  background-color: #fff;
              }
          }
      }
  }

  .slide {
      background: {
          position: center;
          size: cover;
      }

      &--1 {
          background-image: url(../assets/img/sukanta1.jpg);
          border-radius:50%;
          width:300px;
          height:300px;
      }
      &--2 {
          background-image: url(../assets/img/ny.jpg);
          border-radius:50%;
          width:300px;
          height:300px;
      }
      &--3 {
          background-image: url(../assets/img/la.jpg);
          border-radius:50%;
          width:300px;
          height:300px;
      }
  }
</style>






