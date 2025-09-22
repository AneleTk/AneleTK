<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Tankiso Phoofolo — Portfolio</title>
  <meta name="description" content="Portfolio website for Tankiso Phoofolo — SIEM, Splunk dashboards, log analysis." />
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <header>
    <h1>Tankiso Phoofolo</h1>
    <p>Cybersecurity Analyst</p>
    <nav>
      <a href="#projects">Projects</a>
      <a href="#about">About</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <h2>About me</h2>
    <p>Hi, I'm Tankiso. My best kinds of projects are ones that are meaningful to me. Take a look at some of my work below</p>
  </section>

  <section id="projects" class="projects">
    <div class="project">
      <img src="Images/Splunk dashboard_Best_edited.jpg" alt="SIEM dashboard screenshot">
      <div class="project-content">
        <h3>SIEM & Threat Monitoring</h3>
        <p>A consolidated dashboard ingesting logs from routers, EDR, IDS/IPS, vulnerability scanners, and network controllers.</p>
        <div class="tags">
          <span class="tag">Splunk</span>
          <span class="tag">Sophos</span>
          <span class="tag">Snort</span>
          <span class="tag">Nessus</span>
          <span class="tag">Qualys</span>
          <span class="tag">Ubiquiti</span>
        </div>
      </div>
    </div>

    
  </section>

  <footer>
    <p>© 2025 Tankiso Phoofolo — Built for success</p>
  </footer>
</body>
</html>

body {
  margin: 0;
  font-family: Arial, sans-serif;
  background: linear-gradient(135deg, #22203f, #0d0d0d);
  color: #f0f0f0;
  line-height: 1.6;
}

header {
  text-align: center;
  padding: 2rem;
  background: linear-gradient(135deg, #22203f, #0d0d0d);
  border-bottom: 2px solid #d4af37;
}   

header h1 {
  margin: 0;
  font-size: 2.5rem;
  color: #488cc0;
}

header p {
  margin: 0.5rem 0;
  font-size: 1.1rem;
  color: #db9826;
}

nav {
  margin-top: 1rem;
}

nav a {
  color: #f0f0f0;
  text-decoration: none;
  margin: 0 1rem;
  font-weight: bold;
  transition: color 0.3s;
}

nav a:hover {
  color: #d4af37;
}

.hero {
  text-align: center;
  padding: 3rem 1rem;
  background: linear-gradient(135deg, #22203f, #0d0d0d);
}

.hero h2 {
  font-size: 2rem;
  margin-bottom: 1rem;
  color: #db9826;
}

.projects {
  max-width: 1200px;
  margin: 2rem auto;
  padding: 0 1rem;
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 2rem;
}

.project {
  background: linear-gradient(10deg, #488cc0, #0d0d0d);
  border-radius: 10px;
  overflow: hidden;
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.6);
  transition: transform 0.3s;
}

.project:hover {
  transform: translateY(-5px);
}

.project img {
  height: 180px;
  margin: 10px;
  float: left;
}

.project-content {
  padding: 1rem;
}

.project-content h3 {
  margin-top: 0;
  color: #db9826;
}

.tags {
  margin-top: 0.5rem;
}

.tag {
  display: inline-block;
  background: linear-gradient(10deg, #22203f, #0d0d0d);
  color: #f0f0f0;
  border-radius: 4px;
  padding: 0.2rem 0.5rem;
  margin: 0.2rem;
  font-size: 0.85rem;
}

footer {
  text-align: center;
  padding: 1.5rem;
  background: #1a1a1a;
  border-top: 2px solid #d4af37;
  font-size: 0.9rem;
  color: #aaa;
}
