---
layout: default
title: "Kartik Patel Portfolio"
---
<div class="page-header">
  <div class="social-links">
    <a href="https://www.linkedin.com/in/demoralizer/" target="_blank">LinkedIn</a>
    <a href="https://leetcode.com/u/demoralizerr" target="_blank">LeetCode</a>
    <a href="https://github.com/demoralizerr" target="_blank">GitHub</a>
    <a href="mailto:meetkartik40@example.com">meetkartik40@gmail.com</a>
  </div>
</div>

# Welcome to Kartik Patel Portfolio

<div class="portfolio-tabs">

  <a href="/DSA/" class="tab-card">
    <h2>DSA</h2>
    <p>Explore algorithm and data structure problems, resources, and practice questions.</p>
  </a>

  <a href="/SystemDesign/" class="tab-card">
    <h2>System Design</h2>
    <p>Learn system design concepts, patterns, and interview preparation notes.</p>
  </a>

</div>

<style>
.portfolio-tabs {
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
  margin-top: 20px;
}
.page-header {
  display: flex;
  justify-content: flex-end; /* moves to right */
  padding: 10px 30px;
  position: sticky; /* sticks on top when scrolling */
  top: 0;
  background: #f8fafc; /* match Cayman theme bg */
  z-index: 100;
  border-bottom: 1px solid #cbd5e1;
}

.social-links a {
  text-decoration: none;
  color: #2563eb;
  margin-left: 15px;
  font-weight: 500;
  transition: color 0.2s;
}

.social-links a:hover {
  color: #020617;
}  

.tab-card {
  flex: 1 1 250px;
  background: #f1f5f9;
  border: 1px solid #cbd5e1;
  border-radius: 10px;
  padding: 20px;
  text-align: center;
  text-decoration: none;
  color: #1f2937;
  transition: transform 0.2s, box-shadow 0.2s;
}

.tab-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 5px 15px rgba(0,0,0,0.2);
  color: #2563eb;
}

.tab-card h2 {
  margin-top: 0;
  margin-bottom: 10px;
}

.tab-card p {
  margin: 0;
  font-size: 14px;
}
</style>
