<!-- ---
layout: page
title: Photography
permalink: /photography/
description: I like photography and editting videos. I'm far from a professional, I have a Fuji XS-10 camera but with only the most basic shot. This page includes photos I took and liked, hope you will also enjoy them!
nav: true
nav_order: 2
display_categories: [Photos]
horizontal: false
--- -->

<!-- 
<div class="photography">
{%- if site.enable_photography_categories and page.display_categories %}

  {%- for category in page.display_categories %}
  <h2 class="category">{{ category }}</h2>
  {%- assign categorized_photography = site.photography | where: "category", category -%}
  {%- assign sorted_photography = categorized_photography | sort: "importance" %}

  {% if page.horizontal -%}
  <div class="container">
    <div class="row row-cols-2">
    {%- for photography in sorted_photography -%}
      {% include pphotography_horizontal.html %}
    {%- endfor %}
    </div>
  </div>
  {%- else -%}
  <div class="grid">
    {%- for photography in sorted_photography -%}
      {% include photography.html %}
    {%- endfor %}
  </div>
  {%- endif -%}
  {% endfor %}

{%- else -%}

  {%- assign sorted_photography = site.photography | sort: "importance" -%}

  {% if page.horizontal -%}
  <div class="container">
    <div class="row row-cols-2">
    {%- for photography in sorted_photography -%}
      {% include photography_horizontal.html %}
    {%- endfor %}
    </div>
  </div>
  {%- else -%}
  <div class="grid">
    {%- for photography in sorted_photography -%}
      {% include photography.html %}
    {%- endfor %}
  </div>
  {%- endif -%}
{%- endif -%}
</div> -->
