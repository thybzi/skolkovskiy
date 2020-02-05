---
title: Портаж 
---

Тест 

{% include iframe-video_youtube.html id="UK-inwCLc0Y" %}

<div class="blog">
{% assign portazh_posts = site.portazh | order:"date" %}
{% for post in portazh_posts %}
{% include post-preview.html post=post subdir="portazh" %}
{% endfor %}
</div>
