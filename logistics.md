---
layout: default
title: Open Science Codefest Venue
---

<div class="container-fluid featured over-image" id="location">
	<h2>Location</h2>
	<p>All codefest activities will be taking place at  <br/>The Fess Parker Hotel <br/>
	    633 East Cabrillo Boulevard <br/>
	    Santa Barbara, CA<br/>
	    93103</p>
    	<p><a href="http://www.fessparkersantabarbarahotel.com/map-and-directions/"> Detailed directions</a><i class="fa fa-external-link"></i></p>
		<script type="text/javascript" src="http://maps.google.com/maps/api/js?sensor=false"></script>
		<div>
			<div id="gmap_canvas"></div>
			<style>#gmap_canvas img{max-width:none!important;background:none!important}#maps{width:;font-size:10px;font-family:arial;text-align:right;}</style>
		</div>
		<script src="http://ajax.googleapis.com/ajax/libs/jquery/1.11.1/jquery.min.js"></script>
		<script type="text/javascript">jQuery(document).ready(function(){jQuery('.gmap').hide();jQuery("#maps span").click(function() {var $this = $(this);$this.next("div").fadeToggle();$('.gmap').not($this.next("div")).fadeOut();});});</script>
		<script type="text/javascript"> function init_map(){var myOptions = {zoom:14,center:new google.maps.LatLng(34.4169198,-119.67634700000002),mapTypeId: google.maps.MapTypeId.ROADMAP};map = new google.maps.Map(document.getElementById("gmap_canvas"), myOptions);marker = new google.maps.Marker({map: map,position: new google.maps.LatLng(34.4169198, -119.67634700000002)});google.maps.event.addDomListener(window, 'load', init_map);</script>
		<div id="maps"><span>Google Maps (C) 2014</span></div>		
</div>

<div class="container-fluid featured" id="details">
	<h2>Details</h2>
	<p><em>Dates</em> September 2-4, 2014</p>
	<p><em>Location</em> All Codefest activities will be taking place at the Fess Parker Doubletree hotel.</p>
	<p><em>Who</em> Anyone is welcome to attend.</p>
	<p><em>Fee</em> There is no registration fee for Open Science Codefest 2014.</p>
	<p><em>Food</em> Breakfast and lunch will be provided each day.</p>
	<p><em>Code of Conduct</em> Read the <a href="{{ BASE_PATH }}conduct.html">Open Science Codefest Code of Conduct</a></p>
</div>


<div class="container-fluid featured over-image" id="attractions">
	<h2>Local Attractions</h2>
</div>
<div class="container-fluid featured over-image grid" id="beaches">
	<p>Beaches</p>
</div>
<div class="container-fluid featured over-image grid" id="statest">
	<p>Shopping on State Street</p>
</div>
<div class="container-fluid featured over-image grid" id="stearnswharf">
	<p>Stearns Wharf</p>
</div>
<div class="container-fluid featured grid" id="more-attractions">
	<p><a href="http://www.fessparkersantabarbarahotel.com/discover-santa-barbara/attractions/">See more</a><i class="fa fa-external-link"></i></p>
</div>
