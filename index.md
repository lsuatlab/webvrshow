---
layout: home
title: Home
landing-title: Immersive Expressions
description:
image:
author:
nav-menu:
---

<!-- Banner -->
<section id="banner" class="major">
	<div class="inner">
		<header class="major">
			<!-- <h1>{{ page.landing-title }}</h1> -->
			<h1><img alt="Immersive Expressions" src="assets/images/webwhite.svg"></h1>
		</header>
		<div class="content">
			<p style="text-transform: uppercase;">{{ site.description }}</p>
			<ul class="actions">
				<!-- <li><a href="#one" class="button next scrolly">Submit in	 Nov.</a></li> -->
				<li><a href="https://easychair.org/conferences/?conf=acmsigdac17ie" class="button next scrolly">Click to Submit</a></li>
			</ul>
		</div>
	</div>
</section>

<!-- Main -->
<div id="main">

<!-- Two -->
<section id="two">
	<div class="inner">
		<header class="major">
			<h2>Call for Work</h2>
		</header>

			{% include call.html %}

		<ul class="actions">
			<li><a href="https://easychair.org/conferences/?conf=acmsigdac17ie" class="button next">Click to Submit</a></li>
		</ul>
	</div>
</section>

<!-- One -->
{% include tiles.html %}

</div>
