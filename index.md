---
layout: page
title: Hello Internets!
tagline: Supporting tagline
---
{% include JB/setup %}

This is my awesome Homepage. 

Notice my template. 

No big deal. 

<img src="http://media1.giphy.com/media/8vpeyWA3OWOhG/200_s.gif">

Read on!

<hr>

<strong>All Posts</strong>
<ul>
{% assign posts_collate = site.posts %}
{% include JB/posts_collate %}
</ul>
