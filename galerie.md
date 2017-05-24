---
layout: post
title: Galerie
---

## Bilder

<ul class="photo-gallery">
    {% for image in site.static_files %}
        {% if image.path contains 'assets/img/galerie/bilder/' %}
            <li><img src="{{ site.baseurl }}{{ image.path }}" alt="{{ image.basename }}" />{{ image.basename  }}</li>
        {% endif %}
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
