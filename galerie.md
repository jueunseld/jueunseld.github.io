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
hemden:
  - image_path: /assets/img/galerie/hemden/H001.jpg
    title: Betonhemd
  - image_path: /assets/img/galerie/hemden/H002.jpg
    title: Betonhemd
  - image_path: /assets/img/galerie/hemden/H003.jpg
    title: Betonhemd
    
  - image_path: /assets/img/galerie/hemden/H010.jpg
    title: Betonhemd
  - image_path: /assets/img/galerie/hemden/H009.jpg
    title: Betonhemd
  - image_path: /assets/img/galerie/hemden/H004.jpg
    title: Betonhemd
    
  - image_path: /assets/img/galerie/hemden/H005.jpg
    title: Betonhemd
  - image_path: /assets/img/galerie/hemden/H006.jpg
    title: Betonhemd
  - image_path: /assets/img/galerie/hemden/H007.jpg
    title: Betonhemd
    
  - image_path: /assets/img/galerie/hemden/H008.jpg
    title: Betonhemd
  - image_path: /assets/img/galerie/hemden/H011.jpg
    title: Betonhemd
  - image_path: /assets/img/galerie/hemden/H018.jpg
    title: Betonhemd
    
  - image_path: /assets/img/galerie/hemden/H012.jpg
    title: Betonhemd
  - image_path: /assets/img/galerie/hemden/H013.jpg
    title: Betonhemd
  - image_path: /assets/img/galerie/hemden/H014.jpg
    title: Betonhemd

  - image_path: /assets/img/galerie/hemden/H016.jpg
    title: Betonhemd
  - image_path: /assets/img/galerie/hemden/H017.jpg
    title: Betonhemd
  - image_path: /assets/img/galerie/hemden/H015.jpg
    title: Betonhemd

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
  {% for image in page.hemden %}
    <li><img src="{{ image.image_path | prepend: site.baseurl }}" alt="{{ image.title}}"/></li>
  {% endfor %}
</ul>
