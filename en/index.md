---
layout: landing
lang: en
---
<html>
<section id="banner">
	<div class="inner">
		<h2>{{ site.title[page.lang] }}</h2>
		<p>{{ site.description[page.lang] | markdownify }}</p>
		<ul class="actions">
			<li><a href="#rsvp" class="button special">RSVP</a></li>
		</ul>
	</div>
	<a href="#venue" class="more scrolly">About The Venue</a>
</section>

<section id="venue" class="wrapper style3 special">
	{% include sections/en/venue.html %}
</section>

<section id="about" class="wrapper alt style2">
	{% include sections/en/about.html %}
</section>

<section id="rsvp" class="wrapper style1 special">
	{% include sections/en/rsvp.html %}
</section>

<section id="hotels" class="wrapper style3 special">
	{% include sections/en/hotels.html %}
</section>

</html>
