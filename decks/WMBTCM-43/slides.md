---
theme: default
background: '#000000'
class: text-center
highlighter: shiki
lineNumbers: false
drawings:
  persist: false
---

<div class="flex flex-col items-center justify-center h-full">
  <img src="/WMBTCM.png" class="meetup-logo" />
  <div class="meetup-number">#43</div>
  <div class="meetup-date">Mar. 2026</div>
</div>

<style>
.meetup-logo {
  max-width: 600px;
  width: 80%;
  margin-bottom: 2rem;
}
.meetup-number {
  font-size: 2.5rem;
  font-weight: 700;
  color: white;
  font-family: Arial, sans-serif;
  margin-bottom: 0.3rem;
}
.meetup-date {
  font-size: 2rem;
  font-weight: 400;
  color: white;
  font-family: Arial, sans-serif;
}
</style>

---
background: '#000000'
---

<div class="slide2">

  <!-- LEFT: cover art + QRs stacked -->
  <div class="left-col">
    <img src="/bugle-weekly-cover.jpg" class="cover-art" />
    <div class="qr-row">
      <div class="qr-block">
        <img src="/qr-fountain.png" class="qr-code" />
        <div class="qr-label">Fountain</div>
      </div>
      <div class="qr-block">
        <img src="/qr-website.png" class="qr-code" />
        <div class="qr-label">bugle.news</div>
      </div>
    </div>
  </div>

  <!-- RIGHT: title, hosts, bullets, quote -->
  <div class="right-col">
    <div class="show-title">The Bugle Weekly</div>
    <div class="show-hosts">Richard Greaser &amp; Rod Palmer</div>

    <ul class="bullets">
      <li>Launched in January 2023 — a satirical news outlet that, in a parallel dimension, is the world's premiere news agency rivaling the NYT and WSJ</li>
      <li>Stories are real where they come from; here they just appear absurd — a glitch in the matrix lets you catch glimpses</li>
      <li>No corporate sponsorships — the audience is the customer, not the product</li>
      <li>Paired with a Bitcoin podcast covering the thermodynamics of sound money</li>
    </ul>

    <div class="quote">
      "It's like the 753rd funniest account on Twitter"
      <span class="quote-attr">— @udiwertheimer</span>
    </div>
  </div>

</div>

<style>
.slide2 {
  display: flex;
  flex-direction: row;
  align-items: stretch;
  height: 100%;
  width: 100%;
  padding: 2rem 2.5rem;
  box-sizing: border-box;
  gap: 2.5rem;
}
.left-col {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: space-between;
  flex-shrink: 0;
  gap: 1.2rem;
}
.cover-art {
  width: 200px;
  height: 200px;
  border-radius: 14px;
  object-fit: cover;
}
.qr-row {
  display: flex;
  flex-direction: row;
  gap: 1rem;
  justify-content: center;
}
.qr-block {
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 0.3rem;
}
.qr-code {
  width: 110px;
  height: 110px;
  border: 2px solid white;
  border-radius: 6px;
}
.qr-label {
  font-size: 0.85rem;
  color: white;
  font-family: Arial, sans-serif;
}
.right-col {
  display: flex;
  flex-direction: column;
  justify-content: center;
  text-align: left;
  flex: 1;
  gap: 0.8rem;
}
.show-title {
  font-size: 2.4rem;
  font-weight: 700;
  color: #f7931a;
  font-family: Arial, sans-serif;
  line-height: 1.1;
}
.show-hosts {
  font-size: 1.1rem;
  color: #aaaaaa;
  font-family: Arial, sans-serif;
}
.bullets {
  list-style: none;
  padding: 0;
  margin: 0.4rem 0;
  display: flex;
  flex-direction: column;
  gap: 0.55rem;
}
.bullets li {
  font-size: 0.95rem;
  color: #dddddd;
  font-family: Arial, sans-serif;
  line-height: 1.4;
  padding-left: 1.2rem;
  position: relative;
}
.bullets li::before {
  content: "▸";
  color: #f7931a;
  position: absolute;
  left: 0;
}
.quote {
  font-size: 1rem;
  color: #aaaaaa;
  font-family: Georgia, serif;
  font-style: italic;
  border-left: 3px solid #f7931a;
  padding-left: 0.8rem;
  margin-top: 0.4rem;
  line-height: 1.5;
}
.quote-attr {
  display: block;
  font-size: 0.85rem;
  color: #777777;
  font-style: normal;
  margin-top: 0.2rem;
}
</style>
