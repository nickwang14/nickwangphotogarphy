---
layout: about
---
<!-- Header -->
<div class="about">
    <div id="aboutCarousel" class="carousel slide" data-ride="carousel" data-interval="false">
    <div class="carousel-inner">
	    <div class="item intro-message active" 
	    	style="
	    	background: url(/assets/about/aboutbg.jpg)
	    	no-repeat; 
	    	background-position: center center;
	    	background-size: cover;
	    	width:100%;
	    	height:100%;">
	        <h1>Nick Wang</h1>
	        <h3>About</h3>
	        <hr class="intro-divider">
	        <h4> 
	        <a href="/shoot.html">Shoot</a> | 
	        <a href="/fight.html">Fight</a> | 
	        <a href="/explore.html">Explore</a>
	        </h4>
	    </div>
	    <!-- End item 1 -->
	    <div class="item container-fluid intro">
		    <div class="row">
				<div class="col-md-6 col-sm-12 col-xs-12">
				<div class="well photography" data-mh="row-1">
			        <h2 class="section-heading">Shoot</h2>
			        <p class="lead">
			        Photography, as with any art, requires dedication and practice to stay sharp.
			        If you scroll through my <a href="instagram.com/{{instagram_username}}" target="_blank">
			        Instagram</a>, you can see that I try to shoot a wide variety of subjects. However, I find that my strengths lie with animals and architecture, as featured in my <a href="/shoot.html">gallery</a>.
			        </p>
			    </div>
			    </div>
			    <div class="col-md-6 col-sm-12 col-xs-12" id="photography">
			    	<img src="/assets/about/shoot.jpg" class="photography" alt="" data-mh="row-1">
			    </div>
			</div>
			<div class="row">
				<div class="col-md-push-6 col-md-6 col-sm-12 col-xs-12">
				<div class="well photography" data-mh="row-2">
			        <h2 class="section-heading">Fight</h2>
			        <p class="lead"> 
			        I started Muay Thai in 2015. I have since won 2 amateur belts with the Thai Boxing Association (USA). 
			        My experience as a competitor allows me to follow the rhythm of a fight in order to capture pivotal moments.
			        </p>
				</div>
				</div>
				<div class="col-md-pull-6 col-md-6 col-sm-12 col-xs-12" id="photography">
					<img src="/assets/about/fight.jpg" class="photography" alt="" data-mh="row-2">
				</div>
			</div>
			<div class="row">
				<div class="col-md-6 col-sm-12 col-xs-12">
				<div class="well photography" data-mh="row-3">
			        <h2 class="section-heading">Explore</h2>
			        <p class="lead">
			        Travel and Exploration was what inspired me to start shooting. 
			        I wanted to accurately share what the world has to offer, and realized that I needed to improve my photography in order to do justice to those experiences. </p>
			    </div>
			    </div>
			    <div class="col-md-6 col-sm-12 col-xs-12" id="photography">
					<img src="/assets/about/explore.jpg" class="photography" alt="" data-mh="row-3">
				</div>
			</div>
			<div class="row">
				<div class="copyright">
					<p>Photos on this page by: <a href="http://zhangling.photography" target="_blank">zhangling.photography</a> © </p>
				</div>
			</div>
		</div>
	    <div class="item contact-message" 
	    	style="
	    	background: url(/assets/about/contact.jpg)
	    	no-repeat;
	    	background-position: center center;
	    	background-size: cover;
	    	width:100%;
	    	height:100%;">
	        <h2>Get in Touch!</h2>
	        <h3> Collabs | Websites | Photoshoots | Fights </h3>
	        <hr class="intro-divider">
	        <ul class="list-inline contact-social-buttons">
	            <li>
	                <a href="https://instagram.com/{{ site.instagram_username }}" class="btn btn-default btn-lg" target="_blank"><i class="fa fa-instagram fa-fw"></i> <span class="network-name">Instagram</span></a>
	            </li>
	            <li>
	                <a href="https://github.com/{{ site.github_username }}" class="btn btn-default btn-lg" target="_blank"><i class="fa fa-github fa-fw"></i> <span class="network-name">Github</span></a>
	            </li>
	            <li>
	                <a href="https://linkedin.com/{{ site.linkedin_username }}" class="btn btn-default btn-lg" target="_blank"><i class="fa fa-linkedin fa-fw"></i> <span class="network-name">Linkedin</span></a>
	            </li>
	        </ul>
	    </div>
	    <!-- End item 2 -->
	    <!-- Carousel Indicators -->
	  	<ol class="carousel-indicators">
		    <li data-target="#aboutCarousel" data-slide-to="0" class="active">
		    </li>
		    <li data-target="#aboutCarousel" data-slide-to="1">	
		    </li>
		    <li data-target="#aboutCarousel" data-slide-to="2">	
		    </li>
	  	</ol>
	    </div>
    </div>
    <!-- End Carousel -->
    <!-- Carousel Controllers -->
    <a class="left carousel-control" href="#aboutCarousel" role="button" data-slide="prev">
    	<span class="glyphicon glyphicon-chevron-left" aria-hidden="true"></span>
    	<span class="sr-only">Previous</span>
    </a>
    <a class="right carousel-control" href="#aboutCarousel" role="button" data-slide="next">
    	<span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>
    	<span class="sr-only">Next</span>
    </a>
</div>