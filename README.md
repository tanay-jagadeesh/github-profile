<div align="center">

<svg width="800" height="220" viewBox="0 0 800 220" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="bg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%"   stop-color="hsl(252,55%,18%)"/>
      <stop offset="40%"  stop-color="hsl(240,45%,14%)"/>
      <stop offset="70%"  stop-color="hsl(260,50%,16%)"/>
      <stop offset="100%" stop-color="hsl(348,40%,20%)"/>
    </linearGradient>
    <radialGradient id="orb1" cx="20%" cy="60%" r="30%">
      <stop offset="0%" stop-color="rgba(100,80,220,0.18)"/>
      <stop offset="100%" stop-color="transparent"/>
    </radialGradient>
    <radialGradient id="orb2" cx="80%" cy="30%" r="25%">
      <stop offset="0%" stop-color="rgba(220,100,140,0.14)"/>
      <stop offset="100%" stop-color="transparent"/>
    </radialGradient>
    <radialGradient id="orb3" cx="50%" cy="85%" r="20%">
      <stop offset="0%" stop-color="rgba(80,140,255,0.12)"/>
      <stop offset="100%" stop-color="transparent"/>
    </radialGradient>
    <radialGradient id="textglow" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="rgba(160,140,255,0.18)"/>
      <stop offset="100%" stop-color="transparent"/>
    </radialGradient>
    <filter id="blur3" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="3"/>
    </filter>
  </defs>

  <!-- Background -->
  <rect width="800" height="220" fill="url(#bg)" rx="14"/>

  <!-- Ambient orbs -->
  <ellipse cx="160" cy="132" rx="150" ry="110" fill="url(#orb1)"/>
  <ellipse cx="640" cy="66"  rx="130" ry="100" fill="url(#orb2)"/>
  <ellipse cx="400" cy="187" rx="110" ry="80"  fill="url(#orb3)"/>

  <!-- Grid lines -->
  <g stroke="rgba(140,130,255,0.05)" stroke-width="0.5">
    <line x1="0"   y1="0" x2="0"   y2="220"/><line x1="40"  y1="0" x2="40"  y2="220"/>
    <line x1="80"  y1="0" x2="80"  y2="220"/><line x1="120" y1="0" x2="120" y2="220"/>
    <line x1="160" y1="0" x2="160" y2="220"/><line x1="200" y1="0" x2="200" y2="220"/>
    <line x1="240" y1="0" x2="240" y2="220"/><line x1="280" y1="0" x2="280" y2="220"/>
    <line x1="320" y1="0" x2="320" y2="220"/><line x1="360" y1="0" x2="360" y2="220"/>
    <line x1="400" y1="0" x2="400" y2="220"/><line x1="440" y1="0" x2="440" y2="220"/>
    <line x1="480" y1="0" x2="480" y2="220"/><line x1="520" y1="0" x2="520" y2="220"/>
    <line x1="560" y1="0" x2="560" y2="220"/><line x1="600" y1="0" x2="600" y2="220"/>
    <line x1="640" y1="0" x2="640" y2="220"/><line x1="680" y1="0" x2="680" y2="220"/>
    <line x1="720" y1="0" x2="720" y2="220"/><line x1="760" y1="0" x2="760" y2="220"/>
    <line x1="800" y1="0" x2="800" y2="220"/>
    <line x1="0" y1="0"   x2="800" y2="0"  /><line x1="0" y1="40"  x2="800" y2="40" />
    <line x1="0" y1="80"  x2="800" y2="80" /><line x1="0" y1="120" x2="800" y2="120"/>
    <line x1="0" y1="160" x2="800" y2="160"/><line x1="0" y1="200" x2="800" y2="200"/>
    <line x1="0" y1="220" x2="800" y2="220"/>
  </g>

  <!-- Neural network edges -->
  <g stroke="rgba(160,150,255,0.18)" stroke-width="0.8">
    <line x1="60"  y1="40"  x2="150" y2="90" />
    <line x1="150" y1="90"  x2="240" y2="55" />
    <line x1="240" y1="55"  x2="310" y2="130"/>
    <line x1="310" y1="130" x2="420" y2="80" />
    <line x1="420" y1="80"  x2="510" y2="145"/>
    <line x1="510" y1="145" x2="620" y2="100"/>
    <line x1="620" y1="100" x2="720" y2="50" />
    <line x1="720" y1="50"  x2="770" y2="130"/>
    <line x1="60"  y1="40"  x2="240" y2="55" />
    <line x1="150" y1="90"  x2="310" y2="130"/>
    <line x1="240" y1="55"  x2="420" y2="80" />
    <line x1="420" y1="80"  x2="620" y2="100"/>
    <line x1="100" y1="170" x2="200" y2="140"/>
    <line x1="200" y1="140" x2="310" y2="130"/>
    <line x1="310" y1="130" x2="400" y2="180"/>
    <line x1="400" y1="180" x2="510" y2="145"/>
    <line x1="510" y1="145" x2="650" y2="175"/>
    <line x1="650" y1="175" x2="750" y2="165"/>
    <line x1="60"  y1="40"  x2="100" y2="170"/>
    <line x1="720" y1="50"  x2="750" y2="165"/>
  </g>

  <!-- Neural network nodes (glow + core) -->
  <g>
    <circle cx="60"  cy="40"  r="8"  fill="rgba(160,140,255,0.08)" filter="url(#blur3)"/>
    <circle cx="60"  cy="40"  r="2.5" fill="rgba(200,190,255,0.75)"/>
    <circle cx="150" cy="90"  r="8"  fill="rgba(160,140,255,0.08)" filter="url(#blur3)"/>
    <circle cx="150" cy="90"  r="2"  fill="rgba(200,190,255,0.65)"/>
    <circle cx="240" cy="55"  r="8"  fill="rgba(160,140,255,0.08)" filter="url(#blur3)"/>
    <circle cx="240" cy="55"  r="2.5" fill="rgba(200,190,255,0.70)"/>
    <circle cx="310" cy="130" r="8"  fill="rgba(160,140,255,0.08)" filter="url(#blur3)"/>
    <circle cx="310" cy="130" r="2"  fill="rgba(200,190,255,0.60)"/>
    <circle cx="420" cy="80"  r="9"  fill="rgba(160,140,255,0.10)" filter="url(#blur3)"/>
    <circle cx="420" cy="80"  r="3"  fill="rgba(200,190,255,0.80)"/>
    <circle cx="510" cy="145" r="8"  fill="rgba(160,140,255,0.08)" filter="url(#blur3)"/>
    <circle cx="510" cy="145" r="2"  fill="rgba(200,190,255,0.65)"/>
    <circle cx="620" cy="100" r="8"  fill="rgba(160,140,255,0.08)" filter="url(#blur3)"/>
    <circle cx="620" cy="100" r="2.5" fill="rgba(200,190,255,0.70)"/>
    <circle cx="720" cy="50"  r="8"  fill="rgba(160,140,255,0.08)" filter="url(#blur3)"/>
    <circle cx="720" cy="50"  r="2"  fill="rgba(200,190,255,0.60)"/>
    <circle cx="770" cy="130" r="7"  fill="rgba(160,140,255,0.07)" filter="url(#blur3)"/>
    <circle cx="770" cy="130" r="2"  fill="rgba(200,190,255,0.55)"/>
    <circle cx="100" cy="170" r="7"  fill="rgba(160,140,255,0.07)" filter="url(#blur3)"/>
    <circle cx="100" cy="170" r="2"  fill="rgba(200,190,255,0.55)"/>
    <circle cx="200" cy="140" r="7"  fill="rgba(160,140,255,0.07)" filter="url(#blur3)"/>
    <circle cx="200" cy="140" r="2"  fill="rgba(200,190,255,0.60)"/>
    <circle cx="400" cy="180" r="7"  fill="rgba(160,140,255,0.07)" filter="url(#blur3)"/>
    <circle cx="400" cy="180" r="2"  fill="rgba(200,190,255,0.55)"/>
    <circle cx="650" cy="175" r="7"  fill="rgba(160,140,255,0.07)" filter="url(#blur3)"/>
    <circle cx="650" cy="175" r="2"  fill="rgba(200,190,255,0.55)"/>
    <circle cx="750" cy="165" r="7"  fill="rgba(160,140,255,0.07)" filter="url(#blur3)"/>
    <circle cx="750" cy="165" r="2"  fill="rgba(200,190,255,0.55)"/>
  </g>

  <!-- Circuit traces — top-left -->
  <g stroke="rgba(140,130,255,0.12)" stroke-width="1" fill="none">
    <polyline points="20,20 50,20 50,40 80,40"/>
    <polyline points="20,20 20,35 40,35 40,55"/>
    <circle cx="20" cy="20" r="2" fill="rgba(140,130,255,0.25)"/>
    <circle cx="50" cy="20" r="1.5" fill="rgba(140,130,255,0.20)"/>
    <circle cx="50" cy="40" r="1.5" fill="rgba(140,130,255,0.20)"/>
    <circle cx="40" cy="35" r="1.5" fill="rgba(140,130,255,0.20)"/>
  </g>
  <!-- Circuit traces — bottom-right -->
  <g stroke="rgba(140,130,255,0.12)" stroke-width="1" fill="none">
    <polyline points="780,200 750,200 750,180 720,180"/>
    <polyline points="780,200 780,185 760,185 760,165"/>
    <circle cx="780" cy="200" r="2" fill="rgba(140,130,255,0.25)"/>
    <circle cx="750" cy="200" r="1.5" fill="rgba(140,130,255,0.20)"/>
    <circle cx="750" cy="180" r="1.5" fill="rgba(140,130,255,0.20)"/>
    <circle cx="760" cy="185" r="1.5" fill="rgba(140,130,255,0.20)"/>
  </g>

  <!-- Text glow halo -->
  <ellipse cx="400" cy="108" rx="280" ry="55" fill="rgba(160,140,255,0.06)" filter="url(#blur3)"/>

  <!-- Name -->
  <text
    x="400" y="100"
    font-family="'Segoe UI', 'Helvetica Neue', Arial, sans-serif"
    font-size="44" font-weight="700" letter-spacing="-1"
    fill="white" text-anchor="middle"
    style="text-shadow: 0 0 30px rgba(160,140,255,0.5);"
  >Tanay Jagadeesh</text>

  <!-- Subtitle -->
  <text
    x="400" y="130"
    font-family="'Segoe UI', 'Helvetica Neue', Arial, sans-serif"
    font-size="13" font-weight="500" letter-spacing="3"
    fill="rgba(255,255,255,0.60)" text-anchor="middle"
  >DATA ENGINEER  •  AI/ML ENGINEER  •  BUILDING INTELLIGENT SYSTEMS</text>
</svg>

</div>

---

&nbsp;🧠 &nbsp;LLM Research with **Prof. Roberto Foa** (University of Cambridge)

&nbsp;🎙️ &nbsp;Building **voice agents** and a **referral pipeline** with [Wedge (YCS25)](https://www.ycombinator.com/companies/wedge) and Dr. Guha Roy

&nbsp;⚡ &nbsp;**AI/ML Engineer** @ IntoTheOpen

&nbsp;📊 &nbsp;**Incoming Data Science Intern** @ Workplace Safety and Insurance Board (WSIB)

&nbsp;🏆 &nbsp;Won **Canada's largest Data + AI hackathon** — CXC ($1,000 prize, 350+ participants)

---

## Let's Connect

<div align="center">

### Always down to collaborate, build, or just chat.

<p>
  <a href="https://tanayjagadeesh.dev">
    <img src="https://img.shields.io/badge/Portfolio-tanayjagadeesh.dev-1a1a2e?style=for-the-badge&logo=vercel&logoColor=6C63FF" alt="Website"/>
  </a>
  &nbsp;
  <a href="mailto:tanayj2107@gmail.com">
    <img src="https://img.shields.io/badge/Email-tanayj2107%40gmail.com-1a1a2e?style=for-the-badge&logo=maildotru&logoColor=6C63FF" alt="Email"/>
  </a>
  &nbsp;
  <a href="https://linkedin.com/in/tanay-jagadeesh">
    <img src="https://img.shields.io/badge/LinkedIn-tanay--jagadeesh-1a1a2e?style=for-the-badge&logo=linkedin&logoColor=6C63FF" alt="LinkedIn"/>
  </a>
  &nbsp;
  <a href="https://github.com/tanay-jagadeesh">
    <img src="https://img.shields.io/badge/GitHub-tanay--jagadeesh-1a1a2e?style=for-the-badge&logo=github&logoColor=6C63FF" alt="GitHub"/>
  </a>
</p>

</div>
