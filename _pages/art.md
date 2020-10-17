---
title: "Art Gallery"
permalink: /art/
sidebar:
  title: "Navigation"
  nav: "non-research"
gallery:
  - url: /assets/images/art/dragon.jpg
    image_path: /assets/images/art/dragon-th.jpg
    alt: "dragon"
    title: "Dragon"
  - url: /assets/images/art/freeze.jpg
    image_path: /assets/images/art/freeze-th.jpg
    alt: "freeze"
    title: "Freeze"
  - url: /assets/images/art/ghost.jpg
    image_path: /assets/images/art/ghost-th.jpg
    alt: "Ghost"
    title: "Ghost"
  - url: /assets/images/art/planet-queen.jpg
    image_path: /assets/images/art/planet-queen-th.jpg
    alt: "Planet Queen"
    title: "Planet Queen"
  - url: /assets/images/art/tasty.jpg
    image_path: /assets/images/art/tasty-th.jpg
    alt: "Tasty"
    title: "Tasty"
  - url: /assets/images/art/tread.jpg
    image_path: /assets/images/art/tread-th.jpg
    alt: "Tread"
    title: "Tread"
  - url: /assets/images/art/wild.jpg
    image_path: /assets/images/art/wild-th.jpg
    alt: "Wild"
    title: "Wild"
---
I enjoy doodling and making stupid pictures.
Below is a small selection.

{% include gallery id="gallery" layout="" %}
<!-- 
{% for image in site.static_files %}
    {% if image.path contains 'images/photos' %}
        <img src="{{ site.baseurl }}{{ image.path }}" alt="image" />
    {% endif %}
{% endfor %} -->

<!-- {% include gallery id="gallery" class="full" %}

{% for image in site.static_files %}
    {% if image.path contains 'images/photos' %}
        <img src="{{ site.baseurl }}{{ image.path }}" alt="image" />
    {% endif %}
{% endfor %} -->
