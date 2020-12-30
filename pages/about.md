---
layout: page
title: About
permalink: /about/
weight: 5
---

# **About Me** 
<a class="btn btn-outline-primary float-right" href="http://bit.ly/34Tj6ju" role="button">Resume</a>
<br>
Hi I am **{{ site.author.name }}** :wave:,<br><br>
I am a Computer Science student with a deep love for Computer Vision. I love to be on both sides of the technology, research as well as development. But I am a bit biased towards research. Because the satisfaction of creating something entirely new is purely exceptional. I love to share knowledge and help others develop skills in this domain. Hence I lead the AI Club on the campus and write various educational and formal articles.
<div class="skill-bar skill-bar-blue"></div>
<br>
<br>
<div class="row">
{% include about/skills.html title="Computational Skills" source=site.data.programming-skills %}
{% include about/skills.html title="Other Skills" source=site.data.other-skills %}
</div>

<div class="row">
{% include about/timeline.html %}
</div>