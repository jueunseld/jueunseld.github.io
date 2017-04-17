---
layout: post
title: Galerie
images:
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

Gewebe mit Beton gefüllt. Stoff zu Stein erstarrt.

<ul class="photo-gallery">
  {% for image in page.images %}
    <li><img src="{{ image.image_path | prepend: site.baseurl }}" alt="{{ image.title}}"/></li>
  {% endfor %}
</ul>
