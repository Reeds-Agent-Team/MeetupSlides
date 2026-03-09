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
class: text-center
---

<div class="flex flex-col items-center justify-center h-full gap-6">
  <div class="flex items-center gap-6">
    <img src="/bugle-weekly-cover.jpg" class="cover-art" />
    <div class="show-info">
      <div class="show-title">The Bugle Weekly</div>
      <div class="show-hosts">Richard Greaser &amp; Rod Palmer</div>
      <div class="show-desc">The world's most thermodynamically<br>sound Bitcoin podcast</div>
    </div>
  </div>
  <div class="flex gap-12 items-end">
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

<style>
.cover-art {
  width: 180px;
  height: 180px;
  border-radius: 12px;
  object-fit: cover;
  flex-shrink: 0;
}
.show-info {
  text-align: left;
}
.show-title {
  font-size: 2.2rem;
  font-weight: 700;
  color: #f7931a;
  font-family: Arial, sans-serif;
  margin-bottom: 0.3rem;
}
.show-hosts {
  font-size: 1.2rem;
  font-weight: 400;
  color: #cccccc;
  font-family: Arial, sans-serif;
  margin-bottom: 0.6rem;
}
.show-desc {
  font-size: 1rem;
  color: #888888;
  font-family: Arial, sans-serif;
  line-height: 1.4;
}
.qr-block {
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 0.4rem;
}
.qr-code {
  width: 150px;
  height: 150px;
  border: 3px solid white;
  border-radius: 6px;
}
.qr-label {
  font-size: 1rem;
  color: white;
  font-family: Arial, sans-serif;
}
</style>
