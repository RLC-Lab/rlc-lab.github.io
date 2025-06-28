---
title: "Team"
permalink: /team/
author_profile: true
---

# RLC-Lab Team

## Principal Investigator

{% assign author = site.data.authors.Yiming_Gan %}
<div class="team-member">
  <div class="member-avatar">
    {% if author.avatar contains "://" %}
      <img src="{{ author.avatar }}" alt="{{ author.name }}">
    {% else %}
      <img src="{{ author.avatar | prepend: '/images/' | prepend: base_path }}" alt="{{ author.name }}">
    {% endif %}
  </div>
  <div class="member-info">
    <h3>{{ author.name }}</h3>
    <p class="member-title">Principal Investigator</p>
    <p class="member-bio">{{ author.bio }}</p>
    <div class="member-links">
      {% if author.email %}
        <a href="mailto:{{ author.email }}"><i class="fas fa-envelope"></i> Email</a>
      {% endif %}
      {% if author.uri %}
        <a href="{{ author.uri }}"><i class="fas fa-link"></i> Website</a>
      {% endif %}
      {% if author.googlescholar %}
        <a href="{{ author.googlescholar }}"><i class="ai ai-google-scholar"></i> Google Scholar</a>
      {% endif %}
      {% if author.github %}
        <a href="https://github.com/{{ author.github }}"><i class="fab fa-github"></i> GitHub</a>
      {% endif %}
    </div>
  </div>
</div>

## Current Members

### PhD Students

{% assign author = site.data.authors.Guoshuai_Geng %}
<div class="team-member">
  <div class="member-avatar">
    {% if author.avatar contains "://" %}
      <img src="{{ author.avatar }}" alt="{{ author.name }}">
    {% else %}
      <img src="{{ author.avatar | prepend: '/images/' | prepend: base_path }}" alt="{{ author.name }}">
    {% endif %}
  </div>
  <div class="member-info">
    <h3>{{ author.name }}</h3>
    <p class="member-title">PhD Student</p>
    <p class="member-bio">{{ author.bio }}</p>
    <div class="member-links">
      {% if author.email %}
        <a href="mailto:{{ author.email }}"><i class="fas fa-envelope"></i> Email</a>
      {% endif %}
    </div>
  </div>
</div>

{% assign author = site.data.authors.Yuhui_Hao %}
<div class="team-member">
  <div class="member-avatar">
    {% if author.avatar contains "://" %}
      <img src="{{ author.avatar }}" alt="{{ author.name }}">
    {% else %}
      <img src="{{ author.avatar | prepend: '/images/' | prepend: base_path }}" alt="{{ author.name }}">
    {% endif %}
  </div>
  <div class="member-info">
    <h3>{{ author.name }}</h3>
    <p class="member-title">PhD Student</p>
    <p class="member-bio">{{ author.bio }}</p>
    <div class="member-links">
      {% if author.email %}
        <a href="mailto:{{ author.email }}"><i class="fas fa-envelope"></i> Email</a>
      {% endif %}
    </div>
  </div>
</div>

### Master Students

{% assign author = site.data.authors.Kai_Pan %}
<div class="team-member">
  <div class="member-avatar">
    {% if author.avatar contains "://" %}
      <img src="{{ author.avatar }}" alt="{{ author.name }}">
    {% else %}
      <img src="{{ author.avatar | prepend: '/images/' | prepend: base_path }}" alt="{{ author.name }}">
    {% endif %}
  </div>
  <div class="member-info">
    <h3>{{ author.name }}</h3>
    <p class="member-title">Master Student</p>
    <p class="member-bio">{{ author.bio }}</p>
    <div class="member-links">
      {% if author.email %}
        <a href="mailto:{{ author.email }}"><i class="fas fa-envelope"></i> Email</a>
      {% endif %}
    </div>
  </div>
</div>

{% assign author = site.data.authors.Xinquan_Lin %}
<div class="team-member">
  <div class="member-avatar">
    {% if author.avatar contains "://" %}
      <img src="{{ author.avatar }}" alt="{{ author.name }}">
    {% else %}
      <img src="{{ author.avatar | prepend: '/images/' | prepend: base_path }}" alt="{{ author.name }}">
    {% endif %}
  </div>
  <div class="member-info">
    <h3>{{ author.name }}</h3>
    <p class="member-title">Master Student</p>
    <p class="member-bio">{{ author.bio }}</p>
    <div class="member-links">
      {% if author.email %}
        <a href="mailto:{{ author.email }}"><i class="fas fa-envelope"></i> Email</a>
      {% endif %}
    </div>
  </div>
</div>

{% assign author = site.data.authors.Wenhao_Sun %}
<div class="team-member">
  <div class="member-avatar">
    {% if author.avatar contains "://" %}
      <img src="{{ author.avatar }}" alt="{{ author.name }}">
    {% else %}
      <img src="{{ author.avatar | prepend: '/images/' | prepend: base_path }}" alt="{{ author.name }}">
    {% endif %}
  </div>
  <div class="member-info">
    <h3>{{ author.name }}</h3>
    <p class="member-title">Master Student</p>
    <p class="member-bio">{{ author.bio }}</p>
    <div class="member-links">
      {% if author.email %}
        <a href="mailto:{{ author.email }}"><i class="fas fa-envelope"></i> Email</a>
      {% endif %}
    </div>
  </div>
</div>

{% assign author = site.data.authors.Yiyang_Huang %}
<div class="team-member">
  <div class="member-avatar">
    {% if author.avatar contains "://" %}
      <img src="{{ author.avatar }}" alt="{{ author.name }}">
    {% else %}
      <img src="{{ author.avatar | prepend: '/images/' | prepend: base_path }}" alt="{{ author.name }}">
    {% endif %}
  </div>
  <div class="member-info">
    <h3>{{ author.name }}</h3>
    <p class="member-title">Master Student</p>
    <p class="member-bio">{{ author.bio }}</p>
    <div class="member-links">
      {% if author.email %}
        <a href="mailto:{{ author.email }}"><i class="fas fa-envelope"></i> Email</a>
      {% endif %}
    </div>
  </div>
</div>

{% assign author = site.data.authors.Zixuan_Wang %}
<div class="team-member">
  <div class="member-avatar">
    {% if author.avatar contains "://" %}
      <img src="{{ author.avatar }}" alt="{{ author.name }}">
    {% else %}
      <img src="{{ author.avatar | prepend: '/images/' | prepend: base_path }}" alt="{{ author.name }}">
    {% endif %}
  </div>
  <div class="member-info">
    <h3>{{ author.name }}</h3>
    <p class="member-title">Master Student</p>
    <p class="member-bio">{{ author.bio }}</p>
    <div class="member-links">
      {% if author.email %}
        <a href="mailto:{{ author.email }}"><i class="fas fa-envelope"></i> Email</a>
      {% endif %}
    </div>
  </div>
</div>

## Alumni

{% assign author = site.data.authors.Sai_Hou %}
<div class="team-member">
  <div class="member-avatar">
    {% if author.avatar contains "://" %}
      <img src="{{ author.avatar }}" alt="{{ author.name }}">
    {% else %}
      <img src="{{ author.avatar | prepend: '/images/' | prepend: base_path }}" alt="{{ author.name }}">
    {% endif %}
  </div>
  <div class="member-info">
    <h3>{{ author.name }}</h3>
    <p class="member-title">Alumni</p>
    <p class="member-bio">{{ author.bio }}</p>
    <div class="member-links">
      {% if author.email %}
        <a href="mailto:{{ author.email }}"><i class="fas fa-envelope"></i> Email</a>
      {% endif %}
    </div>
  </div>
</div>

## Join Us

We are always looking for talented and motivated students and researchers to join our lab. If you are interested in robotic computing, chip design, or autonomous systems, please feel free to contact us.

**Current Openings:**
- PhD positions in Computer Architecture and Robotics
- Master positions in Embedded Systems and AI
- Research internships for undergraduate students

For more information about joining our lab, please contact [Dr. Yiming Gan](mailto:ganyiming@ict.ac.cn). 