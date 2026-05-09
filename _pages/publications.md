---
layout: page
permalink: /publications/
title: publications
description: peer-reviewed journal and conference papers, slides, and any other relevant information
years: [2024, 2023, 2022, 2021, 2020, 2019, 2016, 2015]
nav: true
rank: 1
---


<div class="publications">

{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>

- - -

<sub>
The material presented on this page is to ensure timely dissemination of scholarly and technical work. Copyright and all rights therein are retained by authors or by other copyright holders. All persons copying this information are expected to adhere to the terms and constraints invoked by each author's copyright. In most cases, these works may not be reposted without the explicit permission of the copyright holder.
</sub>