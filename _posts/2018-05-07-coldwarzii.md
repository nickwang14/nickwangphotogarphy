---
layout: post
title:  "Cold Warz II"
date:   2018-05-07
categories: [fight, muaythai]
permalink: coldwarzii
cover: '/assets/works/coldwarzii/coldwarzii-1.jpg'
---
<link href="css/customimagegallery.css" rel="stylesheet">
<h1>{{ page.title }}</h1>
<h2>{{ page.date | date: '%B %d, %Y' }}</h2>
<p>A local gathering of some of the top talent in Toronto and the area. 
<a href="https://www.facebook.com/jordan.kravitz.14"> Kru Jordan</a> 
is a well known coach and promoter who spares no frills in his events. From well catered tables, to taking good care of his athletes and employees, he goes all out on making sure his event is top quality. 👌 </p>
<p>Find <a href="https://www.facebook.com/Cold-Warz-Muay-Thai-Fight-Promotion-2002128153366396/">Cold Warz</a> on Facebook and don't miss the next event!</p>
<!--<
section id="modal">
	{% for image in site.static_files %}
	    {% if image.path contains 'works/destiny4/' %}
	    <div class="modal fade" tabindex="-1" role="dialog" id="index{{forloop.index}}">
		  <div class="modal-dialog modal-lg">
		    <div class="modal-content">
			    <div class="modal-header">
			        <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
			    </div>
				<img src="{{image.path}}" alt="{{image.name}}" id="{{image.path}}"/>
			</div>
		  </div>
		</div><
	    {% endif %}
	{% endfor %}
</section>
-->
<section class="photos">
	{% for image in site.static_files %}
	    {% if image.path contains 'works/coldwarzii/' %}
	    <a href="#index{{forloop.index}}" class="mobile-noclick">
			<img src="{{image.path}}" alt="{{image.name}}" id="index{{forloop.index}}"/>
		</a>
		{% endif %}
	{% endfor %}
</section>