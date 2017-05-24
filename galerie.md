---
layout: post
title: Galerie

bilder:
  - image_path: /assets/img/galerie/OhneTitel80x80.jpg
    title: Ohne Titel 2016, 80 x 80 
  - image_path: /assets/img/galerie/OhneTitel150x140.jpg
    title: Ohne Titel 2016, 150 x 140
  - image_path: /assets/img/galerie/IMG_1894bearb.jpg
    title: Und ach der Himmel so blau (3) 2016, 80 x 65

---

## Bilder

<ul class="photo-gallery">
  {% for image in page.bilder %}
    <li><img src="{{ image.image_path | prepend: site.baseurl }}" alt="{{ image.title}}"/>{{ image.title}}</li>
  {% endfor %}
</ul>

## Beton

Gewebe mit Beton gefüllt. Stoff zu Stein erstarrt.

<ul class="photo-gallery">
    {% for image in site.static_files %}
        {% if image.path contains 'assets/img/galerie/hemden/' %}
            <li><img src="{{ site.baseurl }}{{ image.path }}" alt="{{ image.basename }}" />{{ image.basename  }}</li>
        {% endif %}
    {% endfor %}
</ul>
