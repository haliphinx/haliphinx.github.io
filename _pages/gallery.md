---
layout: single
title: "Gallery"
permalink: /gallery/
---

{% assign gallery_images = site.static_files
  | where_exp: "file", "file.path contains '/images/gallery/'"
  | where_exp: "file", "file.extname == '.jpg' or file.extname == '.jpeg' or file.extname == '.png' or file.extname == '.gif' or file.extname == '.webp'" %}

<div class="photo-gallery">
  {% if gallery_images.size == 0 %}
    <p>Add images to <code>images/gallery/</code> to populate this page.</p>
  {% else %}
    {% assign sorted_images = gallery_images | sort: "path" %}
    {% for file in sorted_images %}
      {% assign alt_text = file.basename | replace: "-", " " | replace: "_", " " %}
      <a href="{{ file.path | relative_url }}" class="image-popup" aria-label="Open {{ alt_text }}">
        <img src="{{ file.path | relative_url }}" alt="{{ alt_text }}">
      </a>
    {% endfor %}
  {% endif %}
</div>
