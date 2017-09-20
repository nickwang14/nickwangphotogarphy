---
layout: works
page-title: works
---
<div class='work'>
{% for post in site.posts %}
<div class='banner'
	style="
	background: url({{ post.banner }})
	no-repeat;
	background-position: center center;
	background-size: cover;
	width:100%;
	height:100%;">
	<a href="{{ post.url }}"><h1>{{post.title}}</h1></a>
</div>
{% endfor %}
</div>
