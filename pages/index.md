---
layout: default
permalink: /
---

<meta name="description" content="My name is Dishant Parikh. I want to further the boundaries of what's possible with data science. I spend as much time as possible working with, different solutions, combining the power of genetic programming with deep learning.">

<meta name="keywords" content="{{ 'Dishant, parikh, dishant parikh, dishant ieee, Dishant, Parikh, DP, D Parikh, dishant gcet, dishant gtu, gcet, ieee, aic, ieee aic, ieee gcet sb, ieee aic, dishant aic, dishant ai, artificial intelligence, technical writer, dishant trn, the research nest, isro, disahnt isro, indian space research organisation' }}"/>

{% if page.summary %}
<meta name="description" content="{{ page.description | escape }}">
{% endif %}
{%if page.tags %}
<meta name="keywords" content="{{ page.keywords | join: ', ' | escape }}"/>
{%endif %}

{% seo %}
{% include landing.html %}