---
permalink: /research/
title: ""
author_profile: false
hide_masthead: true
classes: wide
layout: none
---

{% include gle-head.html active="research" %}

<div class="gle">

  <div class="gle__titleband">
    <div class="gle__titlelabel">Research</div>
    <div class="gle__titlebody">
      <h1 class="gle__h1">Research</h1>
      <div class="gle__intro">My ongoing work in health economics, at the meeting point of epidemiology and public policy.</div>
    </div>
  </div>

  {% comment %} Fixed section order; empty statuses are skipped automatically. {% endcomment %}
  {% assign order = "published,working,wip" | split: "," %}
  {% assign labels = "Published,Working papers,Work in progress" | split: "," %}

  {% for status in order %}
    {% assign group = site.data.papers | where: "status", status %}
    {% if group.size > 0 %}
      <div class="gle__row">
        <div class="gle__rowlabel">{{ labels[forloop.index0] }}</div>
        <div class="gle__rowbody">
          {% for p in group %}
            <div class="gle__item">
              <div class="gle__ititle">{{ p.title }}</div>
              <div class="gle__byline">{% if p.coauthors and p.coauthors != "" %}with {{ p.coauthors }}{% else %}Single-authored{% endif %}</div>
              <div class="gle__abs">{{ p.abstract }}</div>
              {% if p.pdf %}<a class="gle__pdf" href="{{ p.pdf | relative_url }}">Draft / PDF &darr;</a>{% endif %}
            </div>
          {% endfor %}
        </div>
      </div>
    {% endif %}
  {% endfor %}

</div>

{% include gle-foot.html %}
