---
layout: home
---
<!-- ================= HEADER ================= -->
<header>
  <h1>Rebecca Wagner</h1>
  <nav>
    <a href="#about">About</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<!-- ================= LANDING ================= -->
<section id="hello">
  <h1>Hi, I'm <span>Rebecca Wagner</span></h1>
  <h2>Data Scientist in Washington, D.C.</h2>
  <p>
    I explore data to understand how education, housing, and policy decisions shape our communities.
  </p>
</section>

<!-- ================= PROJECTS ================= -->
<section id="projects">
  <h2>Projects</h2>
  {% include projects.html %}
</section>

<!-- ================= CONTACT ================= -->
<section id="contact">
  <h2>Contact</h2>
  <p>
    Feel free to reach out!<br>
    <a href="mailto:rlw137@georgetown.edu">rlw137@georgetown.edu</a>
  </p>
</section>

<!-- ================= STYLES ================= -->
<style>
  html {
    scroll-behavior: smooth;
  }

  .site-header {
  display: none !important;
  }

  .page-content {
  max-width: none !important;
  width: 100% !important;
  padding: 0 !important;
  }

  body {
    margin: 0;
    font-family: system-ui, -apple-system, sans-serif;
    color: #222;
    background-color: #fff;
  }

  /* Header */
  header {
    position: sticky;
    top: 0;
    background: white;
    border-bottom: 1px solid #eee;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 1rem 2rem;
    z-index: 999;
  }

  header h1 {
    margin: 0;
    font-size: 1.1rem;
    font-weight: 600;
  }

  nav a {
    margin-left: 1.5rem;
    text-decoration: none;
    color: #0366d6;
    font-weight: 600;
  }

  nav a:hover {
    text-decoration: underline;
  }

  /* Sections */
  main, section {
    padding: 80px 2rem;
    max-width: 800px;
    margin: 0 auto;
  }

  section h2 {
    font-size: 1.5rem;
    border-bottom: 2px solid #0366d6;
    display: inline-block;
    margin-bottom: 1rem;
  }

  section p {
    line-height: 1.6;
    font-size: 1rem;
  }

  /* Responsive tweaks */
  @media (max-width: 600px) {
    header {
      flex-direction: column;
      align-items: flex-start;
    }
    nav a {
      margin: 0 0.75rem 0.5rem 0;
    }
    section {
      padding: 60px 1rem;
    }
  }
</style>
