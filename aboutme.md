---
layout: page
title: Yuriy Pakhotin
subtitle: Senior Data Scientist | Ph.D.
---

<div class="row">
<div class="col-lg-8 col-lg-offset-2 col-md-10 col-md-offset-1">
<ul class="list-inline text-center footer-links">
  {%- for link in site.social-network-links -%}
    {%- assign curkey = link[0] -%}
    {%- assign element = site.data.SocialNetworks[curkey] -%}
    <li>
    {%- if curkey == 'rss' -%}
      <a href="{{ '/feed.xml' | prepend: site.baseurl }}" title="{{ element.name }}">
    {%- elsif curkey == 'yelp' -%}
      <a href="https://{{ site.social-network-links[curkey] }}.yelp.com" title="{{ element.name }}">
    {%- else -%}
      <a href="{{element.baseURL}}{{ site.social-network-links[curkey] }}" title="{{ element.name }}">
    {%- endif -%}
        <span class="fa-stack fa-lg" aria-hidden="true">
          <i class="fa fa-circle fa-stack-2x"></i>
          <i class="fa {{ element.icon }} fa-stack-1x fa-inverse"></i>
        </span>
        <span class="sr-only">{{ element.name }}</span>
      </a>
    </li>
  {%- endfor -%}
</ul>
</div>
</div>

 * Accomplished scientist with 20 years of experience in quantitative research, advanced analytical and statistical techniques, data modeling, prediction, simulation and visualization, software development and hardware R&D. Have led analyses of very large and complex datasets using cutting edge algorithms on distributed computing grids.

 * Recognized team leader with over 15 years of management experience for projects in large national and international collaborations. An energetic team player and passionate mentor well adapted to work in a diverse collaborative environment.

 * Creative scholar with proven excellence in academic performance. Have earned a PhD degree in a data-heavy field of physics and contributed to the breakthrough discovery of the Nobel-prize winning Higgs boson (aka “God particle”).

## Professional Organisations

<img src="./img/Logo_ASA_512x512.png" alt="ASA" style="width: 50px;"/>
