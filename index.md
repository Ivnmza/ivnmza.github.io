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
		<a-scene>
	      <a-assets>
	        <a-mixin id="board" geometry="depth: .05; height: 1; width: 6" material="shader: flat"
	                 pivot="0 0.5 0" position="0 -1 0"></a-mixin>
	        <a-mixin id="unhinge" attribute="rotation" to="0 0 0" dur="1000" fill="both"></a-mixin>
	        <img id="shadow" src="{{ site.url }}{{ site.baseurl }}/assets/images/radial-shadow-2.png">
	      </a-assets>

	      <!-- Series of nested boards that unfold one by one. -->
	      <a-entity position="0 0 -8" scale="1 1 1">
	        <!-- Animate rotation and position of group for extra visual flair. -->
	        <a-animation attribute="position" to="0 5 -8" dur="2000"></a-animation>
	        <a-animation attribute="rotation" from="0 60 0" to="0 30 0" dur="2500"></a-animation>

	        <!-- Pivot and position are used to set the "hinge" of each board to it's top edge. -->
	        <a-box mixin="board" color="#F16745">
	          <a-animation mixin="unhinge" from="-20 0 0" delay="1000"></a-animation>

	          <a-box mixin="board" color="#FFC65D">
	            <a-animation mixin="unhinge" from="-175 0 0" delay="250"></a-animation>

	            <a-box mixin="board" color="#7BC8A4">
	              <a-animation mixin="unhinge" from="-180 0 0" delay="500"></a-animation>

	              <a-box mixin="board" color="#4CC3D9">
	                <a-animation mixin="unhinge" from="-180 0 0" delay="750"></a-animation>

	                <a-box mixin="board" color="#93648D">
	                  <a-animation mixin="unhinge" from="-180 0 0" delay="1000"></a-animation>
	                </a-box>
	              </a-box>
	            </a-box>
	          </a-box>
	        </a-box>
	      </a-entity>

	      <a-image position="0 -1 0" src="#shadow" rotation="-90 0 0" scale="6 6 6"></a-image>
	      <a-sky color="#ECECEC"></a-sky>
	      <a-light type="directional" color="#fff" intensity="0.2" position="-1 2 1"></a-light>
	      <a-light type="ambient" color="#fff"></a-light>
	    </a-scene>
		<header class="major">
			<h1 style="font-size: 72px" id="manta">MANTA OPS</h1>
		</header>
		<div class="content">
			<p style="text-transform: uppercase;">Explorations In Culutural Technology</p>
		</div>
		<ul class="actions">
			<li><a href="http://www.mantaops.com" class="button next">See "Healing Winds" Collection</a></li>
		</ul>
	</div>
</section>

</div>

