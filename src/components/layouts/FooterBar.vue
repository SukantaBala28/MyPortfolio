<template>
	<div class="footer">
	  <div class="main-footer">
	  	<div class="container">
		    <div class="row">
	  			<div class="col-md-4 mainfooterLeft">
	  				<div class="">
	  					<h6 class="text-center">HEADER MENU</h6><br/>
	  					<ul>
	  						<li>ABOUT</li>
	  						<li>SERVICES</li>
	  						<li>PORTFOLIO</li>
	  						<li>TEAM</li>
	  						<li>FEEDBACK</li>
	  						<li>CONTACT</li>
	  					</ul>
	  				</div>
	  			</div>
	  			<div class="col-md-4 mainfooterMiddle">
	  				<div class="">
	  					<h6 class="text-center">PERSONAL LINK</h6><br/>
			  			<ul>
	  						<li>CURRICULAM VITAE</li>
	  						<li>BLOG</li>
	  					</ul>
			  		</div>
	  			</div>
	  			<div class="col-md-4">
	  				<div class="text-center">
			  			<p>SOCIAL PLATFORM</p>
			  		</div>
	  			</div>
	  		</div>
		  </div>
	  </div>
	  <div class="subfooter">
	  	<div class="container">
	  		<div class="row">
	  			<div class="col-md-12">
	  				<div class="text-center">
	  			  	<p>&copy;2017 Sukanta Bala's personal portfolio</p>
	  				</div>
	  			</div>
	  		</div>
	  	</div>
	  </div>
	</div>
</template>

<script>
export default {
}
</script>

<style scoped>
.main-footer{
	padding: 150px 0px;
	background-color: #FAFAFA;
}
.mainfooterLeft, .mainfooterMiddle{
	border-right: 2px solid #ff0000;
}
.mainfooterLeft ul li, .mainfooterMiddle ul li{
	list-style-type:none;
	text-align:left;
}
.subfooter{
	padding: 15px 0px 0px 0px;
	background-color: #F00000;
}
</style>
