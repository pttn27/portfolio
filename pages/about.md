---
layout: page
title: About
permalink: /about/
weight: 3
---

# **About Me**

Hi, I am **Nga** :wave:, <!-- **{{ site.author.name }}** -->

I’m a Media Computer Science student, currently interning at Bosch.IO as a UX/UI Designer. <br>
After the end of my internship, I am looking forward to start my career in UX Design in Berlin and will therefore pause my studies pursuing a master degree at TUD.

I am open for any job inquiries in the UX/UI/Interaction Design field in the Berlin area starting around October/November this year.

<!-- 
Through various university projects I’ve learned the basics of media design including UI and UX design but would love to get a deeper understanding of work flows and how to improve my designs. <br>
I have always admired a great functioning user experience and want to create designs that help people and that they love to use. I cannot wait to work on valuable and real projects :)
-->

{% include elements/button.html link="../assets/CV.pdf" text="Download CV" size="sm" target="_blank" %}

<div class="row">
{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
{% include about/skills.html title="Other Skills" source=site.data.other-skills %}
</div>

<div class="row">
{% include about/timeline.html %}
</div>

## Certificates

{% capture carousel_images %}
../assets/Coursera UMJRQRCVQJC9.png
{% endcapture %}
{% include elements/carousel.html %}