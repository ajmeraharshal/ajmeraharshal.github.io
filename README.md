<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>CA Harshal Ajmera | Professional Profile</title>

  <!-- Font -->
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">

  <style>
    :root{
      --bg: #f4f6f8;
      --text: #222;
      --card: #ffffff;
      --accent: #0077b6;
      --muted: #6b7280;
      --glass: rgba(255,255,255,0.6);
    }

    [data-theme="dark"]{
      --bg: #0d1117;
      --text: #e6edf3;
      --card: #111318;
      --accent: #58a6ff;
      --muted: #94a3b8;
      --glass: rgba(255,255,255,0.03);
    }

    * { box-sizing: border-box; }
    html { scroll-behavior: smooth; }
    body{
      margin:0;
      font-family: "Poppins", system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
      background: linear-gradient(180deg,var(--bg), #ffffff 60%);
      color: var(--text);
      transition: background 0.45s ease, color 0.45s ease;
      -webkit-font-smoothing:antialiased;
      -moz-osx-font-smoothing:grayscale;
      min-height:100vh;
      padding: 1.5rem;
    }

    /* Header */
    .site-header{
      max-width: 1100px;
      margin: 0 auto 1.5rem;
      display:flex;
      align-items:center;
      justify-content:space-between;
      gap:1rem;
    }

    .brand {
      display:flex;
      gap:0.75rem;
      align-items:center;
    }

    .brand h3{
      margin:0;
      font-size:0.95rem;
      color: var(--muted);
      font-weight:600;
    }

    .theme-toggle{
      background: linear-gradient(90deg,var(--accent), #00b4d8);
      border: none;
      color: #fff;
      padding: 0.5rem 0.9rem;
      border-radius: 999px;
      font-weight: 600;
      cursor:pointer;
      box-shadow: 0 6px 18px rgba(2,6,23,0.08);
      transition: transform .18s, opacity .18s;
    }
    .theme-toggle:active{ transform: translateY(1px); }
    .theme-toggle:focus{ outline: 3px solid rgba(88,166,255,0.18); }

    /* Main Card */
    .card{
      max-width: 960px;
      margin: 0 auto;
      background: var(--card);
      border-radius: 16px;
      padding: 2rem;
      box-shadow: 0 10px 30px rgba(2,6,23,0.06);
      transition: box-shadow .35s, background .35s;
      overflow: hidden;
    }

    /* top */
    .top {
      display:grid;
      grid-template-columns: 1fr 360px;
      gap: 1.6rem;
      align-items: center;
    }

    /* Left - text */
    .intro h1{
      margin:0;
      color: var(--accent);
      font-size: 2.05rem;
      letter-spacing: -0.02em;
    }
    .intro h2{
      margin: 0.25rem 0 0.8rem;
      font-size: 1rem;
      color: var(--muted);
      font-weight: 500;
    }
    .intro p {
      margin: 0 0 0.9rem;
      line-height:1.65;
      color: var(--text);
    }
    .contact-links {
      margin-top: 0.9rem;
      display:flex;
      gap: 0.8rem;
      justify-content:flex-start;
      flex-wrap:wrap;
    }
    .contact-links a{
      color:var(--card);
      background: linear-gradient(90deg,var(--accent), #00b4d8);
      padding: 0.55rem 0.9rem;
      border-radius: 999px;
      text-decoration:none;
      font-weight:600;
      font-size:0.9rem;
      box-shadow: 0 6px 18px rgba(2,6,23,0.06);
      display:inline-flex;
      align-items:center;
      gap:0.5rem;
    }
    .contact-links a.tel{ background: linear-gradient(90deg,#06b6d4,#0077b6); }
    .resume-download{
      margin-left: 0.35rem;
      background: transparent;
      border: 2px solid var(--accent);
      color: var(--accent);
    }
    .resume-download:hover{
      background: var(--accent);
      color: #fff;
    }

    /* Right - anime animation container */
    .anime-wrap{
      display:flex;
      align-items:center;
      justify-content:center;
      width:100%;
    }
    .anime {
      width: 320px;
      height: 320px;
      border-radius: 14px;
      background: var(--glass);
      display:flex;
      align-items:center;
      justify-content:center;
      box-shadow: 0 8px 30px rgba(2,6,23,0.06);
      transition: transform .45s;
      padding: 6px;
    }

    /* Fade in animations */
    .fade-up{
      opacity:0;
      transform: translateY(18px);
      animation: fadeUp .9s ease forwards;
    }
    .delay-1{ animation-delay: .12s; }
    .delay-2{ animation-delay: .22s; }
    .delay-3{ animation-delay: .32s; }
    @keyframes fadeUp{
      to { opacity:1; transform: translateY(0); }
    }

    /* Beyond Work section */
    .beyond {
      margin-top: 1.6rem;
      padding-top: 1rem;
      border-top: 1px dashed rgba(0,0,0,0.04);
    }
    .beyond h3{
      margin:0 0 0.5rem;
      color: var(--muted);
      font-size: 0.95rem;
      letter-spacing: .2px;
    }
    .beyond p{
      margin:0 0 1rem;
      color: var(--text);
    }

    .interest-grid{
      display:grid;
      grid-template-columns: repeat(2, minmax(0,1fr));
      gap: 0.9rem;
      max-width: 520px;
      margin: 0 auto;
    }

    .interest {
      background: linear-gradient(180deg, rgba(255,255,255,0.6), rgba(255,255,255,0.35));
      border-radius: 12px;
      padding: 0.9rem 1rem;
      display:flex;
      align-items:center;
      justify-content:center;
      gap:0.6rem;
      font-weight:600;
      color: var(--accent);
      box-shadow: 0 6px 20px rgba(2,6,23,0.04);
      transition: transform .22s, box-shadow .22s, background .22s;
      cursor: default;
      user-select: none;
    }
    [data-theme="dark"] .interest { background: linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01)); color: var(--accent); box-shadow:none; border: 1px solid rgba(255,255,255,0.03); }

    .interest:hover{
      transform: translateY(-6px);
      box-shadow: 0 10px 30px rgba(2,6,23,0.08);
    }

    /* Footer */
    footer{
      text-align:center;
      margin-top:1.6rem;
      color: var(--muted);
      font-size:0.9rem;
    }

    /* Responsive */
    @media (max-width: 880px){
      .top { grid-template-columns: 1fr; }
      .anime { width: 260px; height:260px; margin-top:8px; }
      .contact-links { justify-content:center; }
      .card { padding:1.5rem; }
    }
    @media (max-width: 420px){
      .anime { width: 220px; height:220px; }
      .brand h3 { font-size:0.85rem; }
      .intro h1 { font-size:1.6rem; }
    }
  </style>
</head>

<body>
  <!-- Header -->
  <header class="site-header">
    <div class="brand">
      <svg width="36" height="36" viewBox="0 0 24 24" fill="none" aria-hidden style="margin-right:8px">
        <rect x="1" y="1" width="22" height="22" rx="6" fill="url(#g)"></rect>
        <defs>
          <linearGradient id="g" x1="0" x2="1" y1="0" y2="1">
            <stop offset="0" stop-color="#00b4d8"/>
            <stop offset="1" stop-color="#0077b6"/>
          </linearGradient>
        </defs>
      </svg>
      <h3>CA Harshal Ajmera — Professional Portfolio</h3>
    </div>

    <button class="theme-toggle" id="themeToggle" aria-pressed="false">🌗 Toggle Theme</button>
  </header>

  <!-- Main card -->
  <main class="card" role="main">
    <div class="top">
      <!-- Left -->
      <div class="intro fade-up delay-1">
        <h1>CA Harshal Ajmera</h1>
        <h2>Assistant Manager • BPCL • Chartered Accountant • CFA Level II</h2>

        <p>
          I am a Chartered Accountant and CFA Level II candidate with over four years of experience in internal audit, data analytics, and process improvement.
          I focus on leveraging technology to enhance audit efficiency and data-driven decision-making. At BPCL, I built interactive audit dashboards and led a
          team that generated exception reports using ACL to improve timeliness and accuracy of audit insights.
        </p>

        <p class="fade-up delay-2">
          I am passionate about integrating technology with finance to drive smarter business insights — using analytics and automation to improve transparency,
          efficiency and risk management across financial processes.
        </p>

         <p>
          I have provided training to all the new joinees in the department on the audit dashboards and the audit command language.
        </p>

        <div class="contact-links fade-up delay-3" aria-hidden>
          <a class="tel" href="tel:+919975126277">📞 +91 9975126277</a>
          <a href="mailto:ajmeraharshal3599@gmail.com">✉️ Email</a>
          <a href="https://www.linkedin.com/in/harshal-ajmera-0b2b95192" target="_blank" rel="noopener">🔗 LinkedIn</a>
          <a class="resume-download" href="Harshal_Ajmera_Resume.pdf" download>📄 Download Resume</a>
        </div>
      </div>

      <!-- Right -->
      <div class="anime-wrap fade-up delay-2" aria-hidden>
        <div class="anime" role="img" aria-label="Subtle animation of a professional working at desk">
          <!-- Lottie animation (subtle professional working loop) -->
          <script src="https://unpkg.com/@lottiefiles/lottie-player@latest/dist/lottie-player.js"></script>
          <lottie-player
            src="https://assets1.lottiefiles.com/packages/lf20_jtbfg2nb.json"
            background="transparent"
            speed="1"
            loop
            autoplay
            style="width:100%;height:100%;border-radius:12px;">
          </lottie-player>
        </div>
      </div>
    </div>

    <!-- Beyond Work -->
    <section class="beyond fade-up delay-3" aria-labelledby="beyond-heading">
      <h3 id="beyond-heading">Beyond Work</h3>
      <p>Outside of work, I’m passionate about exploring new places, staying active, enjoying great entertainment, and keeping up with the world of finance.</p>

      <div class="interest-grid" role="list" aria-label="Interests">
        <div class="interest" role="listitem">🎒 Travelling</div>
        <div class="interest" role="listitem">⚽ Sports</div>
        <div class="interest" role="listitem">🎬 Entertainment</div>
        <div class="interest" role="listitem">💰 Finance World</div>
      </div>
    </section>

    <footer class="fade-up delay-3" aria-hidden>
      <p>© 2025 Harshal Ajmera • Built with ❤️ using HTML &amp; CSS</p>
    </footer>
  </main>

  <script>
    // Theme: remember preference
    const root = document.documentElement;
    const toggleBtn = document.getElementById('themeToggle');

    // initialize theme from localStorage or OS preference
    const savedTheme = localStorage.getItem('theme');
    if (savedTheme) {
      root.setAttribute('data-theme', savedTheme);
      toggleBtn.setAttribute('aria-pressed', savedTheme === 'dark');
    } else {
      // optional: respect prefers-color-scheme
      const prefersDark = window.matchMedia && window.matchMedia('(prefers-color-scheme: dark)').matches;
      root.setAttribute('data-theme', prefersDark ? 'dark' : 'light');
      toggleBtn.setAttribute('aria-pressed', prefersDark);
    }

    toggleBtn.addEventListener('click', () => {
      const current = root.getAttribute('data-theme');
      const next = current === 'dark' ? 'light' : 'dark';
      root.setAttribute('data-theme', next);
      localStorage.setItem('theme', next);
      toggleBtn.setAttribute('aria-pressed', next === 'dark');
    });

    // small: add staggered fade-up when section enters viewport
    document.addEventListener('DOMContentLoaded', () => {
      const faders = document.querySelectorAll('.fade-up');
      const io = new IntersectionObserver((entries) => {
        entries.forEach(e => {
          if (e.isIntersecting) {
            e.target.style.animationPlayState = 'running';
          }
        });
      }, { threshold: 0.15 });
      faders.forEach(el => {
        el.style.animationPlayState = 'paused';
        io.observe(el);
      });
    });
  </script>
</body>
</html>
