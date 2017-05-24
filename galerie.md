---
layout: default
title: Galerie
---

<script src="https://cdnjs.cloudflare.com/ajax/libs/lightbox2/2.9.0/js/lightbox-plus-jquery.min.js"></script>
<link href="https://cdnjs.cloudflare.com/ajax/libs/lightbox2/2.9.0/css/lightbox.min.css" rel="stylesheet" />

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

<ol class="photo-gallery">
    {% for image in site.static_files %}
        {% if image.path contains 'assets/img/galerie/hemden/' %}
            <li>
                <a href="{{ site.baseurl }}{{ image.path }}" data-lightbox="Hemden" title="{{ image.basename }}">
                    <img src="{{ site.baseurl }}{{ image.path }}" alt="{{ image.basename }}" />
                </a>
            </li>
        {% endif %}
    {% endfor %}
</ol>
