---
permalink: /
title: ""
excerpt: ""
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
.gle__logo .le{color:#fff;-webkit-text-stroke:0.9px #324f6b;text-stroke:0.9px #324f6b;}
.gle__navlinks{display:flex;gap:36px;font-family:'Space Mono',monospace;font-size:11.5px;letter-spacing:0.1em;text-transform:uppercase;}
.gle__navlinks a{color:#324f6b;text-decoration:none !important;}
.gle__navlinks a:hover,.gle__navlinks a.is-active{color:#c8921a;}
.gle__logo a{text-decoration:none !important;}
.gle__bar{height:3px;background:#c8921a;}
.gle__hero{display:grid;grid-template-columns:280px 1fr;border-bottom:1px solid #E3E5E9;}
.gle__photo{width:100%;height:100%;min-height:380px;object-fit:cover;border-right:1px solid #E3E5E9;display:block;background:#f2f3f5;}
.gle__herobody{padding:48px 56px 50px 40px;}
.gle__kicker{font-family:'Space Mono',monospace;font-size:11px;letter-spacing:0.1em;text-transform:uppercase;color:#c8921a;}
.gle__name{font-family:'Newsreader',serif;font-size:54px;font-weight:500;letter-spacing:-0.005em;line-height:1.0;margin:14px 0 0;color:#324f6b;}
.gle__affil{font-size:13.5px;color:#6a7078;line-height:1.6;margin-top:18px;}
.gle__lede{font-size:15.5px;line-height:1.65;color:#2a2f36;max-width:560px;margin-top:20px;}
.gle__links{display:flex;flex-wrap:wrap;gap:10px;margin-top:28px;}
.gle__btn{font-family:'Space Mono',monospace;font-size:11px;letter-spacing:0.08em;text-transform:uppercase;color:#324f6b;border:1px solid #d7dade;padding:9px 15px;}
.gle__btn--primary{border-color:#324f6b;}
.gle__btn:hover{background:#324f6b;color:#fff;border-color:#324f6b;}
.gle__row{display:grid;grid-template-columns:280px 1fr;border-bottom:1px solid #E3E5E9;}
.gle__row--now{border-bottom:1px solid #324f6b;}
.gle__rowlabel{padding:34px 0 34px 56px;font-family:'Space Mono',monospace;font-size:11px;letter-spacing:0.1em;text-transform:uppercase;color:#8a9099;}
.gle__rowlabel--now{color:#c8921a;}
.gle__rowbody{padding:32px 56px 34px 40px;}
.gle__text{font-size:15.5px;color:#2a2f36;line-height:1.65;max-width:620px;}
.gle__more{display:inline-block;font-family:'Space Mono',monospace;font-size:11.5px;letter-spacing:0.06em;text-transform:uppercase;color:#324f6b;margin-top:18px;border-bottom:1px solid #c8921a;padding-bottom:2px;}
.gle__more:hover{color:#c8921a;}
.gle__muted{color:#9aa3b0;}
.gle__footer{display:flex;align-items:center;justify-content:space-between;padding:20px 56px 40px;font-family:'Space Mono',monospace;font-size:11px;letter-spacing:0.08em;color:#8a9099;}
.page,.page__inner-wrap,.page__content,#main,article.page{max-width:100% !important;width:100% !important;padding:0 !important;float:none !important;}
.sidebar,.sidebar__right{display:none !important;}
@media (max-width:720px){
  .gle__hero,.gle__row{grid-template-columns:1fr;}
  .gle__photo{min-height:280px;border-right:none;border-bottom:1px solid #E3E5E9;}
  .gle__herobody,.gle__rowbody{padding:28px 24px;}
  .gle__rowlabel{padding:24px 0 0 24px;}
  .gle__nav,.gle__footer{padding-left:24px;padding-right:24px;}
  .gle__footer{flex-direction:column;gap:8px;align-items:flex-start;}
  .gle__name{font-size:40px;}
}
</style>

<div class="gle">

  <div class="gle__nav">
    <div class="gle__logo"><span class="g">G</span><span class="le">LE</span></div>
    <nav class="gle__navlinks">
      <a href="{{ '/research/' | relative_url }}">Research</a>
      <a href="{{ '/talks/' | relative_url }}">Talks</a>
      <a href="{{ '/teaching/' | relative_url }}">Teaching</a>
      <a href="{{ '/cv/' | relative_url }}">CV</a>
    </nav>
  </div>
  <div class="gle__bar"></div>

  <div class="gle__hero">
    <img class="gle__photo" src="{{ '/images/profile.jpg' | relative_url }}" alt="Gabriel Leblanc-Even">
    <div class="gle__herobody">
      <div class="gle__kicker">PhD Candidate in Economics</div>
      <h1 class="gle__name">Gabriel<br>Leblanc-Even</h1>
      <div class="gle__affil">CREM &middot; CNRS UMR 6211 &mdash; University of Rennes<br>Supervised by Josselin Thuilliez (CNRS)</div>
      <p class="gle__lede">Health economics at the edge of epidemiology and public policy. I study how environmental shocks and intergenerational dynamics shape health and socioeconomic outcomes &mdash; and how public policies interact in shaping it.</p>
      <div class="gle__links">
        <a class="gle__btn gle__btn--primary" href="{{ '/cv/' | relative_url }}">Curriculum Vitae</a>
        <a class="gle__btn" href="https://scholar.google.com/">Scholar</a>
        <a class="gle__btn" href="mailto:gabriel.leblanc-even@univ-rennes.fr">Email</a>
        <a class="gle__btn" href="https://www.linkedin.com/">LinkedIn</a>
        <a class="gle__btn" href="https://github.com/gabriel-leblanceven">GitHub</a>
      </div>
    </div>
  </div>

  <div class="gle__row">
    <div class="gle__rowlabel">Research</div>
    <div class="gle__rowbody">
      <p class="gle__text">My ongoing projects sit at the meeting point of health economics and epidemiology: how environmental shocks and intergenerational dynamics shape health, and how public policies interact &mdash; reinforcing or offsetting one another &mdash; in health-related decisions.</p>
      <a class="gle__more" href="{{ '/research/' | relative_url }}">More in Research &rarr;</a>
    </div>
  </div>

  <div class="gle__row">
    <div class="gle__rowlabel">Teaching</div>
    <div class="gle__rowbody">
      <p class="gle__text">Teaching assistant in microeconomics and applied econometrics at the University of Rennes. I like making empirical reasoning intuitive for first encounters with data. <span class="gle__muted">(replace with your own)</span></p>
      <a class="gle__more" href="{{ '/teaching/' | relative_url }}">More in Teaching &rarr;</a>
    </div>
  </div>

  <div class="gle__row">
    <div class="gle__rowlabel">Talks</div>
    <div class="gle__rowbody">
      <p class="gle__text">Presentations at CREM seminars and doctoral workshops. <span class="gle__muted">(replace with your own)</span></p>
      <a class="gle__more" href="{{ '/talks/' | relative_url }}">More in Talks &rarr;</a>
    </div>
  </div>

  <div class="gle__row gle__row--now">
    <div class="gle__rowlabel gle__rowlabel--now">Now</div>
    <div class="gle__rowbody">
      <p class="gle__text">Building a new environmental-exposure dataset &middot; rereading Deaton&rsquo;s <em>The Great Escape</em> &middot; Brittany by bike on weekends. <span class="gle__muted">(make this yours)</span></p>
    </div>
  </div>

  <div class="gle__footer">
    <span>gabriel.leblanc-even@univ-rennes.fr</span>
    <span>Rennes, France &middot; &copy; 2026</span>
  </div>

</div>
