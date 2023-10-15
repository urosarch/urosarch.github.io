---
layout: page
title: photoportfolio
permalink: /photoportfolio/
---

{% for image in site.static_files %}
  {% if image.path contains 'photoportfolio' %}
    <div class="project">
      <div class="thumbnail">
        <a href="{{ site.baseurl }}{{ image.path }}">
          <img class="thumbnail" src="{{ site.baseurl }}{{ image.path }}" />
        </a>
      </div>
    </div>
  {% elsif image.path contains 'photoportfolio2' %}
    <div class="project-2">
      <div class="thumbnail-2">
        <a href="{{ site.baseurl }}{{ image.path }}">
          <img class="thumbnail-2" src="{{ site.baseurl }}{{ image.path }}" />
        </a>
      </div>
    </div>
  {% elsif image.path contains 'photoportfolio3' %}
    <div class="project-3">
      <div class="thumbnail-3">
        <a href="{{ site.baseurl }}{{ image.path }}">
          <img class="thumbnail-3" src="{{ site.baseurl }}{{ image.path }}" />
        </a>
      </div>
    </div>
  {% elsif image.path contains 'photoportfolio4' %}
    <div class="project-4">
      <div class="thumbnail-4">
        <a href="{{ site.baseurl }}{{ image.path }}">
          <img class="thumbnail-4" src="{{ site.baseurl }}{{ image.path }}" />
        </a>
      </div>
    </div>
  {% elsif image.path contains 'photoportfolio5' %}
    <div class="project-5">
      <div class="thumbnail-5">
        <a href="{{ site.baseurl }}{{ image.path }}">
          <img class="thumbnail-5" src="{{ site.baseurl }}{{ image.path }}" />
        </a>
      </div>
    </div>
  {% elsif image.path contains 'photoportfolio6' %}
    <div class="project-6">
      <div class="thumbnail-6">
        <a href="{{ site.baseurl }}{{ image.path }}">
          <img class="thumbnail-6" src="{{ site.baseurl }}{{ image.path }}" />
        </a>
      </div>
    </div>
  {% elsif image.path contains 'photoportfolio7' %}
    <div class="project-7">
      <div class="thumbnail-7">
        <a href="{{ site.baseurl }}{{ image.path }}">
          <img class="thumbnail-7" src="{{ site.baseurl }}{{ image.path }}" />
        </a>
      </div>
    </div>
  {% elsif image.path contains 'photoportfolio8' %}
    <div class="project-8">
      <div class="thumbnail-8">
        <a href="{{ site.baseurl }}{{ image.path }}">
          <img class="thumbnail-8" src="{{ site.baseurl }}{{ image.path }}" />
        </a>
      </div>
    </div>
  {% elsif image.path contains 'photoportfolio9' %}
    <div class="project-9">
      <div class="thumbnail-9">
        <a href="{{ site.baseurl }}{{ image.path }}">
          <img class="thumbnail-9" src="{{ site.baseurl }}{{ image.path }}" />
        </a>
      </div>
    </div>
  {% endif %}
{% endfor %}

<!-- this is for the lightbox -->
<script type="text/javascript" src="/js/lightbox.js"></script>
<link rel="stylesheet" href="/css/lightbox.css">
