---
layout: gallery
page-title: shoot
---
<!-- Carousel with Thumbnails -->
<div id="background-carousel">
    <div id="myCarousel" class="carousel slide" data-ride="carousel" data-pause="null">
    {% assign path = 'assets/weboptimized/shoot'%}
      	<!-- Wrapper for slides -->
      	<div class="carousel-inner">
      	{% assign counter = 0 %}
		{% for image in site.static_files%}
			{% if image.path contains path %}
				{% if counter < 1 %}
				<div class="item active" style="background-image:url({{image.path}})"></div>
				{% assign counter = counter | plus:1 %}
				{% else %}
				<div class="item" style="background-image:url({{image.path}})"></div>
				{% assign counter = counter | plus:1 %}
				{% endif %}
			{% endif %}
		{% endfor %}
      	</div>
		<!-- Controls -->
	    <a class="left carousel-control" href="#myCarousel" role="button" data-slide="prev">
	    	<span class="glyphicon glyphicon-chevron-left" aria-hidden="true"></span>
	    	<span class="sr-only">Previous</span>
	    </a>
	    <a class="right carousel-control" href="#myCarousel" role="button" data-slide="next">
	    	<span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>
	    	<span class="sr-only">Next</span>
	    </a>
	    <!-- Indicators -->
	    <a class="btn btn-primary list-images" role="button" data-toggle="collapse" href="#thumbnail-collapse" aria-expanded="false" aria-controls="thumbnail-collapse">
		  Click to Toggle
		</a>
	    <div class="collapse" id="thumbnail-collapse">
		  	<ol class="carousel-indicators">
		  	{% assign counter = 0 %}
		  	{% for image in site.static_files%}
				{% if image.path contains path %}
				  	{% if counter < 1 %}
				    <li data-target="#myCarousel" data-slide-to="{{counter}}" class="active">
				    	<img src="{{image.path}}">
				    </li>
				  	{% assign counter = counter | plus:1 %}
				  	{% else %}
				    <li data-target="#myCarousel" data-slide-to="{{counter}}">
				    	<img src="{{image.path}}">
				    </li>
				  	{% assign counter = counter | plus:1 %}
				  	{% endif %}
			  	{% endif %}
		  	{% endfor %}
		  	</ol>
	  	</div>
	</div>
</div>