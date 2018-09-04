---
layout: home
title: Lens by HTML5 UP
album: general
---

<!-- Thumbnail -->

<section id="thumbnails">{% for photo in  site.data.home.fotki %}
	<article>
		<a class="thumbnail" href="{{ photo.image }}" data-position="left center"><img src="{{ photo.tnailurl }}" alt="photo.name" /></a>
		<h2>{{ photo.title }}</h2>
		<p>{{ photo.name }}</p>
	</article>
{% endfor %}</section>

<!--<section id="thumbnails">{% for photo in site.photos %}
	<article>
		<a class="thumbnail" href="{{ photo.image }}" data-position="left center"><img src="{{ photo.thumbnail }}" alt="" /></a>
		<h2>{{ photo.title }}</h2>
		<p>{{ photo.caption }}</p>
	</article>
{% endfor %}</section>
-->
