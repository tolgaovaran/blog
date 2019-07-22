---
title: Projects
layout: landing
description: 'See What i have done'
image: assets/images/pic07.jpg
nav-menu: true
---

<!-- Main -->
<div id="main">

<!-- One -->
 <section id="one">
	<div class="inner">
          {% for post in site.posts %}
	  {% if post.title != 404 %}
	  <header class="major">
	    <h1>{{ post.title }}</h1>
	  </header>
	  {% if post.image %}<span class="image main"><img src="{{ site.baseurl }}/{{ post.image }}" alt="" /></span>{% endif %}
	  {% if post.date %}<p>{{ post.date }}</p>{% endif %}
	  <p>{{ post.content }}</p>
	  {% endif %}
          {% endfor %}
	</div>
      </section>

</div>
<div>
	<h2>Does this update<h2>
	</div>
