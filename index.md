---
layout: home
title: Home
---
<div class="hero-section">
  <div class="profile-container">
    <img src="{{ '/assets/images/profile.png' | relative_url }}" alt="J. Adrian Hernandez" class="profile-image">
  </div>
  <h1>J. Adrian Hernandez</h1>
  <p class="tagline">Software Engineer & Game Developer</p>
</div>

<div class="intro-section">
  <p>Hi! I'm Adrian, a software engineer passionate about creating elegant solutions and engaging games. With expertise in full-stack development and game programming, I love bringing ideas to life through code.</p>
  
  <div class="cta-buttons">
    <a href="{{ '/blog' | relative_url }}" class="cta-link">Read My Blog</a>
    <a href="{{ '/projects' | relative_url }}" class="cta-link">View My Projects</a>
  </div>
</div>

<div class="featured-projects">
  <h2>Featured Projects</h2>
  <div class="project-preview">
    <a href="{{ '/projects' | relative_url }}" class="project-card">
      <h3>Taskify</h3>
      <p>Task management application with Spring Boot & Angular</p>
    </a>
    <a href="{{ '/projects' | relative_url }}" class="project-card">
      <h3>Elude</h3>
      <p>2D game with intelligent AI pathfinding</p>
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
