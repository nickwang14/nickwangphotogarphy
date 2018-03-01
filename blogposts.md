---
layout: blogposts
page-title: blogposts
---
<div class='blogposts'>
	<div class='cover'>
		{% for post in site.categories.fight %} 
		<a class='mobile-noclick' href="{{ post.url }}">
			<h4>{{post.title}}</h4>
			<img src="{{post.cover}}" alt="{{image.name}}" id="index{{forloop.index}}"/>
		</a>
		{% endfor %}
	</div>
{% include paypal.html %}
</div>
