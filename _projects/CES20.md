---
title: APTIV CES 2020
layout: page
tools: [Unity3D, C#, UDP, ]
image: /assets/media/CES20/aptiv-ces2020-booth-displays.jpg
description: Contacted by APTIV to create 3 applications that help showcase their technology at CES20, Las Vegas.  
---

<div class="row">
	<div class="col-sm">
	
		<h2 class="row info role">Systems Programmer</h2>
		<a class="row info date">November 2019 - January 2020, Contract for APTIV</a>
		
		<div class="row info">	
			<a>
				With the aid of some coworkers from <b>Puredepth</b>(now closed down), we took on a contract from <b>APTIV</b>, a global tech innovation company(originally the mothership of Puredepth).
				My job was to focus on the technical software of the project, such as the integration of APTIV's proprietary 'Driver State Sensing' system,
				networking, file systems, video playback, and RS232 for HDMI switching.
			</a>
			<h5><b>THE PROJECT:</b></h5>
			<p>APTIV tasked us with producing an experience aid for their showcase at Consumer Electronics Showcase in Las Vegas 2020.</p>
			<p>We needed to create 3 applications:</p>
			
			<ul>
				<li>A Control Panel to help with HDMI switching and control the TV application through a lan network.</li>
				<li>A TV application that would play videos of different scenario situations based on what was chosen on the control panel. 
					The TV app would then broadcast to the network what scenario was active and the timestamps of the current video at a repeating interval.</li>
				<li>A Cluster(designed from 2019 CES project) that would take the information broadcast from the TV app and use it to determine when to enable/disable a real-time tracking warning for 'eyes on road'. </li>
			</ul>
			
			<p class="text-center">
			{% include elements/button.html link="https://www.aptiv.com/ces2020" text="More at APTIV" %}
			</p>
		</div>
		
		
	</div>
	<div class="col-lg">
		{% capture carousel_images %}/assets/media/CES20/aptiv-ces2020-booth-displays.jpg{% endcapture %}
		{% include elements/carousel.html  %}
	</div>
</div>

<div class="row">
		
</div>