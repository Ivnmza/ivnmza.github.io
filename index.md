---
layout: home
title: Home
landing-title: Hi, my name is Ivan
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
		<header class="major">
			<h2>Wassup World</h2>
		</header>
		<p>I hail from Southern California</p>
		<ul class="actions">
			<li><a href="landing.html" class="button next">Now</a></li>
		</ul>
	</div>
</section>

</div>

