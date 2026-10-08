---
layout: single
title: "About Me"
permalink: /
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<div id="about"></div>

Hi, I'm Jihyeon (Jennie) Kim!

I am currently a Platform Engineer at Hyundai Motor Group, working on large-scale data infrastructure and streaming systems.

My research interests focus on understanding human behavior in digital environments through large-scale interaction data. I am particularly interested in identifying behavioral patterns, exploring how they relate to people's needs and experiences, and how these insights can inform human-centered technologies. Social media and online communities are important areas of interest, with health and well-being as a preferred application domain.

I received both my B.S. and M.S. degrees in Computer Science from Ewha Womans University, South Korea. My academic research has included sentiment analysis of online health communities, people's experiences with digital media, and wearable technologies for exercise support.

Previously, I worked as a Big Data Engineer in the United States, developing and operating large-scale data processing systems.

## Research Interests

Human-Centered Computing; large-scale digital interaction data; computational and statistical analysis of human behavior. Social media and online communities are key contexts of interest, with health and well-being as a preferred application domain.

## Selected Work

### Academic research

- **Online health communities and sentiment analysis:** [EmoWei](https://doi.org/10.1109/IRI.2019.00060) explores emotion-oriented weight management through sentiment analysis.
- **Wearable technologies for exercise support:** [Self-Training Healthcare System Using Multi-Communication Wearable Devices](https://www.dbpia.co.kr/journal/articleDetail?nodeId=NODE07322685).
- **Biomedical text analysis:** [Trends in Genomics & Informatics](https://doi.org/10.5808/GI.2019.17.3.e25), a statistical review of publications, genes, and document clusters.

### Data engineering

My professional work includes large-scale data infrastructure and streaming systems, as well as the development and operation of large-scale data processing systems.

## Publications

<div class="publication-list">
{% include base_path %}
{% for category in site.publication_category %}
{% assign title_shown = false %}
{% for post in site.publications reversed %}
{% if post.category != category[0] %}{% continue %}{% endif %}
{% unless title_shown %}
<h3>{{ category[1].title }}</h3>
{% assign title_shown = true %}
{% endunless %}
{% include archive-single.html %}
{% endfor %}
{% endfor %}

</div>

### Patents

*Details pending confirmation.*

## Experience & Education
{: #experience}

### Professional experience

- **Platform Engineer — Hyundai Motor Group**  
  Current role working on large-scale data infrastructure and streaming systems.
- **Big Data Engineer — United States**  
  Previous role developing and operating large-scale data processing systems.

### Education

- **M.S. in Computer Science — Ewha Womans University, South Korea**
- **B.S. in Computer Science — Ewha Womans University, South Korea**

## CV

*PDF to be added.*
