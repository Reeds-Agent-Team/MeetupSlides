---
theme: default
background: '#000000'
class: text-center
highlighter: shiki
fonts:
  sans: 'Inter'
transition: slide-left
---

<div style="position:absolute;inset:0;background:#000000;display:flex;flex-direction:column;align-items:center;justify-content:center;gap:2rem;">
  <img src="./WMBTCM.png" style="width:60%;max-width:700px;" />
  <p style="font-size:1.5rem;font-weight:600;letter-spacing:0.15em;color:#ffffff;margin:0;">Western Mass Bitcoin Meetup #43</p>
  <p style="font-size:1.25rem;font-weight:600;color:#F7931A;margin:0;">Mar. 2026</p>
</div>

---
layout: none
---

<div style="position:absolute;inset:0;background:#000000;display:flex;gap:2rem;padding:2.5rem 3rem;align-items:stretch;font-family:Inter,sans-serif;">

  <!-- Left: cover + QR codes -->
  <div style="display:flex;flex-direction:column;align-items:center;gap:1.25rem;width:220px;flex-shrink:0;justify-content:center;">
    <img style="width:180px;height:180px;border-radius:14px;" src="https://feeds.fountain.fm/R8scBF2Wiykm0YVldsHQ/files/COVER_ART---DEFAULT---2ac47830-f82a-44aa-b3cb-b5c885519901.jpg" />
    <div style="display:flex;flex-direction:column;align-items:center;gap:4px;">
      <img style="width:110px;height:110px;border-radius:4px;" src="https://api.qrserver.com/v1/create-qr-code/?size=150x150&data=https://fountain.fm/show/lxGTDDEMKkUGn2EN3YRi&bgcolor=ffffff&color=000000" />
      <span style="font-size:0.6rem;color:#F7931A;letter-spacing:0.05em;">Listen on Fountain</span>
    </div>
    <div style="display:flex;flex-direction:column;align-items:center;gap:4px;">
      <img style="width:110px;height:110px;border-radius:4px;" src="https://api.qrserver.com/v1/create-qr-code/?size=150x150&data=https://bugle.news&bgcolor=ffffff&color=000000" />
      <span style="font-size:0.6rem;color:#F7931A;letter-spacing:0.05em;">bugle.news</span>
    </div>
  </div>

  <!-- Right: text -->
  <div style="display:flex;flex-direction:column;flex:1;gap:1rem;justify-content:center;">
    <div>
      <p style="font-size:0.65rem;font-weight:700;letter-spacing:0.18em;text-transform:uppercase;color:#F7931A;margin:0 0 0.3rem;">Podcast Spotlight</p>
      <h1 style="font-size:2.6rem;font-weight:700;color:#ffffff;line-height:1.15;margin:0;">The Bugle Weekly</h1>
      <p style="font-size:1rem;color:#F7931A;margin:0.3rem 0 0;">Richard Greaser &amp; Rod Palmer</p>
    </div>
    <blockquote style="border-left:3px solid #F7931A;padding-left:1rem;font-style:italic;color:#ffffff;font-size:0.9rem;line-height:1.5;margin:0;">
      "It's like the 753rd funniest account on Twitter" — @udiwertheimer
    </blockquote>
    <ul style="list-style:none;padding:0;margin:0;display:flex;flex-direction:column;gap:0.75rem;">
      <li style="font-size:0.85rem;color:#ffffff;line-height:1.5;padding-left:1.2rem;position:relative;">
        <span style="position:absolute;left:0;color:#F7931A;">▸</span>
        Launched in Jan. 2023 by Richard Greaser — in a parallel dimension where the Bugle rivals the NYT and WSJ. A glitch in the matrix lets you glimpse it.
      </li>
      <li style="font-size:0.85rem;color:#ffffff;line-height:1.5;padding-left:1.2rem;position:relative;">
        <span style="position:absolute;left:0;color:#F7931A;">▸</span>
        In your dimension the stories appear absurd. In theirs, they're front-page news.
      </li>
      <li style="font-size:0.85rem;color:#ffffff;line-height:1.5;padding-left:1.2rem;position:relative;">
        <span style="position:absolute;left:0;color:#F7931A;">▸</span>
        Zero corporate sponsorships — by design. When you take sponsor money, the audience becomes the product. The Bugle refuses that deal.
      </li>
      <li style="font-size:0.85rem;color:#ffffff;line-height:1.5;padding-left:1.2rem;position:relative;">
        <span style="position:absolute;left:0;color:#F7931A;">▸</span>
        The world's most thermodynamically sound Bitcoin podcast — credentialed journalists, 40HPW of listening, chain smoking included.
      </li>
    </ul>
  </div>

</div>

---
layout: none
---

<div style="position:absolute;inset:0;background:#0a0a0a;overflow:hidden;font-family:'Space Mono',monospace;color:#f7931a;">

  <!-- grid background -->
  <div style="position:absolute;inset:0;background-image:linear-gradient(rgba(247,147,26,0.04) 1px,transparent 1px),linear-gradient(90deg,rgba(247,147,26,0.04) 1px,transparent 1px);background-size:60px 60px;"></div>
  <!-- center glow -->
  <div style="position:absolute;inset:0;background:radial-gradient(ellipse at 50% 50%,rgba(247,147,26,0.06) 0%,transparent 70%);"></div>

  <div style="position:relative;z-index:1;width:100%;height:100%;display:flex;flex-direction:column;padding:36px 60px 52px;gap:0;">

    <!-- Title -->
    <div style="text-align:center;margin-bottom:24px;">
      <div style="font-size:12px;letter-spacing:0.35em;color:rgba(247,147,26,0.55);text-transform:uppercase;margin-bottom:8px;">The mathematics of scarcity</div>
      <div style="font-family:'Oswald',sans-serif;font-size:44px;font-weight:700;line-height:1;letter-spacing:0.02em;color:#f7931a;text-transform:uppercase;">
        There Will Never Be <span style="color:#fff;">21 Million</span> Bitcoin
      </div>
    </div>

    <!-- Main row -->
    <div style="display:flex;flex:1;gap:40px;align-items:stretch;min-height:0;">

      <!-- Halving chain -->
      <div style="display:flex;flex-direction:column;flex-shrink:0;justify-content:center;gap:0;">
        <div style="display:flex;align-items:center;gap:12px;"><div style="width:10px;height:10px;border-radius:50%;background:#f7931a;box-shadow:0 0 6px #f7931a88;flex-shrink:0;"></div><span style="font-size:12px;color:#f7931a;white-space:nowrap;">Era 1 · 50 BTC/block · blocks 0–209,999</span></div>
        <div style="width:2px;height:14px;background:linear-gradient(to bottom,rgba(247,147,26,0.5),rgba(247,147,26,0.15));margin-left:4px;"></div>
        <div style="display:flex;align-items:center;gap:12px;"><div style="width:10px;height:10px;border-radius:50%;background:#f7931a;box-shadow:0 0 6px #f7931a88;flex-shrink:0;"></div><span style="font-size:12px;color:#f7931a;white-space:nowrap;">Era 2 · 25 BTC/block</span></div>
        <div style="width:2px;height:14px;background:linear-gradient(to bottom,rgba(247,147,26,0.5),rgba(247,147,26,0.15));margin-left:4px;"></div>
        <div style="display:flex;align-items:center;gap:12px;"><div style="width:10px;height:10px;border-radius:50%;background:#f7931a;box-shadow:0 0 6px #f7931a88;flex-shrink:0;"></div><span style="font-size:12px;color:#f7931a;white-space:nowrap;">Era 3 · 12.5 BTC/block</span></div>
        <div style="width:2px;height:14px;background:linear-gradient(to bottom,rgba(247,147,26,0.5),rgba(247,147,26,0.15));margin-left:4px;"></div>
        <div style="display:flex;align-items:center;gap:12px;"><div style="width:10px;height:10px;border-radius:50%;background:#f7931a;box-shadow:0 0 6px #f7931a88;flex-shrink:0;"></div><span style="font-size:12px;color:#f7931a;white-space:nowrap;">Era 4 · 6.25 BTC/block</span></div>
        <div style="width:2px;height:14px;background:linear-gradient(to bottom,rgba(247,147,26,0.5),rgba(247,147,26,0.15));margin-left:4px;"></div>
        <div style="display:flex;align-items:center;gap:12px;"><div style="width:10px;height:10px;border-radius:50%;background:rgba(247,147,26,0.25);flex-shrink:0;"></div><span style="font-size:12px;color:rgba(247,147,26,0.4);white-space:nowrap;">Era 5 · 3.125 BTC/block</span></div>
        <div style="width:2px;height:14px;background:linear-gradient(to bottom,rgba(247,147,26,0.3),rgba(247,147,26,0.1));margin-left:4px;"></div>
        <div style="display:flex;align-items:center;gap:12px;"><div style="width:10px;height:10px;border-radius:50%;background:rgba(247,147,26,0.25);flex-shrink:0;"></div><span style="font-size:12px;color:rgba(247,147,26,0.4);white-space:nowrap;">··· halvings continue ···</span></div>
        <div style="width:2px;height:14px;background:linear-gradient(to bottom,rgba(247,147,26,0.3),rgba(247,147,26,0.1));margin-left:4px;"></div>
        <div style="display:flex;align-items:center;gap:12px;"><div style="width:10px;height:10px;border-radius:50%;background:rgba(247,147,26,0.25);flex-shrink:0;"></div><span style="font-size:12px;color:rgba(247,147,26,0.4);white-space:nowrap;">Era 33 · 0.00000002 BTC (2 sats)</span></div>
        <div style="width:2px;height:14px;background:linear-gradient(to bottom,rgba(247,147,26,0.3),rgba(247,147,26,0.1));margin-left:4px;"></div>
        <div style="display:flex;align-items:center;gap:12px;"><div style="width:10px;height:10px;border-radius:50%;background:rgba(247,147,26,0.25);flex-shrink:0;"></div><span style="font-size:12px;color:rgba(247,147,26,0.4);white-space:nowrap;">Era 34 · 0.00000001 BTC (1 sat)</span></div>
        <div style="width:2px;height:14px;background:linear-gradient(to bottom,rgba(247,147,26,0.2),rgba(247,147,26,0.05));margin-left:4px;"></div>
        <div style="display:flex;align-items:center;gap:12px;"><div style="width:10px;height:10px;border-radius:50%;background:#333;flex-shrink:0;"></div><span style="font-size:12px;color:#444;white-space:nowrap;">Era 34+ · 0.00000000 BTC · block 6,930,000+</span></div>
      </div>

      <!-- Chart - takes up remaining space -->
      <div style="flex:1;display:flex;flex-direction:column;align-items:center;min-width:0;">
        <div style="font-size:11px;letter-spacing:0.2em;color:rgba(247,147,26,0.5);text-transform:uppercase;margin-bottom:10px;">BTC Added Per Era (log scale)</div>
        <svg style="width:100%;flex:1;" viewBox="0 0 820 380" preserveAspectRatio="xMidYMid meet" xmlns="http://www.w3.org/2000/svg">
          <defs>
            <linearGradient id="bG" x1="0" y1="0" x2="0" y2="1">
              <stop offset="0%" stop-color="#f7931a" stop-opacity="0.95"/>
              <stop offset="100%" stop-color="#f7931a" stop-opacity="0.25"/>
            </linearGradient>
            <linearGradient id="bGd" x1="0" y1="0" x2="0" y2="1">
              <stop offset="0%" stop-color="#f7931a" stop-opacity="0.3"/>
              <stop offset="100%" stop-color="#f7931a" stop-opacity="0.06"/>
            </linearGradient>
          </defs>
          <!-- bars -->
          <rect x="60"  y="50"  width="70" height="290" fill="url(#bG)" rx="2"/>
          <text x="95"  y="40"  fill="#f7931a" font-family="Space Mono,monospace" font-size="14" text-anchor="middle">10.5M</text>
          <text x="95"  y="370" fill="rgba(247,147,26,0.5)" font-family="Space Mono,monospace" font-size="13" text-anchor="middle">Era 1</text>

          <rect x="160" y="80"  width="70" height="260" fill="url(#bG)" rx="2"/>
          <text x="195" y="70"  fill="#f7931a" font-family="Space Mono,monospace" font-size="14" text-anchor="middle">5.25M</text>
          <text x="195" y="370" fill="rgba(247,147,26,0.5)" font-family="Space Mono,monospace" font-size="13" text-anchor="middle">Era 2</text>

          <rect x="260" y="115" width="70" height="225" fill="url(#bG)" rx="2"/>
          <text x="295" y="105" fill="#f7931a" font-family="Space Mono,monospace" font-size="14" text-anchor="middle">2.63M</text>
          <text x="295" y="370" fill="rgba(247,147,26,0.5)" font-family="Space Mono,monospace" font-size="13" text-anchor="middle">Era 3</text>

          <rect x="360" y="150" width="70" height="190" fill="url(#bG)" rx="2"/>
          <text x="395" y="140" fill="#f7931a" font-family="Space Mono,monospace" font-size="14" text-anchor="middle">1.31M</text>
          <text x="395" y="370" fill="rgba(247,147,26,0.5)" font-family="Space Mono,monospace" font-size="13" text-anchor="middle">Era 4</text>

          <rect x="460" y="190" width="70" height="150" fill="url(#bGd)" rx="2"/>
          <text x="495" y="180" fill="rgba(247,147,26,0.45)" font-family="Space Mono,monospace" font-size="14" text-anchor="middle">656K</text>
          <text x="495" y="370" fill="rgba(247,147,26,0.3)" font-family="Space Mono,monospace" font-size="13" text-anchor="middle">Era 5</text>

          <rect x="560" y="225" width="70" height="115" fill="url(#bGd)" rx="2"/>
          <text x="595" y="215" fill="rgba(247,147,26,0.35)" font-family="Space Mono,monospace" font-size="14" text-anchor="middle">328K</text>
          <text x="595" y="370" fill="rgba(247,147,26,0.3)" font-family="Space Mono,monospace" font-size="13" text-anchor="middle">Era 6</text>

          <rect x="660" y="265" width="70" height="75" fill="url(#bGd)" rx="2"/>
          <text x="695" y="255" fill="rgba(247,147,26,0.25)" font-family="Space Mono,monospace" font-size="14" text-anchor="middle">164K</text>
          <text x="695" y="370" fill="rgba(247,147,26,0.2)" font-family="Space Mono,monospace" font-size="13" text-anchor="middle">Era 7</text>

          <!-- baseline -->
          <line x1="40" y1="340" x2="780" y2="340" stroke="rgba(247,147,26,0.15)" stroke-width="1"/>

          <!-- decay curve -->
          <path d="M 95 42 Q 430 10 730 258" stroke="rgba(247,147,26,0.3)" stroke-width="2" fill="none" stroke-dasharray="6,4"/>
          <text x="440" y="22" fill="rgba(247,147,26,0.4)" font-family="Space Mono,monospace" font-size="13" text-anchor="middle">Each era mints exactly half the previous</text>
        </svg>
      </div>

      <!-- Truth panel -->
      <div style="flex-shrink:0;width:300px;display:flex;flex-direction:column;gap:16px;justify-content:center;">
        <div style="border:1px solid rgba(247,147,26,0.2);background:rgba(247,147,26,0.04);padding:18px 22px;border-radius:4px;">
          <div style="font-size:11px;letter-spacing:0.3em;text-transform:uppercase;color:rgba(247,147,26,0.4);margin-bottom:8px;">The common belief</div>
          <div style="font-family:'Oswald',sans-serif;font-size:34px;font-weight:700;color:rgba(247,147,26,0.3);text-decoration:line-through;text-decoration-color:rgba(247,147,26,0.5);">21,000,000</div>
          <div style="font-size:11px;color:rgba(247,147,26,0.5);margin-top:6px;line-height:1.5;">BTC — a hard cap that is<br>often cited but never reached</div>
        </div>
        <div style="border:1px solid #f7931a;background:rgba(247,147,26,0.1);padding:18px 22px;border-radius:4px;box-shadow:0 0 24px rgba(247,147,26,0.15),inset 0 0 16px rgba(247,147,26,0.05);">
          <div style="font-size:11px;letter-spacing:0.3em;text-transform:uppercase;color:#f7931a;margin-bottom:8px;">↳ The actual maximum</div>
          <div style="font-family:'Oswald',sans-serif;font-size:30px;font-weight:700;color:#fff;">20,999,999.976<span style="font-size:20px;opacity:0.7;">9</span></div>
          <div style="font-size:11px;color:rgba(255,255,255,0.55);margin-top:6px;line-height:1.5;">BTC ever mineable — because<br>integer halving truncates remainders</div>
        </div>
        <div style="text-align:center;padding:14px;border-top:1px solid rgba(247,147,26,0.2);">
          <div style="font-size:11px;letter-spacing:0.2em;color:rgba(247,147,26,0.5);text-transform:uppercase;margin-bottom:6px;">Forever missing</div>
          <div style="font-family:'Oswald',sans-serif;font-size:22px;color:rgba(247,147,26,0.7);">≈ 0.023 BTC · ~2,300 sats</div>
        </div>
      </div>

    </div>

    <!-- Footer -->
    <div style="position:absolute;bottom:16px;left:60px;right:60px;display:flex;justify-content:space-between;align-items:center;border-top:1px solid rgba(247,147,26,0.12);padding-top:10px;">
      <span style="font-size:10px;color:rgba(247,147,26,0.35);letter-spacing:0.06em;">Block rewards halve every 210,000 blocks · ~4 years · Final subsidy reaches 0 at block 6,930,000</span>
      <span style="font-family:'Oswald',sans-serif;font-size:16px;color:rgba(247,147,26,0.25);letter-spacing:0.1em;">₿ NOT 21M</span>
    </div>

  </div>
</div>
