---
theme: default
background: '#000000'
class: text-center
highlighter: shiki
fonts:
  sans: 'Inter'
transition: slide-left
---

<div class="flex flex-col items-center justify-center h-full gap-8" style="background:#000000; position:absolute; inset:0;">
  <img src="./WMBTCM.png" class="w-2/3 max-w-2xl" />
  <p class="text-2xl font-semibold tracking-widest text-white">Western Mass Bitcoin Meetup #43</p>
  <p class="text-xl font-semibold" style="color: #F7931A;">Mar. 2026</p>
</div>

---
layout: none
class: 'p-0'
---

<style>
.slide2-wrap {
  position: absolute;
  inset: 0;
  background: #000000;
  display: flex;
  height: 100%;
  gap: 1.5rem;
  padding: 2rem 2.5rem;
  align-items: flex-start;
  font-family: Inter, sans-serif;
}
.podcast-left {
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 1rem;
  width: 200px;
  flex-shrink: 0;
}
.podcast-left img.cover {
  width: 160px;
  height: 160px;
  border-radius: 12px;
}
.podcast-left img.qr {
  width: 90px;
  height: 90px;
  border-radius: 4px;
}
.qr-label {
  font-size: 0.65rem;
  color: #F7931A;
  margin-top: 2px;
  text-align: center;
}
.podcast-right {
  display: flex;
  flex-direction: column;
  flex: 1;
  gap: 0.75rem;
  padding-top: 0.25rem;
}
.spotlight-label {
  font-size: 0.7rem;
  font-weight: 700;
  letter-spacing: 0.12em;
  text-transform: uppercase;
  color: #F7931A;
  margin-bottom: 0.1rem;
}
.podcast-title {
  font-size: 2rem;
  font-weight: 700;
  color: #ffffff;
  line-height: 1.2;
  margin: 0;
}
.podcast-hosts {
  font-size: 0.95rem;
  color: #F7931A;
  margin: 0;
}
.podcast-quote {
  border-left: 3px solid #F7931A;
  padding-left: 0.75rem;
  font-style: italic;
  color: #ffffff;
  font-size: 0.8rem;
  line-height: 1.4;
  margin: 0;
}
.podcast-bullets {
  list-style: none;
  padding: 0;
  margin: 0;
  display: flex;
  flex-direction: column;
  gap: 0.5rem;
}
.podcast-bullets li {
  font-size: 0.78rem;
  color: #ffffff;
  line-height: 1.4;
}
.podcast-bullets li::before {
  content: "▸ ";
  color: #F7931A;
}
</style>

<div class="slide2-wrap">
  <div class="podcast-left">
    <img class="cover" src="https://feeds.fountain.fm/R8scBF2Wiykm0YVldsHQ/files/COVER_ART---DEFAULT---2ac47830-f82a-44aa-b3cb-b5c885519901.jpg" />
    <div style="display:flex;flex-direction:column;align-items:center;">
      <img class="qr" src="https://api.qrserver.com/v1/create-qr-code/?size=120x120&data=https://fountain.fm/show/lxGTDDEMKkUGn2EN3YRi&bgcolor=ffffff&color=000000" />
      <p class="qr-label">Listen on Fountain</p>
    </div>
    <div style="display:flex;flex-direction:column;align-items:center;">
      <img class="qr" src="https://api.qrserver.com/v1/create-qr-code/?size=120x120&data=https://bugle.news&bgcolor=ffffff&color=000000" />
      <p class="qr-label">bugle.news</p>
    </div>
  </div>
  <div class="podcast-right">
    <div>
      <p class="spotlight-label">Podcast Spotlight</p>
      <h1 class="podcast-title">The Bugle Weekly</h1>
      <p class="podcast-hosts">Richard Greaser & Rod Palmer</p>
    </div>
    <blockquote class="podcast-quote">
      "It's like the 753rd funniest account on Twitter" — @udiwertheimer
    </blockquote>
    <ul class="podcast-bullets">
      <li>Launched in Jan. 2023 by Richard Greaser — in a parallel dimension where the Bugle rivals the NYT and WSJ. A glitch in the matrix lets you glimpse it.</li>
      <li>In your dimension the stories appear absurd. In theirs, they're front-page news.</li>
      <li>Zero corporate sponsorships — by design. When you take sponsor money, the audience becomes the product. The Bugle refuses that deal.</li>
      <li>The world's most thermodynamically sound Bitcoin podcast — credentialed journalists, 40HPW of listening, chain smoking included.</li>
    </ul>
  </div>
</div>

---
layout: none
class: 'p-0'
---

<style>
@import url('https://fonts.googleapis.com/css2?family=Space+Mono:wght@400;700&family=Oswald:wght@700&display=swap');

.s3 {
  position: absolute;
  inset: 0;
  background: #0a0a0a;
  color: #f7931a;
  font-family: 'Space Mono', monospace;
  overflow: hidden;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}
.s3::before {
  content: '';
  position: absolute;
  inset: 0;
  background-image:
    linear-gradient(rgba(247,147,26,0.04) 1px, transparent 1px),
    linear-gradient(90deg, rgba(247,147,26,0.04) 1px, transparent 1px);
  background-size: 60px 60px;
  pointer-events: none;
}
.s3::after {
  content: '';
  position: absolute;
  inset: 0;
  background: radial-gradient(ellipse at 50% 50%, rgba(247,147,26,0.06) 0%, transparent 70%);
  pointer-events: none;
}
.s3-inner {
  position: relative;
  width: 100%;
  height: 100%;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  padding: 28px 50px 48px;
  z-index: 1;
  gap: 0;
}
.s3 .title-block {
  text-align: center;
  margin-bottom: 20px;
}
.s3 .eyebrow {
  font-size: 11px;
  letter-spacing: 0.35em;
  color: rgba(247,147,26,0.55);
  text-transform: uppercase;
  margin-bottom: 6px;
}
.s3 .headline {
  font-family: 'Oswald', sans-serif;
  font-size: 38px;
  font-weight: 700;
  line-height: 1.1;
  letter-spacing: 0.02em;
  color: #f7931a;
  text-transform: uppercase;
}
.s3 .headline span { color: #fff; }
.s3 .main-row {
  display: flex;
  align-items: flex-start;
  gap: 36px;
  width: 100%;
  flex: 1;
  min-height: 0;
}
.s3 .halving-chain {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  flex-shrink: 0;
}
.s3 .era-row {
  display: flex;
  align-items: center;
  gap: 10px;
}
.s3 .era-dot {
  width: 9px;
  height: 9px;
  border-radius: 50%;
  background: #f7931a;
  flex-shrink: 0;
  box-shadow: 0 0 6px #f7931a88;
}
.s3 .era-dot.dim { background: rgba(247,147,26,0.25); box-shadow: none; }
.s3 .era-dot.dead { background: #333; box-shadow: none; }
.s3 .era-label {
  font-size: 11px;
  color: #f7931a;
  white-space: nowrap;
  line-height: 1;
}
.s3 .era-label.dim { color: rgba(247,147,26,0.4); }
.s3 .era-label.dead { color: #444; }
.s3 .era-connector {
  width: 2px;
  height: 12px;
  background: linear-gradient(to bottom, rgba(247,147,26,0.5), rgba(247,147,26,0.15));
  margin-left: 3px;
}
.s3 .chart-area {
  flex: 1;
  display: flex;
  flex-direction: column;
  align-items: center;
  min-width: 0;
}
.s3 .chart-label {
  font-size: 10px;
  letter-spacing: 0.2em;
  color: rgba(247,147,26,0.5);
  text-transform: uppercase;
  margin-bottom: 8px;
}
.s3 svg.bar-chart {
  width: 100%;
  height: 220px;
}
.s3 .truth-panel {
  flex-shrink: 0;
  width: 280px;
  display: flex;
  flex-direction: column;
  gap: 12px;
}
.s3 .myth-box, .s3 .truth-box {
  border: 1px solid;
  padding: 12px 16px;
  border-radius: 4px;
}
.s3 .myth-box {
  border-color: rgba(247,147,26,0.2);
  background: rgba(247,147,26,0.04);
}
.s3 .truth-box {
  border-color: #f7931a;
  background: rgba(247,147,26,0.1);
  box-shadow: 0 0 20px rgba(247,147,26,0.15), inset 0 0 15px rgba(247,147,26,0.05);
}
.s3 .box-tag {
  font-size: 10px;
  letter-spacing: 0.3em;
  text-transform: uppercase;
  margin-bottom: 6px;
}
.s3 .myth-box .box-tag { color: rgba(247,147,26,0.4); }
.s3 .truth-box .box-tag { color: #f7931a; }
.s3 .box-value {
  font-family: 'Oswald', sans-serif;
  font-size: 26px;
  font-weight: 700;
  line-height: 1.1;
}
.s3 .myth-box .box-value { color: rgba(247,147,26,0.3); text-decoration: line-through; text-decoration-color: rgba(247,147,26,0.5); }
.s3 .truth-box .box-value { color: #fff; }
.s3 .box-sub {
  font-size: 10px;
  color: rgba(247,147,26,0.5);
  margin-top: 4px;
  line-height: 1.5;
}
.s3 .truth-box .box-sub { color: rgba(255,255,255,0.55); }
.s3 .missing-btc {
  text-align: center;
  padding: 10px;
  border-top: 1px solid rgba(247,147,26,0.2);
}
.s3 .missing-label {
  font-size: 10px;
  letter-spacing: 0.2em;
  color: rgba(247,147,26,0.5);
  text-transform: uppercase;
  margin-bottom: 4px;
}
.s3 .missing-value {
  font-family: 'Oswald', sans-serif;
  font-size: 18px;
  color: rgba(247,147,26,0.7);
}
.s3 .footer {
  position: absolute;
  bottom: 14px;
  left: 50px;
  right: 50px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  border-top: 1px solid rgba(247,147,26,0.12);
  padding-top: 8px;
}
.s3 .footer-note {
  font-size: 10px;
  color: rgba(247,147,26,0.35);
  letter-spacing: 0.06em;
}
.s3 .btc-symbol {
  font-family: 'Oswald', sans-serif;
  font-size: 16px;
  color: rgba(247,147,26,0.25);
  letter-spacing: 0.1em;
}
</style>

<div class="s3">
  <div class="s3-inner">
    <div class="title-block">
      <div class="eyebrow">The mathematics of scarcity</div>
      <div class="headline">There Will Never Be <span>21 Million</span> Bitcoin</div>
    </div>
    <div class="main-row">
      <div class="halving-chain">
        <div class="era-row"><div class="era-dot"></div><div class="era-label">Era 1 · 50 BTC/block · blocks 0–209,999</div></div>
        <div class="era-connector"></div>
        <div class="era-row"><div class="era-dot"></div><div class="era-label">Era 2 · 25 BTC/block</div></div>
        <div class="era-connector"></div>
        <div class="era-row"><div class="era-dot"></div><div class="era-label">Era 3 · 12.5 BTC/block</div></div>
        <div class="era-connector"></div>
        <div class="era-row"><div class="era-dot"></div><div class="era-label">Era 4 · 6.25 BTC/block</div></div>
        <div class="era-connector"></div>
        <div class="era-row"><div class="era-dot dim"></div><div class="era-label dim">Era 5 · 3.125 BTC/block</div></div>
        <div class="era-connector"></div>
        <div class="era-row"><div class="era-dot dim"></div><div class="era-label dim">··· halvings continue ···</div></div>
        <div class="era-connector"></div>
        <div class="era-row"><div class="era-dot dim"></div><div class="era-label dim">Era 33 · 0.00000002 BTC (2 sats)</div></div>
        <div class="era-connector"></div>
        <div class="era-row"><div class="era-dot dim"></div><div class="era-label dim">Era 34 · 0.00000001 BTC (1 sat)</div></div>
        <div class="era-connector"></div>
        <div class="era-row"><div class="era-dot dead"></div><div class="era-label dead">Era 34+ · 0.00000000 BTC · block 6,930,000+</div></div>
      </div>
      <div class="chart-area">
        <div class="chart-label">BTC Added Per Era (log scale)</div>
        <svg class="bar-chart" viewBox="0 0 820 320" xmlns="http://www.w3.org/2000/svg">
          <defs>
            <linearGradient id="barGrad" x1="0" y1="0" x2="0" y2="1">
              <stop offset="0%" stop-color="#f7931a" stop-opacity="0.95"/>
              <stop offset="100%" stop-color="#f7931a" stop-opacity="0.25"/>
            </linearGradient>
            <linearGradient id="barGradDim" x1="0" y1="0" x2="0" y2="1">
              <stop offset="0%" stop-color="#f7931a" stop-opacity="0.3"/>
              <stop offset="100%" stop-color="#f7931a" stop-opacity="0.06"/>
            </linearGradient>
          </defs>
          <rect x="60"  y="40"  width="60" height="260" fill="url(#barGrad)" rx="2"/>
          <text x="90"  y="32"  fill="#f7931a" font-family="Space Mono" font-size="12" text-anchor="middle">10.5M</text>
          <text x="90"  y="315" fill="rgba(247,147,26,0.5)" font-family="Space Mono" font-size="11" text-anchor="middle">Era 1</text>
          <rect x="150" y="60"  width="60" height="240" fill="url(#barGrad)" rx="2"/>
          <text x="180" y="52"  fill="#f7931a" font-family="Space Mono" font-size="12" text-anchor="middle">5.25M</text>
          <text x="180" y="315" fill="rgba(247,147,26,0.5)" font-family="Space Mono" font-size="11" text-anchor="middle">Era 2</text>
          <rect x="240" y="90"  width="60" height="210" fill="url(#barGrad)" rx="2"/>
          <text x="270" y="82"  fill="#f7931a" font-family="Space Mono" font-size="12" text-anchor="middle">2.63M</text>
          <text x="270" y="315" fill="rgba(247,147,26,0.5)" font-family="Space Mono" font-size="11" text-anchor="middle">Era 3</text>
          <rect x="330" y="120" width="60" height="180" fill="url(#barGrad)" rx="2"/>
          <text x="360" y="112" fill="#f7931a" font-family="Space Mono" font-size="12" text-anchor="middle">1.31M</text>
          <text x="360" y="315" fill="rgba(247,147,26,0.5)" font-family="Space Mono" font-size="11" text-anchor="middle">Era 4</text>
          <rect x="420" y="150" width="60" height="150" fill="url(#barGradDim)" rx="2"/>
          <text x="450" y="142" fill="rgba(247,147,26,0.45)" font-family="Space Mono" font-size="12" text-anchor="middle">656K</text>
          <text x="450" y="315" fill="rgba(247,147,26,0.3)" font-family="Space Mono" font-size="11" text-anchor="middle">Era 5</text>
          <rect x="510" y="180" width="60" height="120" fill="url(#barGradDim)" rx="2"/>
          <text x="540" y="172" fill="rgba(247,147,26,0.35)" font-family="Space Mono" font-size="12" text-anchor="middle">328K</text>
          <text x="540" y="315" fill="rgba(247,147,26,0.3)" font-family="Space Mono" font-size="11" text-anchor="middle">Era 6</text>
          <rect x="600" y="210" width="60" height="90" fill="url(#barGradDim)" rx="2"/>
          <text x="630" y="202" fill="rgba(247,147,26,0.25)" font-family="Space Mono" font-size="12" text-anchor="middle">164K</text>
          <text x="630" y="315" fill="rgba(247,147,26,0.2)" font-family="Space Mono" font-size="11" text-anchor="middle">Era 7</text>
          <rect x="690" y="245" width="60" height="55" fill="url(#barGradDim)" rx="2"/>
          <text x="720" y="237" fill="rgba(247,147,26,0.2)" font-family="Space Mono" font-size="12" text-anchor="middle">···</text>
          <text x="720" y="315" fill="rgba(247,147,26,0.15)" font-family="Space Mono" font-size="11" text-anchor="middle">···</text>
          <line x1="40" y1="300" x2="780" y2="300" stroke="rgba(247,147,26,0.15)" stroke-width="1"/>
          <path d="M 80 30 Q 400 0 750 252" stroke="rgba(247,147,26,0.3)" stroke-width="2" fill="none" stroke-dasharray="6,4"/>
          <text x="430" y="18" fill="rgba(247,147,26,0.4)" font-family="Space Mono" font-size="13" text-anchor="middle">Each era mints exactly half the previous</text>
        </svg>
      </div>
      <div class="truth-panel">
        <div class="myth-box">
          <div class="box-tag">The common belief</div>
          <div class="box-value">21,000,000</div>
          <div class="box-sub">BTC — a hard cap that is<br>often cited but never reached</div>
        </div>
        <div class="truth-box">
          <div class="box-tag">↳ The actual maximum</div>
          <div class="box-value">20,999,999.976<span style="font-size:18px;opacity:0.7">9</span></div>
          <div class="box-sub">BTC ever mineable — because<br>integer halving truncates remainders</div>
        </div>
        <div class="missing-btc">
          <div class="missing-label">Forever missing</div>
          <div class="missing-value">≈ 0.023 BTC · ~2,300 sats</div>
        </div>
      </div>
    </div>
    <div class="footer">
      <div class="footer-note">Block rewards halve every 210,000 blocks · ~4 years · Final subsidy reaches 0 at block 6,930,000</div>
      <div class="btc-symbol">₿ NOT 21M</div>
    </div>
  </div>
</div>
