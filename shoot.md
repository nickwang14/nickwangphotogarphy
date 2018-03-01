---
layout: carousel
page-title: shoot
---
<!-- Carousel with Thumbnails -->
<div id="background-carousel">
    <div id="myCarousel" class="carousel slide" data-ride="carousel" data-pause="hover">
    {% assign path = 'assets/weboptimized/shoot'%}
      	<!-- Wrapper for slides -->
      	<div class="carousel-inner">
      	{% assign counter = 0 %}
		{% for image in site.static_files%}
			{% if image.path contains path %}
				{% if counter < 1 %}
				<div class="carousel-item active" style="background-image:url({{image.path}})"></div>
				{% assign counter = counter | plus:1 %}
				{% else %}
				<div class="carousel-item" style="background-image:url({{image.path}})"></div>
				{% assign counter = counter | plus:1 %}
				{% endif %}
			{% endif %}
		{% endfor %}
      	</div>
		<!-- Controls -->
		<a class="carousel-control-prev" href="#myCarousel" role="button" data-slide="prev">
    		<span class="carousel-control-prev-icon" aria-hidden="true"></span>
			<span class="sr-only">Previous</span>
		</a>
	    <a class="carousel-control-next" href="#myCarousel" role="button" data-slide="next">
	    	<span class="carousel-control-next-icon" aria-hidden="true"></span>
	    	<span class="sr-only">Next</span>
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
