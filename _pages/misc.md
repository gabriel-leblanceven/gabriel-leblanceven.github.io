---
permalink: /misc/
title: "Miscellaneous"
author_profile: false
hide_masthead: true
classes: wide
layout: single
sitemap: false
noindex: true
---

<style>
.gle{font-family:'Public Sans',sans-serif;color:#14171C;max-width:1080px;margin:0 auto;}
.gle a{text-decoration:none;}
.gle__nav{display:flex;align-items:center;justify-content:space-between;padding:26px 56px;}
.gle__navlinks{display:flex;gap:36px;font-family:'Space Mono',monospace;font-size:11.5px;letter-spacing:0.1em;text-transform:uppercase;}
.gle__navlinks a{color:#324f6b;text-decoration:none !important;}
.gle__navlinks a:hover{color:#c8921a;}
.gle__bar{height:3px;background:#c8921a;}
.gle__titleband{display:grid;grid-template-columns:280px 1fr;border-bottom:1px solid #14171C;}
.gle__titlebody{padding:32px 56px 36px 40px;}
.gle__h1{font-family:'Newsreader',serif;font-size:40px;font-weight:500;line-height:1.05;color:#324f6b;margin:0;}
.gle__intro{font-size:15px;color:#5a6275;line-height:1.6;margin-top:12px;max-width:600px;}
.gle__row{display:grid;grid-template-columns:280px 1fr;border-bottom:1px solid #E3E5E9;}
.gle__rowlabel{padding:34px 0 34px 56px;font-family:'Space Mono',monospace;font-size:11px;letter-spacing:0.1em;text-transform:uppercase;color:#8a9099;}
.gle__rowbody{padding:30px 56px 32px 40px;}
.gle .gle__text{font-size:16px;color:#2a2f36;line-height:1.65;max-width:620px;margin:0;}
.gle__footer{display:flex;align-items:center;justify-content:space-between;padding:20px 56px 40px;font-family:'Space Mono',monospace;font-size:11px;letter-spacing:0.08em;color:#8a9099;border-top:1px solid #324f6b;}
@media(max-width:720px){.gle__titleband,.gle__row{grid-template-columns:1fr;}.gle__titlebody,.gle__rowbody{padding:20px 24px 24px;}.gle__rowlabel{padding:24px 0 0 24px;}.gle__nav,.gle__footer{padding-left:24px;padding-right:24px;}.gle__h1{font-size:32px;}}
.page,.page__inner-wrap,#main,article.page{max-width:100% !important;width:100% !important;padding:0 !important;float:none !important;}
.sidebar,.sidebar__right{display:none !important;}
.page__content{padding-left:0 !important;padding-right:0 !important;}
.page__hero{display:none !important;}
.page__title{display:none !important;}
body{padding-top:0 !important;}
#masthead{display:none !important;}
.page__footer{display:none !important;}
.footer{display:none !important;}
</style>

<div class="gle__nav">
  {% include gle-logo.html %}
  <nav class="gle__navlinks">
    <a href="{{ '/research/' | relative_url }}">Research</a>
    <a href="{{ '/talks/'    | relative_url }}">Talks</a>
    <a href="{{ '/teaching/' | relative_url }}">Teaching</a>
    <a href="{{ '/cv/'       | relative_url }}">CV</a>
  </nav>
</div>
<div class="gle__bar"></div>

<div class="gle">
  <div class="gle__titleband">
    <div></div>
    <div class="gle__titlebody">
      <h1 class="gle__h1">Miscellaneous</h1>
      <div class="gle__intro">A few things that keep me busy outside research.</div>
    </div>
  </div>

  <div class="gle__row">
    <div class="gle__rowlabel">Art</div>
    <div class="gle__rowbody">
      <p class="gle__text">I have a soft spot for Impressionism and previously worked at the Mus&eacute;e d'Orsay, which is also where the monogram of this site comes from.</p>
    </div>
  </div>

  <div class="gle__row">
    <div class="gle__rowlabel">Rowing</div>
    <div class="gle__rowbody">
      <p class="gle__text">I row. Few things clear the mind like a session on the water.</p>
    </div>
  </div>

  <div class="gle__row">
    <div class="gle__rowlabel">Drawing</div>
    <div class="gle__rowbody">
      <p class="gle__text">I draw in my spare time.</p>
    </div>
  </div>

  <div class="gle__row">
    <div class="gle__rowlabel">Singing</div>
    <div class="gle__rowbody">
      <p class="gle__text">I used to sing in a choir, a great lesson in listening to others.</p>
    </div>
  </div>

  <div class="gle__row">
    <div class="gle__rowlabel">Plants</div>
    <div class="gle__rowbody">
      <p class="gle__text">I am a houseplant enthusiast with a particular interest in plant tissue culture: growing new plants from a few cells in sterile conditions. Lab protocols, it turns out, are not only for economists.</p>
    </div>
  </div>

  <div class="gle__footer">
    <span>gabriel.leblanc-even@univ-rennes.fr</span>
    <span>Rennes, France &middot; &copy; {{ 'now' | date: "%Y" }}</span>
  </div>
</div>
