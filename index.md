---
layout: home
title: Home
landing-title: Welcome to my humble abode!
description:
image: 
author:
nav-menu:
---

<!-- Banner -->
<section id="banner" class="major">
	<div class="inner">
		<title>Design by J.Loo</title>
		<header class="major">
			<h1>{{ page.landing-title }}</h1>
		</header>
		<div class="content">
			<p style="text-transform: uppercase;">{{ site.description }}</p>
			<ul class="actions">
				<li><a href="#one" class="button next scrolly">View My Recent Work</a></li>
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
		<p>Feel free to drop me a message! I'd love to hear from you!</p>
	</div>
</section>

</div>
