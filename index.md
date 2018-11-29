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
	<a href="#venue" class="more scrolly">About The Venue</a>
</section>

<section id="venue" class="wrapper style3 special">
	{% include sections/venue.html %}
</section>

<section id="about" class="wrapper alt style2">
	{% include sections/about.html %}
</section>

<section id="rsvp" class="wrapper style1 special">
	{% include sections/rsvp.html %}
</section>


</html>
