---
layout: archive
title: "Blog Post Series"
permalink: /series/
author_profile: true
---

Explore my blog posts organized into cohesive series:

<div class="series-grid">
  <div class="series-card">
    <h2><a href="/series/alignment-essays/">Alignment Essays</a></h2>
    <p class="series-count">3 posts</p>
    <p>A three-part exploration of AI alignment through the lenses of intelligence, cultural anthropology, and human social systems.</p>
    <div class="series-topics">
      <span class="topic-tag">AI Alignment</span>
      <span class="topic-tag">Philosophy</span>
      <span class="topic-tag">Anthropology</span>
    </div>
    <a href="/series/alignment-essays/" class="series-link">View series →</a>
  </div>

  <div class="series-card">
    <h2><a href="/series/caiac/">Columbia AI Alignment Club</a></h2>
    <p class="series-count">8 weekly posts</p>
    <p>Weekly reflections and notes from the Columbia AI Alignment Club Technical Fellowship, covering key papers in AI safety and alignment research.</p>
    <div class="series-topics">
      <span class="topic-tag">AI Safety</span>
      <span class="topic-tag">Technical</span>
      <span class="topic-tag">Research Notes</span>
    </div>
    <a href="/series/caiac/" class="series-link">View series →</a>
  </div>
</div>

<style>
.series-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 2em;
  margin-top: 2em;
}

.series-card {
  background: #f9f9f9;
  border: 1px solid #e0e0e0;
  border-radius: 8px;
  padding: 1.5em;
  transition: transform 0.2s, box-shadow 0.2s;
}

.series-card:hover {
  transform: translateY(-4px);
  box-shadow: 0 4px 12px rgba(0,0,0,0.1);
}

.series-card h2 {
  margin-top: 0;
  margin-bottom: 0.5em;
}

.series-card h2 a {
  text-decoration: none;
  color: #333;
}

.series-card h2 a:hover {
  color: #4CAF50;
}

.series-count {
  color: #666;
  font-size: 0.9em;
  margin-bottom: 1em;
  font-weight: 600;
}

.series-card > p {
  color: #555;
  line-height: 1.6;
  margin-bottom: 1em;
}

.series-topics {
  margin: 1em 0;
}

.topic-tag {
  display: inline-block;
  background: white;
  border: 1px solid #ddd;
  padding: 0.3em 0.8em;
  margin: 0.2em;
  border-radius: 4px;
  font-size: 0.85em;
  color: #666;
}

.series-link {
  display: inline-block;
  margin-top: 1em;
  color: #4CAF50;
  text-decoration: none;
  font-weight: 600;
}

.series-link:hover {
  text-decoration: underline;
}
</style>
