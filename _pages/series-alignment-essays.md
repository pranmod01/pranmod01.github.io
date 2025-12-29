---
layout: archive
title: "Alignment Essays Series"
permalink: /series/alignment-essays/
author_profile: true
---

<div class="series-intro">
  <p>A three-part exploration of AI alignment through the lenses of intelligence, cultural anthropology, and human social systems.</p>
</div>

{% assign series_posts = site.posts | where: "series", "alignment-essays" | sort: "series_order" %}

<div class="series-list">
  {% for post in series_posts %}
    <div class="series-item">
      <h2><a href="{{ post.url }}">Part {{ post.series_order }}: {{ post.title }}</a></h2>
      <p class="post-meta">{{ post.date | date: "%B %d, %Y" }}</p>
      <p>{{ post.excerpt | strip_html | truncatewords: 40 }}</p>
      <a href="{{ post.url }}" class="read-more">Read more →</a>
    </div>
  {% endfor %}
</div>

<style>
.series-intro {
  background: #f5f5f5;
  padding: 1.5em;
  border-left: 4px solid #4CAF50;
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
  color: #4CAF50;
}

.post-meta {
  color: #666;
  font-size: 0.9em;
  margin-bottom: 0.5em;
}

.read-more {
  color: #4CAF50;
  text-decoration: none;
  font-weight: 500;
}

.read-more:hover {
  text-decoration: underline;
}
</style>
