---
layout: default
title: Nagamitesh Nagamuralee - Portfolio
permalink: /projects/
---
THIS PAGE IS NOT DONE, THESE ARE JUST EXAMPLES, RESUME PAGE IS DONE.
<div class="gallery-container">
<div class="project-gallery">
    {% for project in site.projects %}
      <div class="gallery-item">
        <a href="{{ project.url | relative_url }}">
          <img src="{{ project.image | relative_url }}" alt="{{ project.title }}" />
          <p>{{ project.title}}</p>
        </a>
      </div>
    {% endfor %}
</div>
</div>