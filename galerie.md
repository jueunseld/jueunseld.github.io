---
layout: default
title: Galerie
images:
  - image_path: /assets/img/galerie/hemden/H001.jpg
    title: Apple Pie
  - image_path: /assets/img/galerie/hemden/H002.jpg
    title: Birthday Cake
  - image_path: /assets/img/galerie/hemden/H003.jpg
    title: Black Forest
---

<ul class="photo-gallery">
  {% for image in page.images %}
    <li><img src="{{ image.image_path | prepend: site.baseurl }}" alt="{{ image.title}}"/></li>
  {% endfor %}
</ul>