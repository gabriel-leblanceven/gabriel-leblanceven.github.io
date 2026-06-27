---
permalink: /research/
title: ""
author_profile: false
hide_masthead: true
classes: wide
layout: single
---

<style>
.gle{font-family:'Public Sans',sans-serif;color:#14171C;max-width:1080px;margin:0 auto;}
.gle a{text-decoration:none;}
.gle__nav{display:flex;align-items:center;justify-content:space-between;padding:26px 56px;}
.gle__logo{font-family:'Space Mono',monospace;font-size:18px;font-weight:700;letter-spacing:0.42em;}
.gle__logo .g{color:#324f6b;}
.gle__logo .le{color:#fff;-webkit-text-stroke:0.9px #324f6b;}
.gle__navlinks{display:flex;gap:36px;font-family:'Space Mono',monospace;font-size:11.5px;letter-spacing:0.1em;text-transform:uppercase;}
.gle__navlinks a{color:#324f6b;text-decoration:none !important;}
.gle__navlinks a:hover,.gle__navlinks a.is-active{color:#c8921a;}
.gle__bar{height:3px;background:#c8921a;}
.gle__titleband{display:grid;grid-template-columns:1fr;border-bottom:1px solid #14171C;}
.gle__titlebody{padding:32px 56px 36px 56px;}
.gle__h1{font-family:'Newsreader',serif;font-size:40px;font-weight:500;line-height:1.05;color:#324f6b;margin:0;}
.gle__intro{font-size:15px;color:#5a6275;line-height:1.6;margin-top:12px;max-width:600px;}
.gle__row{display:grid;grid-template-columns:280px 1fr;border-bottom:1px solid #E3E5E9;}
.gle__rowlabel{padding:34px 0 34px 56px;font-family:'Space Mono',monospace;font-size:11px;letter-spacing:0.1em;text-transform:uppercase;color:#8a9099;}
.gle__rowbody{padding:14px 56px 20px 40px;}
.gle__item{padding:22px 0;border-bottom:1px solid #EDEEF1;}
.gle__item:last-child{border-bottom:none;}
.gle__ititle{font-family:'Newsreader',serif;font-size:21px;font-weight:500;line-height:1.3;color:#324f6b;}
.gle__byline{font-family:'Public Sans',sans-serif;font-style:italic;font-size:13px;color:#c8921a;margin-top:6px;}
.gle__abs{font-size:14.5px;color:#3a4048;line-height:1.6;margin-top:10px;max-width:640px;}
.gle__pdf{display:inline-block;font-family:'Space Mono',monospace;font-size:10.5px;letter-spacing:0.06em;text-transform:uppercase;color:#324f6b;border-bottom:1px solid #c8921a;margin-top:12px;padding-bottom:1px;}
.gle__pdf:hover{color:#c8921a;}
.gle__footer{display:flex;align-items:center;justify-content:space-between;padding:20px 56px 40px;font-family:'Space Mono',monospace;font-size:11px;letter-spacing:0.08em;color:#8a9099;border-top:1px solid #324f6b;}
@media(max-width:720px){.gle__titleband,.gle__row{grid-template-columns:1fr;}.gle__titlebody,.gle__rowbody{padding:20px 24px 24px;}.gle__rowlabel{padding:24px 0 0 24px;}.gle__nav,.gle__footer{padding-left:24px;padding-right:24px;}.gle__h1{font-size:32px;}}
.page,.page__inner-wrap,#main,article.page{max-width:100% !important;width:100% !important;padding:0 !important;float:none !important;}
.sidebar,.sidebar__right{display:none !important;}
.page__content{padding-left:0 !important;padding-right:0 !important;}
.page__hero{display:none !important;}
body{padding-top:0 !important;}
#masthead{display:none !important;}
.page__footer{display:none !important;}
.footer{display:none !important;}
.gle__logo a{text-decoration:none !important;color:inherit;}
.gle__logo a:hover .g{color:#c8921a;}
.gle__logo a:hover .le{color:transparent;-webkit-text-stroke:0.9px #c8921a;text-stroke:0.9px #c8921a;}
</style>

<div class="gle__nav">
  <div class="gle__logo"><a href="{{ '/' | relative_url }}"><span class="g">G</span><span class="le">LE</span></a></div>
  <nav class="gle__navlinks">
    <a href="{{ '/research/' | relative_url }}" class="is-active">Research</a>
    <a href="{{ '/talks/'    | relative_url }}">Talks</a>
    <a href="{{ '/teaching/' | relative_url }}">Teaching</a>
    <a href="{{ '/cv/'       | relative_url }}">CV</a>
  </nav>
</div>
<div class="gle__bar"></div>

<div class="gle">
  <div class="gle__titleband">
    <div class="gle__titlebody">
      <h1 class="gle__h1">Research</h1>
      <div class="gle__intro">My ongoing work in health economics, at the meeting point of epidemiology and public policy.</div>
    </div>
  </div>

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

  <div class="gle__footer">
    <span>gabriel.leblanc-even@univ-rennes.fr</span>
    <span>Rennes, France &middot; &copy; {{ 'now' | date: "%Y" }}</span>
  </div>
</div>
