---
layout: default
images:
  - image_path: /assets/img/gallerie/hemden/H001.jpg
    title: Apple Pie
  - image_path: /assets/img/gallerie/hemden/H002.jpg
    title: Birthday Cake
  - image_path: /assets/img/gallerie/hemden/H003.jpg
    title: Black Forest
---

<ul class="photo-gallery">
  {% for image in page.images %}
    <li><img src="{{ image.image_path }}" alt="{{ image.title}}"/></li>
  {% endfor %}
</ul>