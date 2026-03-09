---
theme: default
background: '#000000'
class: text-center
highlighter: shiki
fonts:
  sans: 'Inter'
transition: slide-left
---

<div class="flex flex-col items-center justify-center h-full gap-8">
  <img src="./WMBTCM.png" class="w-2/3 max-w-2xl" />
  <p class="text-2xl font-semibold tracking-widest text-white">Western Mass Bitcoin Meetup #43</p>
  <p class="text-xl font-semibold" style="color: #F7931A;">Mar. 2026</p>
</div>

---
layout: none
---

<style>
.podcast-slide {
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

<div class="podcast-slide">
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
