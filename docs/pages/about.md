---
layout: page
title: About
permalink: /about/
weight: 2
---

# **About Me**

Hi I am **{{ site.author.name }}**. I am an undergraduate CS student at University of California, Davis as well as a competetive cyclist currently racing for Team California in the DET ranks. In addition to my life as a student and a cylist, I enjoy taking photos on the side as a sort of creative outlet.

![Me]( ../assets/me.jpg "Me")

<br>
<div class="row">
{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
{% include about/skills.html title="Software Skills" source=site.data.software-skills %}
</div>

<div class="row">
{% include about/timeline.html %}
</div>