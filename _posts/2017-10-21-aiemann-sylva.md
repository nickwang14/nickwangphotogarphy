---
layout: posts
title:  "Zahabi Wedding"
date:   2017-10-21
categories: [wedding, events]
permalink: aiemann-sylva
cover: '/assets/works/aiemann-sylva/aiemann-sylva-22.jpg'
---
<link href="css/customimagegallery.css" rel="stylesheet">
<h1>{{ page.title }}</h1>
<h2>{{ page.date | date: '%B %d, %Y' }}</h2>
<h4>Aiemann ❤ Sylva</h4>
<p>From the groom's, to the bride's, followed by a tear-jerking ceremony and a dance party to remember.🤵👰</p>

<!--<
section id="modal">
	{% for image in site.static_files %}
	    {% if image.path contains 'works/aiemann-sylva/' %}
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
	    {% if image.path contains 'works/aiemann-sylva/' %}
	    <a href="#index{{forloop.index}}" class="mobile-noclick">
			<img src="{{image.path}}" alt="{{image.name}}" id="index{{forloop.index}}"/>
		</a>
		{% endif %}
	{% endfor %}
</section>

<p>
	If you like my work, please show your support by making a donation of your choice.
	<br/>
	I do my work on a tight budget and pay out of pocket to travel to events.
	<br/>
	All contributions will be invested in gear for better photos in the future!
	<br/>
</p>

<form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_top">
<input type="hidden" name="cmd" value="_s-xclick">
<input type="hidden" name="hosted_button_id" value="89GFKBT95ZJT6">
<input type="image" src="https://www.paypalobjects.com/en_US/i/btn/btn_donate_SM.gif" border="0" name="submit" alt="PayPal - The safer, easier way to pay online!">
<img alt="" border="0" src="https://www.paypalobjects.com/en_US/i/scr/pixel.gif" width="1" height="1">
</form>
<!-- PayPal Logo --><table border="0" cellpadding="10" cellspacing="0" align="center"><tr><td align="center"></td></tr><tr><td align="center"><a href="https://www.paypal.com/webapps/mpp/paypal-popup" title="How PayPal Works" onclick="javascript:window.open('https://www.paypal.com/webapps/mpp/paypal-popup','WIPaypal','toolbar=no, location=no, directories=no, status=no, menubar=no, scrollbars=yes, resizable=yes, width=1060, height=700'); return false;"><img src="https://www.paypalobjects.com/webstatic/mktg/logo/AM_mc_vs_dc_ae.jpg" border="0" alt="PayPal Acceptance Mark"></a></td></tr></table><!-- PayPal Logo -->