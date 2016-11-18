---
layout: home
title: Home
landing-title: Welcome to my humble abode!
description:
image: assets/images/Heartinhand.jpg
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
				<li><a href="#one" class="button next scrolly">View My Work</a></li>
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
			<h2>Curious About Me?</h2>
		</header>
		<p>Feel free to drop me a message or read my blog!</p>
		<ul class="actions">
			<li><a href="blog.html" class="button next">Go To Blog</a></li>
		</ul>
	</div>
</section>

</div>
