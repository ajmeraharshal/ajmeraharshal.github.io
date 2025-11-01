<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>CA Harshal Ajmera | AI & Finance Professional</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap');

    :root {
      --bg-color: #f9fafc;
      --text-color: #333;
      --primary-color: #004aad;
      --accent-color: #ffc107;
      --card-bg: #ffffff;
    }

    body.dark {
      --bg-color: #0f172a;
      --text-color: #f1f5f9;
      --primary-color: #60a5fa;
      --accent-color: #facc15;
      --card-bg: #1e293b;
    }

    body {
      font-family: 'Poppins', sans-serif;
      margin: 0;
      background: var(--bg-color);
      color: var(--text-color);
      transition: all 0.5s ease;
    }

    header {
      background: linear-gradient(135deg, var(--primary-color), #007bff);
      color: white;
      text-align: center;
      padding: 60px 20px 100px;
      position: relative;
      transition: background 0.5s ease;
    }

    header img {
      width: 140px;
      height: 140px;
      border-radius: 50%;
      object-fit: cover;
      border: 4px solid #fff;
      box-shadow: 0 4px 20px rgba(0,0,0,0.2);
      margin-bottom: 15px;
    }

    header h1 {
      font-size: 2.5rem;
      margin: 10px 0 5px;
    }

    header h3 {
      font-weight: 400;
      color: #dbeafe;
      margin: 0 0 10px;
    }

    main {
      background: var(--card-bg);
      max-width: 950px;
      margin: -60px auto 50px;
      padding: 40px;
      border-radius: 20px;
      box-shadow: 0 8px 30px rgba(0,0,0,0.1);
      transition: all 0.5s ease;
    }

    h2 {
      color: var(--primary-color);
      border-left: 5px solid var(--accent-color);
      padding-left: 10px;
      margin-bottom: 20px;
      font-weight: 600;
    }

    li {
      background: rgba(0,0,0,0.05);
      margin: 8px 0;
      padding: 10px 15px;
      border-radius: 8px;
      transition: all 0.3s ease;
    }

    body.dark li {
      background: rgba(255,255,255,0.05);
    }

    li:hover {
      transform: translateX(5px);
    }

    .skills-bar {
      background: #e0e0e0;
      border-radius: 10px;
      overflow: hidden;
      height: 10px;
      margin-top: 5px;
    }

    body.dark .skills-bar {
      background: #334155;
    }

    .bar {
      height: 10px;
      background: linear-gradient(90deg, var(--primary-color), #00b4d8);
      width: 0;
      border-radius: 10px;
      animation: growBar 2s ease forwards;
    }

    @keyframes growBar {
      to {width: var(--width);}
    }

    .toggle-btn {
      position: absolute;
      top: 20px;
      right: 20px;
      background: var(--accent-color);
      color: #000;
      border: none;
      border-radius: 25px;
      padding: 8px 16px;
      font-weight: 600;
      cursor: pointer;
      transition: all 0.3s ease;
    }

    .toggle-btn:hover {
      transform: scale(1.05);
    }

    footer {
      background: var(--primary-color);
      color: white;
      text-align: center;
      padding: 15px;
      font-size: 0.9rem;
      letter-spacing: 0.3px;
      transition: background 0.5s ease;
    }

    @media (max-width: 768px) {
      main {
        margin: -40px 15px 30px;
        padding: 30px;
      }
    }
  </style>
</head>
<body>

  <header>
    <button class="toggle-btn" id="theme-toggle">🌙 Dark Mode</button>
    <img src="https://i.ibb.co/r2F3x4W/profile-placeholder.jpg" alt="Harshal Ajmera Photo">
    <h1>CA Harshal Ajmera</h1>
    <h3>Assistant Manager – BPCL | Chartered Accountant | CFA Level II</h3>
    <p>Exploring how AI is transforming finance, investments & audit efficiency.</p>
  </header>

  <main>
    <section>
      <h2>About Me</h2>
      <p>
        I am a Chartered Accountant and CFA Level II candidate currently working as an Assistant Manager at 
        Bharat Petroleum Corporation Limited (BPCL), with over four years of experience in internal audit, 
        data analytics, and process improvement. My work focuses on leveraging technology to enhance audit 
        efficiency and drive data-based decision-making.
      </p>
      <p>
        I have developed interactive audit dashboards and led a team responsible for generating exception 
        reports using ACL, improving the timeliness and accuracy of audit insights. I am passionate about 
        exploring how Artificial Intelligence can transform financial analysis, portfolio management, and 
        the future of intelligent investing.
      </p>
      <p>
      I have provided training to all the new joinees in the department on the audit dashboards and 
        the audit command language.
      <p>
    </section>

    <section>
      <h2>Core Skills</h2>
      <ul>
        <li>Internal Audit & Risk Management <div class="skills-bar"><div class="bar" style="--width:90%"></div></div></li>
        <li>Financial Analysis & Reporting <div class="skills-bar"><div class="bar" style="--width:85%"></div></div></li>
        <li>Data Analytics & Visualization <div class="skills-bar"><div class="bar" style="--width:80%"></div></div></li>
        <li>ACL (Audit Command Language) <div class="skills-bar"><div class="bar" style="--width:75%"></div></div></li>
        <li>AI in Finance & Investments <div class="skills-bar"><div class="bar" style="--width:70%"></div></div></li>
      </ul>
    </section>

    <section>
      <h2>Speaker Session</h2>
      <p>
        <strong>Topic:</strong> <em>AI in Mutual Funds</em><br><br>
        <strong>Overview:</strong> Understanding how Artificial Intelligence is reshaping 
        mutual fund analysis, portfolio optimization, and investor decision-making. 
        This session bridges traditional financial understanding with cutting-edge AI 
        applications — helping professionals navigate the next era of intelligent investing.
      </p>
    </section>

    <section class="contact">
      <h2>Contact</h2>
      <p>
        📞 +91 9975126277 <br>
        📧 <a href="mailto:ajmeraharshal3599@gmail.com">ajmeraharshal3599@gmail.com</a> <br>
        🔗 <a href="https://www.linkedin.com/in/harshal-ajmera-0b2b95192" target="_blank">LinkedIn Profile</a>
      </p>
    </section>
  </main>

  <footer>
    © 2025 CA Harshal Ajmera | Designed with passion for Finance & AI
  </footer>

  <script>
    const toggleBtn = document.getElementById('theme-toggle');
    const body = document.body;

    // Load saved theme
    const currentTheme = localStorage.getItem('theme');
    if (currentTheme === 'dark') {
      body.classList.add('dark');
      toggleBtn.textContent = '☀️ Light Mode';
    }

    toggleBtn.addEventListener('click', () => {
      body.classList.toggle('dark');
      const isDark = body.classList.contains('dark');
      toggleBtn.textContent = isDark ? '☀️ Light Mode' : '🌙 Dark Mode';
      localStorage.setItem('theme', isDark ? 'dark' : 'light');
    });
  </script>

</body>
</html>
