---
layout: home
title: Hi, I'm Rebecca Wagner. I'm a data scientist based in Washington, D.C.
---

I study social policy like education and housing. Thanks for checking out my page.

Contact me at rlw137@georgetown.edu.

<div style="margin-top:30px;">
  <a href="www.linkedin.com/in/rebeccawagner01" target="_blank"
     style="padding:10px 18px; background-color:#d7b3f2; color:white; border-radius:6px; text-decoration:none; margin-right:8px; font-weight:bold;">
     LinkedIn
  </a>

  <a href="https://github.com/rebeccalwagner" target="_blank"
     style="padding:10px 18px; background-color:#d7b3f2; color:white; border-radius:6px; text-decoration:none; margin-right:8px; font-weight:bold;">
     GitHub
  </a>

  <a href="{{ '/assets/files/placeholder_resume.pdf' | relative_url }}" 
     target="_blank" 
     style="padding:10px 18px; background-color:#d7b3f2; color:white; border-radius:6px; text-decoration:none; font-weight:bold;">
     CV
  </a>
</div>

<nav style="text-align:center; margin: 20px 0;">
  <a href="#about" style="margin:0 10px;">About</a>
  <a href="#projects" style="margin:0 10px;">Projects</a>
  <a href="#contact" style="margin:0 10px;">Contact</a>
</nav>

<style>
html { scroll-behavior: smooth; }
section { padding: 50px 0; border-bottom: 1px solid #eee; }
</style>

<section id="about">
  {% include about.html %}
</section>

<section id="projects">
  {% include projects.html %}
</section>
