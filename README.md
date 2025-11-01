<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Harshal Ajmera | Digital Profile</title>
  <meta name="description" content="Simple editable single-file digital profile template" />
  <style>
    :root{--accent:#0b63ff;--bg:#0f1724;--card:#0b1220;--muted:#94a3b8;font-family:Inter,system-ui,Arial}
    html,body{height:100%;margin:0;background:linear-gradient(180deg,#071124 0%, #071224 100%);color:#e6eef8}
    .container{max-width:920px;margin:40px auto;padding:28px}
    header{display:flex;gap:20px;align-items:center}
    .avatar{width:100px;height:100px;border-radius:16px;background:linear-gradient(135deg,var(--accent),#34d399);display:flex;align-items:center;justify-content:center;font-weight:700}
    h1{margin:0;font-size:28px}
    .role{color:var(--muted);margin-top:6px}
    .contact{margin-left:auto;text-align:right;color:var(--muted)}
    .card{background:rgba(255,255,255,0.03);padding:18px;border-radius:14px;margin-top:18px}
    .grid{display:grid;grid-template-columns:1fr 320px;gap:18px}
    .skills {display:flex;flex-wrap:wrap;gap:8px;margin-top:8px}
    .skill-pill{background:rgba(255,255,255,0.04);padding:8px 10px;border-radius:999px;font-size:13px}
    .section-title{font-weight:700;margin-bottom:8px}
    .experience .item{margin-bottom:12px}
    footer{margin-top:20px;color:var(--muted);font-size:13px;text-align:center}
    @media (max-width:840px){.grid{grid-template-columns:1fr}.contact{margin-left:0;text-align:left}}
    a.link{color:var(--accent);text-decoration:none}
    .stat{font-size:28px;font-weight:700}
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="avatar">HA</div>
      <div>
        <h1 id="name">Harshal Ajmera</h1>
        <div class="role" id="role">Chartered Accountant | Finance Content Creator</div>
        <div class="muted" id="location">Mumbai, India</div>
      </div>

      <div class="contact">
        <div id="email">ajmeraharshal3599@gmail.com</div>
        <div style="margin-top:6px"><a id="linkedin" class="link" href="https://www.linkedin.com/in/harshal-ajmera-0b2b95192" target="_blank">LinkedIn</a> • +91 99751 26277</div>
      </div>
    </header>

    <main class="grid">
      <div>
        <section class="card" id="about">
          <div class="section-title">About Me</div>
          <div id="aboutText">I create easy-to-understand finance content on Instagram and YouTube, and work in internal audit. I help non-finance audiences learn investing, personal finance, and tax basics.</div>
        </section>

        <section class="card" style="margin-top:14px" id="experience">
          <div class="section-title">Work Experience</div>
          <div class="experience">
            <div class="item">
              <strong>Internal Audit — Bharat Petroleum Corporation Ltd (BPCL)</strong>
              <div class="muted">Assistant Manager (Internal Audit)</div>
              <div class="muted" style="margin-top:6px">Mar 2024 — Present</div>
              <div style="margin-top:6px">Lead internal audit projects across SBUs and design unified risk-rating frameworks.</div>
            </div>

            <div class="item">
              <strong>Previous — RB Sharma &amp; Co</strong>
              <div class="muted">Article Assistant</div>
            </div>
          </div>
        </section>

        <section class="card" style="margin-top:14px" id="teaching">
          <div class="section-title">Teaching & Workshops</div>
          <div>Created short Reels, 7-slide posts, and conducted workshops on topics such as Advanced Excel, SIP myths, mutual funds, and personal finance basics.</div>
        </section>

      </div>

      <aside>
        <div class="card" id="skillsCard">
          <div class="section-title">Skills</div>
          <div class="skills" id="skillsList">
            <!-- Skills are rendered here from the JS array below. Edit the `skillsData` array in the script to update. -->
          </div>
        </div>

        <div class="card" style="margin-top:14px;text-align:center">
          <div class="section-title">Key Numbers</div>
          <div class="stat">600+</div>
          <div class="muted">Individuals Trained</div>
        </div>

        <div class="card" style="margin-top:14px">
          <div class="section-title">Quick Links</div>
          <div><a class="link" target="_blank" href="#">Instagram</a></div>
          <div style="margin-top:6px"><a class="link" target="_blank" href="#">YouTube</a></div>
        </div>
      </aside>
    </main>

    <footer>
      © <span id="year">2025</span> Harshal Ajmera. All rights reserved.
    </footer>
  </div>

  <script>
    /* =========================
       EASY EDIT: update these fields
       - skillsData: array of strings for skills shown as pills
       - contact & header fields below
       After editing, save this file as index.html and push to your GitHub repo.
       ========================= */

    const skillsData = [
      "Financial Analysis",
      "Advanced Excel",
      "Power BI",
      "Audit & Compliance",
      "Content Creation",
      "SIP / Mutual Funds",
      "Personal Finance",
      "Automation (VBA)"
    ];

    // Render skills
    const skillsList = document.getElementById('skillsList');
    skillsData.forEach(s => {
      const el = document.createElement('div');
      el.className = 'skill-pill';
      el.textContent = s;
      skillsList.appendChild(el);
    });

    // Small helper: set year automatically
    document.getElementById('year').textContent = new Date().getFullYear();

    /* ===== To customize header/contact/about quickly =====
       Edit the values below or wire them to a small JSON you'd fetch.
    */
    // document.getElementById('name').textContent = 'Harshal Ajmera';
    // document.getElementById('role').textContent = 'Chartered Accountant | Finance Content Creator';
    // document.getElementById('location').textContent = 'Mumbai, India';
    // document.getElementById('email').textContent = 'ajmeraharshal3599@gmail.com';
    // document.getElementById('linkedin').href = 'https://www.linkedin.com/in/harshal-ajmera-0b2b95192';

  </script>
</body>
</html>
