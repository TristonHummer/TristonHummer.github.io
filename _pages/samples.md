---
layout: page
permalink: /samples/
title: Samples
description:
nav: true
nav_order: 3
---

{% if site.data.samples.samples %}

<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  <!-- {% for sample in site.data.samples.samples %}
    <div> 
    {{ sample.name }}
    </div>
    <audio controls src="{% include dropbox.liquid url=sample.url %}" type="{{sample.type}}"></audio>

    
  {% endfor %} -->

<iframe src="https://whyp.it/embeds/track/330218?token=3Gfwc&showUser=false&showWhypBranding=false&transparentBackground=true" width="100%" height="200" scrolling="no" frameborder="0" loading="lazy"></iframe>



</div>
{% endif %}