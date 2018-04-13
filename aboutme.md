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

* Accomplished Data Science strategist and practitioner with 20 years of experience in quantitative research, advanced analytical and statistical techniques, experiments design, full-stack software engineering and hardware R&D. Hands-on machine learning, AI and IoT enthusiast. Have led multiple analyses of Big Data using cutting edge algorithms on distributed Computing Grids and in the Cloud. Currently wrangling data at General Motors Innovation Center in Austin, TX paving the path to GM vision of a world with zero crashes, zero emissions and zero congestion.

* Recognized team leader with over 15 years of management experience for projects in large national and international collaborations. An energetic team player well adapted to work in a diverse collaborative environment. Passionate mentor for data-oriented startups, speaker at local meetups and national conferences.

* Creative researcher and scholar with proven excellence in academic performance. Have earned a PhD degree in a data-heavy field of nuclear physics and contributed to the breakthrough discovery of the Nobel-prize winning Higgs boson (aka “God particle”). Author or co-author of more than 700 publications (h-index is 47).

* Active member of professional organizations as follows: American Statistical Association (ASA), Association for Computing Machinery (ACM), American Physical Society (APS), European Physical Society (EPS) and Society of Automotive Engineers (SAE).

<p align="center">
<a href="http://www.amstat.org"><img src="https://pakhot.in/img/Logo_ASA_512x512.png" alt="ASA" width="50"/></a>&nbsp;<a href="https://www.acm.org"><img src="https://pakhot.in/img/Logo_ACM_512x512.png" alt="ACM" width="50"/></a>&nbsp;<a href="https://www.aps.org"><img src="https://pakhot.in/img/Logo_APS_512x512.png" alt="APS" width="50"/></a>&nbsp;<a href="https://www.eps.org"><img src="https://pakhot.in/img/Logo_EPS_512x512.png" alt="SAE" width="50"/></a>&nbsp;<a href="https://www.sae.org"><img src="https://pakhot.in/img/Logo_SAE_512x512.png" alt="SAE" width="50"/></a>
</p>
