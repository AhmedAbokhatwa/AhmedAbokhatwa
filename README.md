<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />

  <!-- ===== PRIMARY SEO META ===== -->
  <title>Ahmed Abukhatwa – Senior ERPNext Developer & Frappe Engineer | Cairo, Egypt</title>
  <meta name="description" content="Ahmed Abukhatwa is a Senior Software Engineer specializing in Frappe ERPNext development, Django, Vue.js, and Node.js. Open to remote ERP consulting, custom development, and open-source collaboration." />
  <meta name="keywords" content="ERPNext Developer, Frappe Developer, Senior Software Engineer, Django Developer, Vue.js, Node.js, ERP Consulting, Cairo Egypt, Remote Developer, Open Source, SaaS, eCommerce, Backend Optimization" />
  <meta name="author" content="Ahmed Abukhatwa" />
  <meta name="robots" content="index, follow" />
  <link rel="canonical" href="https://ahmedabokhatwa.github.io/" />

  <!-- ===== OPEN GRAPH (LinkedIn / Facebook) ===== -->
  <meta property="og:type" content="profile" />
  <meta property="og:title" content="Ahmed Abukhatwa – Senior ERPNext & Frappe Developer" />
  <meta property="og:description" content="Transforming business operations through intelligent automation and custom ERP solutions. Based in Cairo, Egypt. Open to remote opportunities." />
  <meta property="og:url" content="https://ahmedabokhatwa.github.io/" />
  <meta property="og:image" content="https://avatars.githubusercontent.com/AhmedAbokhatwa" />
  <meta property="profile:first_name" content="Ahmed" />
  <meta property="profile:last_name" content="Abukhatwa" />

  <!-- ===== TWITTER CARD ===== -->
  <meta name="twitter:card" content="summary_large_image" />
  <meta name="twitter:title" content="Ahmed Abukhatwa – Senior ERPNext Developer" />
  <meta name="twitter:description" content="Senior Frappe ERPNext developer from Cairo. Expert in Django, Vue.js, Node.js. Open to remote consulting." />
  <meta name="twitter:image" content="https://avatars.githubusercontent.com/AhmedAbokhatwa" />

  <!-- ===== STRUCTURED DATA (JSON-LD) ===== -->
  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "Person",
    "name": "Ahmed Abukhatwa",
    "jobTitle": "Senior Software Engineer – ERPNext & Frappe Developer",
    "description": "Senior Software Engineer specializing in Frappe ERPNext, Django, Vue.js, and Node.js. Focused on backend performance optimization and custom ERP solutions.",
    "url": "https://ahmedabokhatwa.github.io/",
    "image": "https://avatars.githubusercontent.com/AhmedAbokhatwa",
    "email": "ahmedabukhatwa1@gmail.com",
    "address": {
      "@type": "PostalAddress",
      "addressLocality": "Cairo",
      "addressCountry": "EG"
    },
    "sameAs": [
      "https://github.com/AhmedAbokhatwa",
      "http://linkedin.com/in/ahmed-abukhatwa-641a76251"
    ],
    "knowsAbout": ["ERPNext", "Frappe Framework", "Django", "Vue.js", "Node.js", "Python", "MySQL", "PostgreSQL", "Docker", "Redis"],
    "seeks": "Remote ERP consulting and custom development opportunities"
  }
  </script>

  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link href="https://fonts.googleapis.com/css2?family=Syne:wght@400;600;700;800&family=DM+Mono:wght@300;400;500&display=swap" rel="stylesheet" />

  <style>
    :root {
      --bg: #050A0F;
      --surface: #0C1520;
      --card: #111C2A;
      --border: #1E3048;
      --accent: #00D4FF;
      --accent2: #00FF9D;
      --accent3: #FF6B35;
      --text: #E8F4FD;
      --muted: #6B8CAD;
      --heading: #Syne, sans-serif;
    }

    *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

    body {
      background: var(--bg);
      color: var(--text);
      font-family: 'DM Mono', monospace;
      line-height: 1.6;
      overflow-x: hidden;
    }

    /* Animated grid background */
    body::before {
      content: '';
      position: fixed;
      inset: 0;
      background-image:
        linear-gradient(rgba(0,212,255,0.03) 1px, transparent 1px),
        linear-gradient(90deg, rgba(0,212,255,0.03) 1px, transparent 1px);
      background-size: 60px 60px;
      pointer-events: none;
      z-index: 0;
    }

    .container { max-width: 900px; margin: 0 auto; padding: 0 24px; position: relative; z-index: 1; }

    /* ── HERO ── */
    .hero {
      padding: 80px 0 60px;
      display: grid;
      grid-template-columns: 1fr auto;
      gap: 40px;
      align-items: center;
      border-bottom: 1px solid var(--border);
    }

    .hero-tag {
      font-size: 11px;
      letter-spacing: 3px;
      color: var(--accent);
      text-transform: uppercase;
      margin-bottom: 16px;
      opacity: 0;
      animation: fadeUp 0.6s ease forwards 0.1s;
    }

    .hero-name {
      font-family: 'Syne', sans-serif;
      font-size: clamp(42px, 6vw, 72px);
      font-weight: 800;
      line-height: 1.05;
      background: linear-gradient(135deg, var(--text) 30%, var(--accent));
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      background-clip: text;
      opacity: 0;
      animation: fadeUp 0.6s ease forwards 0.2s;
    }

    .hero-title {
      font-family: 'Syne', sans-serif;
      font-size: 18px;
      font-weight: 600;
      color: var(--accent2);
      margin: 12px 0 20px;
      opacity: 0;
      animation: fadeUp 0.6s ease forwards 0.3s;
    }

    .hero-desc {
      font-size: 14px;
      color: var(--muted);
      max-width: 520px;
      opacity: 0;
      animation: fadeUp 0.6s ease forwards 0.4s;
    }

    .hero-location {
      display: flex;
      align-items: center;
      gap: 6px;
      font-size: 12px;
      color: var(--muted);
      margin-top: 16px;
      opacity: 0;
      animation: fadeUp 0.6s ease forwards 0.5s;
    }

    .hero-location span { color: var(--accent2); }

    .avatar-wrap {
      position: relative;
      opacity: 0;
      animation: fadeIn 0.8s ease forwards 0.3s;
    }

    .avatar-wrap::before {
      content: '';
      position: absolute;
      inset: -3px;
      border-radius: 50%;
      background: conic-gradient(var(--accent), var(--accent2), var(--accent3), var(--accent));
      animation: spin 4s linear infinite;
      z-index: -1;
    }

    .avatar {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      border: 4px solid var(--bg);
      display: block;
      object-fit: cover;
      background: var(--surface);
    }

    /* ── CTA BUTTONS ── */
    .cta-row {
      display: flex;
      flex-wrap: wrap;
      gap: 12px;
      margin-top: 32px;
      opacity: 0;
      animation: fadeUp 0.6s ease forwards 0.6s;
    }

    .btn {
      display: inline-flex;
      align-items: center;
      gap: 8px;
      padding: 10px 20px;
      border-radius: 6px;
      font-family: 'DM Mono', monospace;
      font-size: 12px;
      font-weight: 500;
      text-decoration: none;
      letter-spacing: 0.5px;
      transition: all 0.2s;
      border: 1px solid transparent;
    }

    .btn-primary {
      background: var(--accent);
      color: #000;
      border-color: var(--accent);
    }

    .btn-primary:hover { background: #00BFEA; transform: translateY(-2px); box-shadow: 0 8px 24px rgba(0,212,255,0.3); }

    .btn-ghost {
      background: transparent;
      color: var(--text);
      border-color: var(--border);
    }

    .btn-ghost:hover { border-color: var(--accent); color: var(--accent); transform: translateY(-2px); }

    /* ── SECTION ── */
    .section {
      padding: 56px 0;
      border-bottom: 1px solid var(--border);
    }

    .section-label {
      font-size: 10px;
      letter-spacing: 4px;
      text-transform: uppercase;
      color: var(--accent);
      margin-bottom: 8px;
    }

    .section-title {
      font-family: 'Syne', sans-serif;
      font-size: 28px;
      font-weight: 700;
      margin-bottom: 32px;
      color: var(--text);
    }

    /* ── EXPERTISE CARDS ── */
    .expertise-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
      gap: 16px;
    }

    .expertise-card {
      background: var(--card);
      border: 1px solid var(--border);
      border-radius: 12px;
      padding: 24px;
      transition: all 0.3s;
      position: relative;
      overflow: hidden;
    }

    .expertise-card::before {
      content: '';
      position: absolute;
      top: 0; left: 0; right: 0;
      height: 2px;
      background: linear-gradient(90deg, var(--accent), transparent);
      opacity: 0;
      transition: opacity 0.3s;
    }

    .expertise-card:hover { border-color: var(--accent); transform: translateY(-4px); }
    .expertise-card:hover::before { opacity: 1; }

    .expertise-icon { font-size: 28px; margin-bottom: 12px; }
    .expertise-name {
      font-family: 'Syne', sans-serif;
      font-size: 16px;
      font-weight: 700;
      margin-bottom: 8px;
    }

    .expertise-desc { font-size: 12px; color: var(--muted); line-height: 1.5; }

    /* ── SKILLS ── */
    .skills-grid {
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
    }

    .skill-pill {
      display: inline-flex;
      align-items: center;
      gap: 6px;
      padding: 6px 14px;
      background: var(--card);
      border: 1px solid var(--border);
      border-radius: 100px;
      font-size: 12px;
      color: var(--text);
      transition: all 0.2s;
    }

    .skill-pill:hover { border-color: var(--accent2); color: var(--accent2); }

    .skill-dot {
      width: 6px;
      height: 6px;
      border-radius: 50%;
      background: var(--accent2);
    }

    /* ── CONTACT ── */
    .contact-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 12px;
    }

    .contact-card {
      display: flex;
      align-items: center;
      gap: 14px;
      background: var(--card);
      border: 1px solid var(--border);
      border-radius: 10px;
      padding: 18px 20px;
      text-decoration: none;
      color: var(--text);
      transition: all 0.2s;
    }

    .contact-card:hover { border-color: var(--accent); transform: translateY(-3px); box-shadow: 0 8px 24px rgba(0,212,255,0.1); }

    .contact-icon { font-size: 22px; }
    .contact-label { font-size: 10px; color: var(--muted); letter-spacing: 1px; text-transform: uppercase; }
    .contact-value { font-size: 13px; font-weight: 500; margin-top: 2px; }

    /* ── CURRENT FOCUS ── */
    .focus-list { display: flex; flex-direction: column; gap: 12px; }

    .focus-item {
      display: flex;
      align-items: flex-start;
      gap: 14px;
      background: var(--card);
      border: 1px solid var(--border);
      border-radius: 10px;
      padding: 16px 20px;
    }

    .focus-bullet {
      width: 8px;
      height: 8px;
      border-radius: 50%;
      background: var(--accent3);
      margin-top: 5px;
      flex-shrink: 0;
    }

    .focus-text { font-size: 13px; color: var(--muted); }
    .focus-text strong { color: var(--text); }

    /* ── FOOTER ── */
    footer {
      padding: 40px 0;
      text-align: center;
      font-size: 12px;
      color: var(--muted);
    }

    footer a { color: var(--accent); text-decoration: none; }

    /* ── ANIMATIONS ── */
    @keyframes fadeUp {
      from { opacity: 0; transform: translateY(20px); }
      to   { opacity: 1; transform: translateY(0); }
    }

    @keyframes fadeIn {
      from { opacity: 0; }
      to   { opacity: 1; }
    }

    @keyframes spin {
      to { transform: rotate(360deg); }
    }

    @media (max-width: 600px) {
      .hero { grid-template-columns: 1fr; }
      .avatar-wrap { order: -1; }
      .avatar { width: 80px; height: 80px; }
    }
  </style>
</head>

<body>
  <main class="container" role="main">

    <!-- ── HERO ── -->
    <header class="hero" aria-label="Profile introduction">
      <div>
        <p class="hero-tag">Senior Software Engineer</p>
        <h1 class="hero-name">Ahmed<br>Abukhatwa</h1>
        <h2 class="hero-title">ERPNext &amp; Frappe Developer</h2>
        <p class="hero-desc">
          Transforming business operations through intelligent automation and custom ERP solutions.
          Specializing in large-scale backend performance optimization.
        </p>
        <p class="hero-location">
          📍 Cairo, Egypt &nbsp;·&nbsp; <span>Open to remote opportunities</span>
        </p>
        <nav class="cta-row" aria-label="Profile links">
          <a href="https://github.com/AhmedAbokhatwa" class="btn btn-primary" target="_blank" rel="noopener" aria-label="GitHub Profile">
            ⚡ GitHub Profile
          </a>
          <a href="https://drive.google.com/file/d/1VVdGq1BvpSiJlKSaHECWUZrKbYjfICYb/view?usp=sharing" class="btn btn-ghost" target="_blank" rel="noopener" aria-label="View CV">
            📄 View Resume
          </a>
          <a href="http://linkedin.com/in/ahmed-abukhatwa-641a76251" class="btn btn-ghost" target="_blank" rel="noopener" aria-label="LinkedIn">
            in LinkedIn
          </a>
        </nav>
      </div>
      <div class="avatar-wrap" aria-hidden="true">
        <img
          src="https://avatars.githubusercontent.com/AhmedAbokhatwa"
          alt="Ahmed Abukhatwa – Senior ERPNext Developer"
          class="avatar"
          width="120" height="120"
          loading="eager"
        />
      </div>
    </header>

    <!-- ── EXPERTISE ── -->
    <section class="section" aria-labelledby="expertise-heading">
      <p class="section-label">What I do</p>
      <h2 class="section-title" id="expertise-heading">Core Expertise</h2>
      <div class="expertise-grid">
        <article class="expertise-card">
          <div class="expertise-icon">🏗️</div>
          <h3 class="expertise-name">ERP Development</h3>
          <p class="expertise-desc">Building and customizing Frappe ERPNext solutions tailored to complex business workflows and enterprise-scale operations.</p>
        </article>
        <article class="expertise-card">
          <div class="expertise-icon">⚡</div>
          <h3 class="expertise-name">Backend Performance</h3>
          <p class="expertise-desc">Optimizing large-scale application backends — query tuning, caching strategies with Redis, async processing, and scalability patterns.</p>
        </article>
        <article class="expertise-card">
          <div class="expertise-icon">🌐</div>
          <h3 class="expertise-name">Full-Stack Web</h3>
          <p class="expertise-desc">End-to-end web applications using Vue.js, Django, Node.js/Express, and REST APIs — from architecture to deployment.</p>
        </article>
        <article class="expertise-card">
          <div class="expertise-icon">🤝</div>
          <h3 class="expertise-name">ERP Consulting</h3>
          <p class="expertise-desc">Strategic consulting on ERP system selection, implementation, integration, and ongoing customization for SMEs and enterprises.</p>
        </article>
      </div>
    </section>

    <!-- ── CURRENT FOCUS ── -->
    <section class="section" aria-labelledby="focus-heading">
      <p class="section-label">Right now</p>
      <h2 class="section-title" id="focus-heading">Currently Focused On</h2>
      <div class="focus-list">
        <div class="focus-item">
          <div class="focus-bullet"></div>
          <p class="focus-text"><strong>Backend performance optimization</strong> in large-scale Frappe and Django applications — profiling bottlenecks, restructuring queries, and reducing response times at scale.</p>
        </div>
        <div class="focus-item">
          <div class="focus-bullet"></div>
          <p class="focus-text"><strong>Open-source collaboration</strong> on full-stack web applications, eCommerce platforms, ERP systems, and SaaS products — contributions and co-building welcome.</p>
        </div>
        <div class="focus-item">
          <div class="focus-bullet"></div>
          <p class="focus-text"><strong>ERP consulting engagements</strong> — helping businesses streamline operations through custom ERPNext implementations and smart automation.</p>
        </div>
      </div>
    </section>

    <!-- ── SKILLS ── -->
    <section class="section" aria-labelledby="skills-heading">
      <p class="section-label">Tech stack</p>
      <h2 class="section-title" id="skills-heading">Languages &amp; Tools</h2>
      <div class="skills-grid" role="list">
        <!-- Languages -->
        <span class="skill-pill" role="listitem"><span class="skill-dot"></span>Python</span>
        <span class="skill-pill" role="listitem"><span class="skill-dot"></span>JavaScript</span>
        <span class="skill-pill" role="listitem"><span class="skill-dot"></span>Bash</span>
        <span class="skill-pill" role="listitem"><span class="skill-dot"></span>HTML5</span>
        <span class="skill-pill" role="listitem"><span class="skill-dot"></span>CSS3</span>
        <!-- Frameworks -->
        <span class="skill-pill" role="listitem"><span class="skill-dot" style="background:var(--accent)"></span>Frappe</span>
        <span class="skill-pill" role="listitem"><span class="skill-dot" style="background:var(--accent)"></span>ERPNext</span>
        <span class="skill-pill" role="listitem"><span class="skill-dot" style="background:var(--accent)"></span>Django</span>
        <span class="skill-pill" role="listitem"><span class="skill-dot" style="background:var(--accent)"></span>Vue.js</span>
        <span class="skill-pill" role="listitem"><span class="skill-dot" style="background:var(--accent)"></span>Node.js</span>
        <span class="skill-pill" role="listitem"><span class="skill-dot" style="background:var(--accent)"></span>Express.js</span>
        <span class="skill-pill" role="listitem"><span class="skill-dot" style="background:var(--accent)"></span>React</span>
        <span class="skill-pill" role="listitem"><span class="skill-dot" style="background:var(--accent)"></span>Tailwind CSS</span>
        <span class="skill-pill" role="listitem"><span class="skill-dot" style="background:var(--accent)"></span>Bootstrap</span>
        <!-- Databases -->
        <span class="skill-pill" role="listitem"><span class="skill-dot" style="background:var(--accent3)"></span>MySQL</span>
        <span class="skill-pill" role="listitem"><span class="skill-dot" style="background:var(--accent3)"></span>PostgreSQL</span>
        <span class="skill-pill" role="listitem"><span class="skill-dot" style="background:var(--accent3)"></span>MongoDB</span>
        <span class="skill-pill" role="listitem"><span class="skill-dot" style="background:var(--accent3)"></span>SQLite</span>
        <span class="skill-pill" role="listitem"><span class="skill-dot" style="background:var(--accent3)"></span>Redis</span>
        <!-- DevOps -->
        <span class="skill-pill" role="listitem"><span class="skill-dot" style="background:#FF6B9D"></span>Docker</span>
        <span class="skill-pill" role="listitem"><span class="skill-dot" style="background:#FF6B9D"></span>Nginx</span>
        <span class="skill-pill" role="listitem"><span class="skill-dot" style="background:#FF6B9D"></span>Git</span>
        <span class="skill-pill" role="listitem"><span class="skill-dot" style="background:#FF6B9D"></span>Linux</span>
        <span class="skill-pill" role="listitem"><span class="skill-dot" style="background:#FF6B9D"></span>Postman</span>
      </div>
    </section>

    <!-- ── CONTACT ── -->
    <section class="section" aria-labelledby="contact-heading">
      <p class="section-label">Get in touch</p>
      <h2 class="section-title" id="contact-heading">Connect With Me</h2>
      <div class="contact-grid">
        <a href="mailto:ahmedabukhatwa1@gmail.com" class="contact-card" aria-label="Email Ahmed Abukhatwa">
          <span class="contact-icon">✉️</span>
          <div>
            <div class="contact-label">Email</div>
            <div class="contact-value">ahmedabukhatwa1@gmail.com</div>
          </div>
        </a>
        <a href="http://linkedin.com/in/ahmed-abukhatwa-641a76251" class="contact-card" target="_blank" rel="noopener" aria-label="Ahmed Abukhatwa on LinkedIn">
          <span class="contact-icon">💼</span>
          <div>
            <div class="contact-label">LinkedIn</div>
            <div class="contact-value">ahmed-abukhatwa</div>
          </div>
        </a>
        <a href="https://wa.me/201010871072" class="contact-card" target="_blank" rel="noopener" aria-label="WhatsApp Ahmed Abukhatwa">
          <span class="contact-icon">💬</span>
          <div>
            <div class="contact-label">WhatsApp</div>
            <div class="contact-value">+20 101 087 1072</div>
          </div>
        </a>
        <a href="https://github.com/AhmedAbokhatwa" class="contact-card" target="_blank" rel="noopener" aria-label="Ahmed Abukhatwa on GitHub">
          <span class="contact-icon">🐙</span>
          <div>
            <div class="contact-label">GitHub</div>
            <div class="contact-value">@AhmedAbokhatwa</div>
          </div>
        </a>
      </div>
    </section>

  </main>

  <footer>
    <div class="container">
      <p>
        Open to: <strong style="color:var(--text)">ERP Consulting</strong> · <strong style="color:var(--text)">Custom Development</strong> · <strong style="color:var(--text)">Open Source</strong>
      </p>
      <p style="margin-top:12px;">
        &copy; 2025 Ahmed Abukhatwa · Cairo, Egypt ·
        <a href="https://github.com/AhmedAbokhatwa" rel="noopener">github.com/AhmedAbokhatwa</a>
      </p>
    </div>
  </footer>

</body>
</html>
