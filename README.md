<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>CA Harshal Ajmera | Professional Profile</title>
  <style>
    body {
      font-family: 'Poppins', sans-serif;
      margin: 0;
      padding: 0;
      background-color: var(--bg);
      color: var(--text);
      transition: background 0.3s, color 0.3s;
    }

    :root {
      --bg: #f9fafb;
      --text: #111827;
      --card-bg: #ffffff;
      --glow: rgba(0, 0, 0, 0.1);
    }

    [data-theme="dark"] {
      --bg: #111827;
      --text: #f9fafb;
      --card-bg: #1f2937;
      --glow: rgba(255, 255, 255, 0.1);
    }

    .container {
      max-width: 900px;
      margin: 0 auto;
      padding: 2rem;
      text-align: center;
    }

    h1 {
      font-size: 2.5rem;
      margin-bottom: 0.5rem;
    }

    h2 {
      margin-top: 2rem;
      color: #6366f1;
      font-weight: 600;
    }

    p {
      max-width: 700px;
      margin: 0.5rem auto;
      line-height: 1.6;
      font-size: 1rem;
    }

    .anime-container {
      width: 250px;
      height: 250px;
      margin: 1.5rem auto;
      background: url('https://cdn.dribbble.com/users/25514/screenshots/16073968/media/b2b06e217dfda3e21b13a0e2e7ad4c32.gif') center/cover no-repeat;
      border-radius: 50%;
      box-shadow: 0 0 20px var(--glow);
    }

    .btn {
      display: inline-block;
      padding: 0.8rem 1.5rem;
      margin: 0.5rem;
      border: none;
      border-radius: 30px;
      cursor: pointer;
      background: #6366f1;
      color: #fff;
      font-weight: 500;
      transition: transform 0.2s ease, box-shadow 0.3s ease;
      text-decoration: none;
    }

    .btn:hover {
      transform: translateY(-3px);
      box-shadow: 0 0 15px #6366f1;
    }

    .interest-grid {
      display: grid;
      grid-template-columns: repeat(2, 1fr);
      gap: 1rem;
      max-width: 400px;
      margin: 1rem auto;
    }

    .interest-btn {
      padding: 0.8rem 1rem;
      border-radius: 25px;
      background: var(--card-bg);
      box-shadow: 0 0 10px var(--glow);
      font-size: 0.95rem;
      transition: all 0.3s ease;
    }

    .interest-btn:hover {
      box-shadow: 0 0 15px #6366f1;
      transform: translateY(-3px);
    }

    .theme-toggle {
      position: absolute;
      top: 20px;
      right: 20px;
      background: none;
      border: none;
      cursor: pointer;
      font-size: 1.2rem;
      color: var(--text);
    }

    footer {
      margin-top: 3rem;
      font-size: 0.9rem;
      color: #6b7280;
    }
  </style>
</head>
<body>
  <button class="theme-toggle" onclick="toggleTheme()">🌙</button>

  <div class="container">
    <div class="anime-container"></div>
    <h1>CA Harshal Ajmera</h1>
    <p>Assistant Manager at BPCL | Chartered Accountant | CFA Level II Candidate</p>

    <h2>About Me</h2>
    <p>
      I am a finance professional with 4 years of experience at BPCL, specializing in internal audit, data analytics, and process improvement.
      I’ve led projects developing audit dashboards and automated exception reports using ACL, improving efficiency and insight quality.
      I’m passionate about exploring how AI can enhance investment decisions, financial analysis, and audit efficiency.
    </p>

    <h2>Beyond Work</h2>
    <p>Outside of work, I’m passionate about exploring new places, staying active, enjoying great entertainment, and keeping up with the world of finance.</p>
    <div class="interest-grid">
      <div class="interest-btn">🎒 Travelling</div>
      <div class="interest-btn">⚽ Sports</div>
      <div class="interest-btn">🎬 Entertainment</div>
      <div class="interest-btn">💰 Finance World</div>
    </div>

    <h2>Contact</h2>
    <p>📧 ajmeraharshal3599@gmail.com | 📞 +91 9975126277</p>
    <p><a href="https://www.linkedin.com/in/harshal-ajmera-0b2b95192" target="_blank" class="btn">LinkedIn</a></p>
    <a href="Harshal_Ajmera_Resume.pdf" download class="btn">📄 Download Resume</a>
  </div>

  <footer>© 2025 Harshal Ajmera | Built with ❤️ using HTML & CSS</footer>

  <script>
    function toggleTheme() {
      const currentTheme = document.documentElement.getAttribute("data-theme");
      const newTheme = currentTheme === "dark" ? "" : "dark";
      document.documentElement.setAttribute("data-theme", newTheme);
      document.querySelector(".theme-toggle").textContent = newTheme === "dark" ? "☀️" : "🌙";
    }
  </script>
</body>
</html>
