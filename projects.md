---
layout: landing
title: Projects
description: 
image: assets/images/pic07.jpg
nav-menu: yes
---

<!-- Banner -->
<!-- Note: The "styleN" class below should match that of the header element. -->
<section id="banner" class="style2">
	<div class="inner">
		<span class="image">
			<img src="{{ site.baseurl }}/{{ page.image }}" alt="" />
		</span>
		<header class="major">
			<h1>Projects</h1>
		</header>
		<div class="content">
			<p>{{ page.description }}</p>
		</div>
	</div>
</section>

<!-- Main -->
<div id="main">

<!-- One -->

<!-- Two -->
<section id="two" class="spotlights">
	{% for post in site.posts %}
	<section>
		<a href="{{post.url}}" class="image">
			<img src="{{post.image}}" alt="" data-position="center center" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>{{post.title}}</h3>
				</header>
				<p>{{post.excerpt}}</p>
				<ul class="actions">
					<li><a href="{{post.url}}" class="button">Learn more</a></li>
				</ul>
			</div>
		</div>
	</section>
	{% endfor %}
</section>


<!-- Three -->
<section id="three">
</section>

</div>
