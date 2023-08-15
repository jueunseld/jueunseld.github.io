---
type: news
published: true
hideDate: true
title: |-
  GALERIEimZWETSCHGENWEG  
---

Wir laden ein zum Besuch unserer Ausstellung

<h1 class="news-title">NEUE BILDER</h1>

**9. Sep. - 30.Sep. 2023**

Vernissage Samstag, 9. September, 16 Uhr

Die Ausstellung ist geöffnet Sa + So von 14 – 18 Uhr

sowie nach Vereinbarung

<br>
ZU GAST
<h3 class="news-title">BERND GOERING</h3>

**SKULPTUREN**


    <!-- Gallery Section -->
    <section id="new_paintings" class="content-section text-center">
        <h1>Neue Bilder 2019 – 2023</h1>
        <div class="gallery-section">
            <div class="container">
                <div class="photo-gallery">
                    {% for image in site.static_files %}
                    {% if image.path contains '/neue-bilder/' %}
                    {% unless image.basename contains 'thumbnail' %}
                    <div itemscope itemtype="https://schema.org/Painting">
                        <data hidden itemprop="name">{{ image.basename }}</data>
                        <data hidden itemprop="creator">Jürgen Unseld</data>
                        <a itemprop="url" href="{{ site.baseurl }}{{ image.path }}" data-lightbox="Galerie" title="{{ image.basename }}">
                            <img itemprop="thumbnailUrl" src="{{ site.baseurl }}{{ image.path }}-thumbnail.jpg" alt="{{ image.basename }}" />
                        </a>
                    </div>
                    {% endunless %}
                    {% endif %}
                    {% endfor %}
                </div>
            </div>
        </div>
    </section>