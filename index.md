---
layout: landing
---
<html>
<section id="banner">
	<div class="inner">
		<h2>{{ site.title }}</h2>
		<p>{{ site.description | markdownify }}</p>
		<ul class="actions">
			<li><a href="#rsvp" class="button special">RSVP</a></li>
		</ul>
	</div>
	<a href="#about" class="more scrolly">About The Couple</a>
</section>

<section id="about" class="wrapper alt style2">
	{% include sections/about.html %}
</section>

<section id="rsvp" class="wrapper style1 special">
	{% include sections/rsvp.html %}
</section>

<section id="details" class="wrapper style3 special">
	{% include sections/details.html %}
</section>
</html>
