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
.gle__logo a{text-decoration:none !important;color:inherit;}
.gle__logo a:hover .g{color:#c8921a;}
.gle__logo a:hover .le{color:transparent;-webkit-text-stroke:0.9px #c8921a;text-stroke:0.9px #c8921a;}
.gle__bar{height:3px;background:#c8921a;}
.gle__hero{display:grid;grid-template-columns:280px 1fr;border-bottom:1px solid #E3E5E9;}
.gle__photo{width:100%;height:100%;min-height:380px;object-fit:cover;object-position:center 20%;border-right:1px solid #E3E5E9;display:block;background:#f2f3f5;}
.gle__herobody{padding:28px 56px 50px 40px;}
.gle__kicker{font-family:'Space Mono',monospace;font-size:10px;letter-spacing:0.1em;text-transform:uppercase;color:#c8921a;line-height:2;}
.gle__name{font-family:'Newsreader',serif;font-size:52px;font-weight:500;letter-spacing:-0.005em;line-height:1.0;margin:14px 0 0;color:#324f6b;}
.gle__supervisor{font-size:14px;color:#324f6b;line-height:1.5;margin-top:14px;font-style:italic;margin-bottom:16px;}
.gle .gle__lede{font-size:16px;line-height:1.65;color:#2a2f36;max-width:560px;margin-top:0;text-align:justify;}
.gle__links{display:flex;flex-wrap:wrap;gap:10px;margin-top:28px;}
.gle__btn{font-family:'Space Mono',monospace;font-size:10px;letter-spacing:0.08em;text-transform:uppercase;color:#324f6b;border:1px solid #324f6b;padding:9px 15px;text-decoration:none !important;}
.gle__btn:hover{background:#324f6b;color:#c8921a !important;border-color:#324f6b;text-decoration:none !important;}
.gle__row{display:grid;grid-template-columns:280px 1fr;border-bottom:1px solid #E3E5E9;}
.gle__row--now{border-bottom:1px solid #324f6b;background:rgba(200,146,26,0.06);}
.gle__rowlabel{padding:34px 0 34px 56px;font-family:'Space Mono',monospace;font-size:10px;letter-spacing:0.1em;text-transform:uppercase;color:#8a9099;}
.gle__rowlabel--now{color:#c8921a;}
.gle__row--now .gle__rowbody{min-width:0;}
.gle__nowctl{display:flex;align-items:center;justify-content:center;gap:14px;max-width:620px;margin-top:10px;}
.gle__nowbtn{display:flex;align-items:center;justify-content:center;width:22px;height:22px;padding:0;border:1px solid rgba(50,79,107,0.3);border-radius:50%;background:none;color:rgba(50,79,107,0.55);cursor:pointer;transition:border-color .2s,color .2s;}
.gle__nowbtn svg{display:block;}
.gle__nowbtn:hover,.gle__nowbtn:focus-visible{border-color:#c8921a;color:#c8921a;}
.gle__nowdots{display:flex;gap:6px;}
.gle__nowdots i{display:block;width:7px;height:7px;border-radius:50%;border:1px solid #324f6b;box-sizing:border-box;transition:background .2s,border-color .2s;}
.gle__nowdots i.is-active{background:#c8921a;border-color:#c8921a;}
.gle__slides{display:flex;align-items:flex-start;transition:height .3s;overflow-x:auto;scroll-snap-type:x mandatory;scrollbar-width:none;outline:none;}
.gle__slides::-webkit-scrollbar{display:none;}
.gle__slide{flex:0 0 100%;scroll-snap-align:start;}
.gle__rowbody{padding:32px 56px 34px 40px;}
.gle .gle__text{font-size:16px;color:#2a2f36;line-height:1.65;max-width:620px;text-align:justify;}
.gle__row--link{grid-template-columns:280px 1fr auto;color:inherit;text-decoration:none !important;}
.gle__go{display:flex;align-items:center;justify-content:center;padding:0 40px;}
.gle__go svg{display:block;color:#324f6b;transition:color .2s;}
.gle__go-arrow{transition:transform .2s;}
.gle__go text{opacity:0;transition:opacity .25s;}
.gle__row--link:hover .gle__go text,.gle__row--link:focus-visible .gle__go text{opacity:1;}
@media (hover:none){.gle__go text{opacity:1;}}
.gle__row--link:hover .gle__go svg,.gle__row--link:focus-visible .gle__go svg{color:#c8921a;}
.gle__row--link:hover .gle__go-arrow,.gle__row--link:focus-visible .gle__go-arrow{transform:translateX(1px);}
.gle__next{margin-top:14px;padding:12px 14px;border-left:2px solid #c8921a;background:rgba(200,146,26,0.08);}
.gle__next-label{display:block;font-family:'Space Mono',monospace;font-size:10px;letter-spacing:0.1em;text-transform:uppercase;color:#c8921a;}
.gle__next-title{display:block;font-family:'Newsreader',serif;font-size:17px;font-weight:500;color:#324f6b;line-height:1.3;margin-top:4px;}
.gle__next-meta{display:block;font-size:13px;font-style:italic;color:#6a7078;margin-top:2px;}
.gle__muted{color:#9aa3b0;}
.gle__footer{display:flex;align-items:center;justify-content:space-between;padding:20px 56px 40px;font-family:'Space Mono',monospace;font-size:11px;letter-spacing:0.08em;color:#8a9099;}
.page,.page__inner-wrap,#main,article.page{max-width:100% !important;width:100% !important;padding:0 !important;float:none !important;}
.sidebar,.sidebar__right{display:none !important;}
.page__content{padding-left:0 !important;padding-right:0 !important;}
.page__hero{display:none !important;}
body{padding-top:0 !important;}
#masthead{display:none !important;}
.page__footer{display:none !important;}
.footer{display:none !important;}
@media (max-width:720px){
  .gle .gle__row--link{grid-template-columns:1fr auto;}
  .gle__row--link .gle__rowlabel{grid-column:1 / -1;}
  .gle__go{padding:0 20px 0 0;}
  .gle__hero,.gle__row{grid-template-columns:1fr;}
  .gle__herobody,.gle__rowbody{padding:28px 24px;}
  .gle__rowlabel{padding:24px 0 0 24px;}
  .gle__nav,.gle__footer{padding-left:24px;padding-right:24px;}
  .gle__footer{flex-direction:column;gap:8px;align-items:flex-start;}
  /* Phone hero: small photo beside the name, the rest of the intro below at full width */
  .gle__hero{grid-template-columns:112px 1fr;column-gap:16px;padding:24px 24px 28px;}
  .gle__photo{grid-row:1;width:112px;height:150px;min-height:0;object-position:center 15%;border:1px solid #E3E5E9;}
  .gle__herobody{display:contents;}
  .gle__name{grid-column:2;grid-row:1;align-self:center;margin:0;font-size:30px;}
  .gle__herobody > *:not(.gle__name){grid-column:1 / -1;}
  .gle__herobody > .gle__kicker:first-of-type{margin-top:20px !important;}
}
html, body{margin:0 !important;padding:0 !important;}
</style>

<div class="gle__nav">
  {% include gle-logo.html %}
  <nav class="gle__navlinks">
    <a href="{{ '/research/' | relative_url }}">Research</a>
    <a href="{{ '/talks/' | relative_url }}">Talks</a>
    <a href="{{ '/teaching/' | relative_url }}">Teaching</a>
    <a href="{{ '/cv/' | relative_url }}">CV</a>
  </nav>
</div>
<div class="gle__bar"></div>

<div class="gle">
  <div class="gle__hero">
    <img class="gle__photo" src="{{ '/images/profile.jpg' | relative_url }}" alt="Gabriel Leblanc-Even">
    <div class="gle__herobody">
      <h1 class="gle__name">Gabriel <span style="white-space:nowrap;">Leblanc-Even</span></h1>
      <div class="gle__kicker" style="margin-top: 14px;">PhD Candidate in Economics</div>
      <div class="gle__kicker">CREM &middot; CNRS UMR 6211 &middot; University of Rennes</div>
      <div class="gle__supervisor">Supervised by Josselin Thuilliez (DR CNRS)</div>
      <p class="gle__lede">My research examines how environmental shocks and intergenerational dynamics influence individuals' health and shape their socioeconomic outcomes. I am also interested in the interaction of multiple public policies &mdash; not only evaluating their individual effects but also investigating their combined or offsetting impacts, particularly on health-related decisions.</p>
      <div class="gle__links">
        <a class="gle__btn" href="{{ '/cv/' | relative_url }}">CV</a>
        <a class="gle__btn" href="mailto:gabriel.leblanc-even@univ-rennes.fr">Email</a>
        <a class="gle__btn" href="https://www.linkedin.com/">LinkedIn</a>
        <a class="gle__btn" href="https://github.com/gabriel-leblanceven">GitHub</a>
      </div>
    </div>
  </div>

  <!-- Research / Talks / Teaching rows link to their pages as a whole; the circled arrow on the right matches the Now control -->
  <a class="gle__row gle__row--link" href="{{ '/research/' | relative_url }}" aria-label="More in Research">
    <div class="gle__rowlabel">Research</div>
    <div class="gle__rowbody">
      <p class="gle__text">My primary research agenda lies in health economics, closely connected to epidemiology, with a strong interest in development economics and how public policies can shape human societies.</p>
    </div>
    <span class="gle__go" aria-hidden="true"><svg width="60" height="66" viewBox="0 0 60 66" fill="none" focusable="false"><defs><path id="gle-explore-research" d="M5,42 A25,25 0 0 1 55,42"/></defs><text font-family="Space Mono, monospace" font-size="8.5" letter-spacing="1.8" fill="currentColor"><textPath href="#gle-explore-research" startOffset="50%" text-anchor="middle">EXPLORE</textPath></text><circle cx="30" cy="42" r="18.25" stroke="currentColor" stroke-width="1.5"/><g class="gle__go-arrow"><path d="M23.5 42 H36.5 M32 37.5 L36.5 42 L32 46.5" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/></g></svg></span>
  </a>

  <a class="gle__row gle__row--link" href="{{ '/talks/' | relative_url }}" aria-label="More in Talks">
    <div class="gle__rowlabel">Talks</div>
    <div class="gle__rowbody">
      {% assign upcoming = site.data.talks | where_exp: "t", "t.upcoming == true" %}
      <p class="gle__text">This section lists the seminars, conferences and workshops where I have presented my work.{% if upcoming.size == 0 %} Further presentations are scheduled for the current year.{% endif %}</p>
      {% for t in upcoming limit:2 %}
        <div class="gle__next">
          <span class="gle__next-label">Upcoming</span>
          <span class="gle__next-title">{{ t.title }}</span>
          <span class="gle__next-meta">{% if t.date %}{{ t.date }} &middot; {% endif %}{{ t.place }}</span>
        </div>
      {% endfor %}
    </div>
    <span class="gle__go" aria-hidden="true"><svg width="60" height="66" viewBox="0 0 60 66" fill="none" focusable="false"><defs><path id="gle-explore-talks" d="M5,42 A25,25 0 0 1 55,42"/></defs><text font-family="Space Mono, monospace" font-size="8.5" letter-spacing="1.8" fill="currentColor"><textPath href="#gle-explore-talks" startOffset="50%" text-anchor="middle">EXPLORE</textPath></text><circle cx="30" cy="42" r="18.25" stroke="currentColor" stroke-width="1.5"/><g class="gle__go-arrow"><path d="M23.5 42 H36.5 M32 37.5 L36.5 42 L32 46.5" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/></g></svg></span>
  </a>

  <a class="gle__row gle__row--link" href="{{ '/teaching/' | relative_url }}" aria-label="More in Teaching">
    <div class="gle__rowlabel">Teaching</div>
    <div class="gle__rowbody">
      <p class="gle__text">I teach courses ranging from core economics to more advanced topics closer to my research, including econometrics and health economics.</p>
    </div>
    <span class="gle__go" aria-hidden="true"><svg width="60" height="66" viewBox="0 0 60 66" fill="none" focusable="false"><defs><path id="gle-explore-teaching" d="M5,42 A25,25 0 0 1 55,42"/></defs><text font-family="Space Mono, monospace" font-size="8.5" letter-spacing="1.8" fill="currentColor"><textPath href="#gle-explore-teaching" startOffset="50%" text-anchor="middle">EXPLORE</textPath></text><circle cx="30" cy="42" r="18.25" stroke="currentColor" stroke-width="1.5"/><g class="gle__go-arrow"><path d="M23.5 42 H36.5 M32 37.5 L36.5 42 L32 46.5" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/></g></svg></span>
  </a>

  <!-- Now block: slides cycled by light prev/next circles around centred dots (both loop); the row label follows the current slide's data-label -->
  <div class="gle__row gle__row--now">
    <div class="gle__rowlabel gle__rowlabel--now" id="gle-now-label">Now</div>
    <div class="gle__rowbody">
      <div class="gle__slides" id="gle-slides" tabindex="0" role="region" aria-roledescription="carousel" aria-label="Now and more">
        <div class="gle__slide" data-label="Now" role="group" aria-roledescription="slide" aria-label="1 of 2">
          <p class="gle__text">Mostly writing my dissertation and enjoying Brittany. One of these is more relaxing than the other.</p>
        </div>
        <div class="gle__slide" data-label="The Monogram" role="group" aria-roledescription="slide" aria-label="2 of 2">
          <p class="gle__text">If you've been wondering about the logo in the top-left corner: it is my personal monogram (GLE). As an art lover with a soft spot for Impressionism &mdash; and having previously worked at the Mus&eacute;e d'Orsay &mdash; I adapted it from Henri de Toulouse-Lautrec's iconic circular monogram. It is a small personal, historical touch on an otherwise academic website. And yes, it also doubles as a &ldquo;Home&rdquo; button!</p>
        </div>
      </div>
      <div class="gle__nowctl">
        <button type="button" class="gle__nowbtn" id="gle-prev" aria-label="Previous"><svg width="10" height="10" viewBox="0 0 14 14" fill="none" stroke="currentColor" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M9 2 L4 7 L9 12"/></svg></button>
        <span class="gle__nowdots" id="gle-dots" aria-hidden="true"></span>
        <button type="button" class="gle__nowbtn" id="gle-next" aria-label="Next"><svg width="10" height="10" viewBox="0 0 14 14" fill="none" stroke="currentColor" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M5 2 L10 7 L5 12"/></svg></button>
      </div>
    </div>
  </div>

  <div class="gle__footer">
    <span>gabriel.leblanc-even@univ-rennes.fr</span>
    <span>Rennes, France &middot; &copy; {{ 'now' | date: "%Y" }}</span>
  </div>
</div>

<script>
(function(){
  var box = document.getElementById('gle-slides');
  if (!box) return;
  var slides = box.querySelectorAll('.gle__slide');
  var label = document.getElementById('gle-now-label');
  var prev = document.getElementById('gle-prev'), next = document.getElementById('gle-next'), dots = document.getElementById('gle-dots');
  var n = slides.length, idx = 0, settle;
  if (n < 2) { next.parentNode.style.display = 'none'; return; }
  for (var i = 0; i < n; i++) dots.appendChild(document.createElement('i'));
  function current(){ return Math.round(box.scrollLeft / box.clientWidth); }
  /* Render slide k right away on click or key; swipes are picked up once scrolling settles */
  function render(k){
    idx = k;
    label.textContent = slides[k].getAttribute('data-label');
    box.style.height = slides[k].offsetHeight + 'px';
    for (var j = 0; j < n; j++) dots.children[j].classList.toggle('is-active', j === k);
  }
  function go(k){
    k = (k + n) % n;
    box.scrollTo({ left: k * box.clientWidth, behavior: 'smooth' });
    render(k);
  }
  prev.addEventListener('click', function(){ go(idx - 1); });
  next.addEventListener('click', function(){ go(idx + 1); });
  box.addEventListener('keydown', function(e){ if (e.key === 'ArrowLeft') go(idx - 1); if (e.key === 'ArrowRight') go(idx + 1); });
  box.addEventListener('scroll', function(){ clearTimeout(settle); settle = setTimeout(function(){ render(current()); }, 120); });
  window.addEventListener('resize', function(){ box.scrollLeft = idx * box.clientWidth; render(idx); });
  render(0);
})();
</script>
