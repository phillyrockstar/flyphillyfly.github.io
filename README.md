<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>ZerothNyx | Street-Futuristic Guardian Energy</title>
  <meta name="description" content="ZerothNyx is building safer mobility systems, AI-guided protection, and future-forward innovation rooted in purpose." />
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header class="site-header">
    <div class="container nav">
      <div class="brand">ZEROTHNYX</div>
      <nav>
        <ul class="nav-links">
          <li><a href="#home">Home</a></li>
          <li><a href="#projects">Projects</a></li>
          <li><a href="#vision">Vision</a></li>
          <li><a href="#updates">Updates</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <main id="home">
    <section class="hero">
      <div class="hero-bg">
        <img src="images/hero.jpg" alt="Futuristic concept background" />
      </div>
      <div class="container hero-content">
        <p class="eyebrow">Built in Philadelphia. Designed for the future.</p>
        <h1>Street-Futuristic Guardian Energy</h1>
        <p class="subtitle">
          ZerothNyx is a future-facing innovation brand exploring safer mobility,
          AI-assisted protection, advanced materials, and human-centered technology.
        </p>
        <div class="hero-actions">
          <a class="btn" href="#projects">Explore the Vision</a>
          <a class="btn secondary" href="#contact">Connect</a>
        </div>
      </div>
    </section>

    <section id="vision" class="section">
      <div class="container">
        <h2>The Vision</h2>
        <p>
          This is not about hype. It is about building real systems, learning in public,
          and shaping technology that protects people, expands opportunity, and respects life.
        </p>
        <p>
          The mission begins with research, simulation, materials study, software logic,
          and disciplined prototyping — one step at a time.
        </p>
      </div>
    </section>

    <section id="projects" class="section">
      <div class="container">
        <h2>Core Projects</h2>
        <div class="cards">
          <article class="card">
            <h3>Guardian Core</h3>
            <p>
              A software and systems foundation for safety logic, monitoring,
              simulation, and future hardware integration.
            </p>
          </article>

          <article class="card">
            <h3>Power Systems R&amp;D</h3>
            <p>
              Battery research, thermal management concepts, and energy-system modeling
              for future mobility platforms.
            </p>
          </article>

          <article class="card">
            <h3>Materials Index</h3>
            <p>
              A structured library of materials, constraints, tradeoffs, and sourcing notes
              for wearable systems and advanced prototypes.
            </p>
          </article>

          <article class="card">
            <h3>Fly Philly Fly</h3>
            <p>
              A long-term vision exploring personal mobility, safety-first design,
              and technology that helps people rise instead of being left behind.
            </p>
          </article>
        </div>
      </div>
    </section>

    <section id="updates" class="section">
      <div class="container">
        <h2>Current Status</h2>
        <ul class="updates">
          <li>Website foundation launched</li>
          <li>Brand identity and message being refined</li>
          <li>Project architecture and documentation in active development</li>
          <li>Future motion design and interactive visuals planned</li>
        </ul>
      </div>
    </section>

    <section id="contact" class="section">
      <div class="container">
        <h2>Contact</h2>
        <p>Email: contact@zerothnyxofficial.com <span class="muted">(replace when ready)</span></p>
      </div>
    </section>
  </main>

  <footer class="site-footer">
    <div class="container">
      <p>&copy; <span id="year"></span> ZEROTHNYX. All rights reserved.</p>
    </div>
  </footer>

  <script src="script.js"></script>
</body>
</html>
:root {
  --max: 1120px;
  --bg: #070b16;
  --bg-soft: #0d1324;
  --text: #f3f6ff;
  --muted: #b8c1d9;
  --line: rgba(255,255,255,0.12);
  --accent: #7cc7ff;
}

* {
  box-sizing: border-box;
}

html {
  scroll-behavior: smooth;
}

body {
  margin: 0;
  font-family: system-ui, -apple-system, Segoe UI, Roboto, Arial, sans-serif;
  background:
    radial-gradient(circle at top, rgba(70,100,180,0.18), transparent 35%),
    linear-gradient(180deg, #05070f, #0a1020 60%, #060912);
  color: var(--text);
  line-height: 1.6;
}

img {
  max-width: 100%;
  display: block;
}

a {
  color: var(--accent);
  text-decoration: none;
}

.container {
  width: min(100% - 32px, var(--max));
  margin: 0 auto;
}

.site-header {
  position: sticky;
  top: 0;
  z-index: 50;
  backdrop-filter: blur(14px);
  background: rgba(5, 8, 18, 0.65);
  border-bottom: 1px solid var(--line);
}

.nav {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 16px 0;
  gap: 18px;
}

.brand {
  font-weight: 800;
  letter-spacing: 0.08em;
}

.nav-links {
  list-style: none;
  display: flex;
  gap: 16px;
  padding: 0;
  margin: 0;
  flex-wrap: wrap;
}

.nav-links a {
  color: var(--text);
  opacity: 0.88;
}

.hero {
  position: relative;
  min-height: 86vh;
  display: grid;
  align-items: center;
  overflow: hidden;
}

.hero-bg {
  position: absolute;
  inset: 0;
  opacity: 0.28;
}

.hero-bg img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}

.hero-content {
  position: relative;
  z-index: 2;
  padding: 80px 0;
}

.eyebrow {
  text-transform: uppercase;
  letter-spacing: 0.14em;
  font-size: 0.82rem;
  color: var(--muted);
}

h1 {
  font-size: clamp(2.6rem, 6vw, 5.4rem);
  line-height: 0.95;
  margin: 0 0 18px;
  max-width: 10ch;
}

.subtitle {
  max-width: 62ch;
  color: var(--muted);
  font-size: 1.08rem;
}

.hero-actions {
  display: flex;
  gap: 12px;
  margin-top: 24px;
  flex-wrap: wrap;
}

.btn {
  display: inline-block;
  padding: 12px 18px;
  border: 1px solid rgba(255,255,255,0.18);
  border-radius: 999px;
  color: white;
  background: rgba(255,255,255,0.06);
}

.btn.secondary {
  background: transparent;
  opacity: 0.8;
}

.section {
  padding: 72px 0;
  border-top: 1px solid var(--line);
}

h2 {
  font-size: clamp(1.8rem, 4vw, 3rem);
  margin-top: 0;
}

.cards {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
  gap: 18px;
}

.card {
  background: rgba(255,255,255,0.03);
  border: 1px solid var(--line);
  border-radius: 20px;
  padding: 20px;
  transition: transform 0.25s ease, border-color 0.25s ease;
}

.card:hover {
  transform: translateY(-4px);
  border-color: rgba(124,199,255,0.5);
}

.updates {
  padding-left: 20px;
}

.muted {
  color: var(--muted);
}

.site-footer {
  border-top: 1px solid var(--line);
  padding: 24px 0 40px;
  color: var(--muted);
}
