---
layout: works
page-title: works
---
<div class='work'>
<div class='cover'>
	{% for post in site.posts %}
	<a class='mobile-noclick' href="{{ post.url }}">
		<h4>{{post.title}}</h4>
		<img src="{{post.cover}}" alt="{{image.name}}" id="index{{forloop.index}}"/>
	</a>
	{% endfor %}
</div>
	<p style="text-align: center;">
		If you like my work, please show your support by making a donation of your choice.
		<br/>
		I do my work on a tight budget and pay out of pocket to travel to events.
		<br/>
		All contributions will be invested in gear for better photos in the future!
		<br/>
	</p>
	<form style="text-align: center;" action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_top">
	<input type="hidden" name="cmd" value="_s-xclick">
	<input type="hidden" name="hosted_button_id" value="89GFKBT95ZJT6">
	<input type="image" src="https://www.paypalobjects.com/en_US/i/btn/btn_donate_SM.gif" border="0" name="submit" alt="PayPal - The safer, easier way to pay online!">
	<img alt="" border="0" src="https://www.paypalobjects.com/en_US/i/scr/pixel.gif" width="1" height="1">
	</form>
	<!-- PayPal Logo -->
	<table class='paypal' border="0" cellpadding="10" cellspacing="0" align="center">
		<tr><td align="center"></td></tr>
		<tr><td align="center">
			<a href="https://www.paypal.com/webapps/mpp/paypal-popup" title="How PayPal Works" onclick="javascript:window.open('https://www.paypal.com/webapps/mpp/paypal-popup','WIPaypal','toolbar=no, location=no, directories=no, status=no, menubar=no, scrollbars=yes, resizable=yes, width=1060, height=700'); return false;"><img src="https://www.paypalobjects.com/webstatic/mktg/logo/AM_mc_vs_dc_ae.jpg" border="0" alt="PayPal Acceptance Mark"></a>
		</td></tr>
	</table><!-- PayPal Logo -->

</div>
