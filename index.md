---
layout: home
title: Home
---
<div class="hero-section">
  <div class="profile-container">
    <img src="{{ '/assets/images/profile.png' | relative_url }}" alt="J. Adrian Hernandez" class="profile-image">
  </div>
  <h1>J. Adrian Hernandez</h1>
</div>

<div class="intro-section">
  <p>Hey there, I'm Adrian. I enjoy building things with code. Whether it's crafting web applications or creating games, I enjoy the whole process of bringing ideas to life. In my free time, you can find me reading, playing video/tabletop games, or watching movies.</p>
  
  <div class="cta-buttons">
    <a href="{{ '/blog' | relative_url }}" class="cta-link">Read My Blog</a>
    <a href="{{ '/projects' | relative_url }}" class="cta-link">View My Projects</a>
  </div>
</div>

<div class="featured-projects">
  <h2>Some of my Projects</h2>
  <div class="project-preview">
    <a href="{{ '/projects' | relative_url }}" class="project-card">
      <h3>Taskify</h3>
      <p>Task management application with Spring Boot & Angular</p>
    </a>
    <a href="{{ '/projects' | relative_url }}" class="project-card">
      <h3>Dodge</h3>
      <p>A fast-paced browser game where you dodge enemies and collect gems using Three.js</p>
    </a>
  </div>
</div>

<div class="latest-posts">
  <h2>Latest Posts</h2>
  <div class="post-preview-container">
    {% for post in site.posts limit:2 %}
    <a href="{{ post.url }}" class="post-card">
      <h3>{{ post.title }}</h3>
      <time>{{ post.date | date_to_string }}</time>
      <p>{{ post.excerpt | strip_html | truncatewords: 30 }}</p>
    </a>
    {% endfor %}
  </div>
</div>
