<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>CA Harshal Ajmera | Professional Profile</title>
  <style>
    :root {
      --bg-color: #f4f6f8;
      --text-color: #222;
      --card-bg: #fff;
      --accent: #0077b6;
    }

    [data-theme='dark'] {
      --bg-color: #0d1117;
      --text-color: #e6edf3;
      --card-bg: #161b22;
      --accent: #58a6ff;
    }

    body {
      font-family: 'Poppins', sans-serif;
      background-color: var(--bg-color);
      color: var(--text-color);
      margin: 0;
      padding: 0;
      transition: background 0.4s, color 0.4s;
    }

    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 1rem 2rem;
    }

    .theme-toggle {
      cursor: pointer;
      border: none;
      background: var(--accent);
      color: white;
      padding: 0.5rem 1rem;
      border-radius: 20px;
      font-size: 0.9rem;
      transition: all 0.3s ease;
    }

    .theme-toggle:hover {
      opacity: 0.85;
    }

    .container {
      display: flex;
      flex-direction: column;
      align-items: center;
      text-align: center;
      max-width: 900px;
      margin: 2rem auto;
      padding: 2rem;
      background: var(--card-bg);
      border-radius: 20px;
      box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
    }

    h1 {
      color: var(--accent);
      font-size: 2.5rem;
      margin-bottom: 0.3rem;
    }

    h2 {
      font-weight: 500;
      font-size: 1.2rem;
      margin-bottom: 1rem;
    }

    .anime {
      width: 300px;
      height: 300px;
      margin: 1.5rem 0;
    }

    p {
      line-height: 1.7;
      margin-bottom: 1rem;
    }

    .contact {
      margin-top: 1.5rem;
    }

    .contact a {
      color: var(--accent);
      text-decoration: none;
      margin: 0 0.8rem;
      font-weight: 500;
      transition: color 0.3s ease;
    }

    .contact a:hover {
      color: #ff9800;
    }

    .resume-btn {
      display: inline-block;
      margin-top: 1.5rem;
      background: var(--accent);
      color: #fff;
      padding: 0.8rem 1.5rem;
      border-radius: 25px;
      text-decoration: none;
      font-weight: 600;
      transition: background 0.3s ease;
    }

    .resume-btn:hover {
      background: #ff9800;
    }

    footer {
      text-align: center;
      margin-top: 3rem;
      font-size: 0.9rem;
      color: #888;
    }
  </style>
</head>

<body>
  <header>
    <h3>🌐 My Professional Portfolio</h3>
    <button class="theme-toggle" id="themeToggle">🌗 Toggle Theme</button>
  </header>

  <div class="container">
    <h1>CA Harshal Ajmera</h1>
    <h2>Assistant Manager | BPCL | CA | CFA Level II</h2>

    <!-- Anime Animation -->
    <div class="anime">
      <lottie-player src="https://assets1.lottiefiles.com/packages/lf20_jtbfg2nb.json" background="transparent" speed="1" loop autoplay></lottie-player>
    </div>

    <p>
      I am a Chartered Accountant and CFA Level II candidate currently working as an Assistant Manager at Bharat Petroleum Corporation Limited (BPCL), with over four years of experience in internal audit, data analytics, and process improvement.
      My work focuses on leveraging technology to enhance audit efficiency and data-driven decision-making. At BPCL, I have developed interactive audit dashboards and led a team responsible for generating exception reports using the ACL language.
    </p>

    <p>
      I am deeply passionate about integrating technology with finance to drive smarter business insights. My interest lies in using data analytics and automation to improve transparency, efficiency, and risk management across financial processes.
      I continuously explore new ways to combine analytical thinking with innovation for better decision-making.
    </p>

    <p>
      I have provided training to all the new joinees in the department on the audit dashboards and the audit command language.
    </p>
    
    <div class="contact">
      <a href="tel:+919975126277">📞 +91 9975126277</a>
      <a href="mailto:ajmeraharshal3599@gmail.com">✉️ ajmeraharshal3599@gmail.com</a>
      <a href="https://www.linkedin.com/in/harshal-ajmera-0b2b95192" target="_blank">🔗 LinkedIn</a>
    </div>

    <!-- Resume Download Button -->
    <a href="Resume_Harshal Ajmera.pdf" download class="download-btn">Download Resume</a>
  </div>

  <footer>
    © 2025 Harshal Ajmera | Built with ❤️ using HTML & CSS
  </footer>

  <!-- Lottie Player Script -->
  <script src="https://unpkg.com/@lottiefiles/lottie-player@latest/dist/lottie-player.js"></script>

  <!-- Theme Toggle Script -->
  <script>
    const toggle = document.getElementById("themeToggle");
    toggle.addEventListener("click", () => {
      const currentTheme = document.documentElement.getAttribute("data-theme");
      const newTheme = currentTheme === "dark" ? "light" : "dark";
      document.documentElement.setAttribute("data-theme", newTheme);
    });
  </script>
</body>
</html>
