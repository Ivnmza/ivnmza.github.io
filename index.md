---
layout: home
title: Home
landing-title: I. MEZA
description: 
image: 
author: 
nav-menu: 
---

<!-- Banner -->
<section id="banner" class="major">
	<div class="inner">
		<header class="major">
			<h1>{{ page.landing-title }}</h1>
		</header>
		<div class="content">
			<p style="text-transform: uppercase;">{{ site.description }}</p>
			<ul class="actions">
				<li><a href="#one" class="button next scrolly">Click To Release</a></li>
			</ul>
		</div>
	</div>
</section>

<!-- Main -->
<div id="main">

<!-- One -->
{% include tiles.html %}

<!-- Two -->
<section id="two">
	<div class="inner">
		<video playsinline autoplay muted loop poster="{{ site.url }}{{ site.baseurl }}/assets/images/imezaBackground.png" id="bgvid">
	    <!-- <source src="icey.webm" type="video/webm"> -->
	    <source src="{{ site.url }}{{ site.baseurl }}/assets/images/imezaBackground.mp4" type="video/mp4">
		</video>
		<header class="major">
			<h1 style="font-size: 72px" id="manta">MANTA OPS</h1>
		</header>
		<div class="content">
			<p style="text-transform: uppercase;">Explorations In Cultural Technology</p>
		</div>
		<ul class="actions">
			<li><a href="http://www.mantaops.com" class="button next">See "Healing Winds" Collection</a></li>
		</ul>
	</div>
</section>

</div>

