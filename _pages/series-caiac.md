---
layout: archive
title: "Columbia AI Alignment Club (CAIAC) Reading Notes"
permalink: /series/caiac/
author_profile: true
---

<div class="series-intro">
  <p>Weekly reflections and notes from the Columbia AI Alignment Club Technical Fellowship, covering key papers in AI safety, alignment, interpretability, control, and evaluation.</p>
</div>

{% assign series_posts = site.posts | where: "series", "caiac" | sort: "series_order" %}

<div class="series-list">
  {% for post in series_posts %}
    <div class="series-item">
      <h2><a href="{{ post.url }}">Week {{ post.series_order }}: {{ post.title | replace: 'CAIAC Papers Week ' | append: post.series_order | replace: post.series_order, '' }}</a></h2>
      <p class="post-meta">{{ post.date | date: "%B %d, %Y" }}</p>
      {% assign post_tags = post.tags | join: ", " %}
      <p class="post-tags"><strong>Topics:</strong> {{ post_tags }}</p>
      <a href="{{ post.url }}" class="read-more">Read notes →</a>
    </div>
  {% endfor %}
</div>

<style>
.series-intro {
  background: #f5f5f5;
  padding: 1.5em;
  border-left: 4px solid #2196F3;
  margin-bottom: 2em;
}

.series-list {
  margin-top: 2em;
}

.series-item {
  margin-bottom: 2.5em;
  padding-bottom: 2em;
  border-bottom: 1px solid #e0e0e0;
}

.series-item:last-child {
  border-bottom: none;
}

.series-item h2 {
  margin-bottom: 0.5em;
}

.series-item h2 a {
  text-decoration: none;
  color: #333;
}

.series-item h2 a:hover {
  color: #2196F3;
}

.post-meta {
  color: #666;
  font-size: 0.9em;
  margin-bottom: 0.3em;
}

.post-tags {
  color: #666;
  font-size: 0.9em;
  margin-bottom: 0.8em;
}

.read-more {
  color: #2196F3;
  text-decoration: none;
  font-weight: 500;
}

.read-more:hover {
  text-decoration: underline;
}
</style>
