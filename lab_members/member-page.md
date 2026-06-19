---
layout: default
title: Lab Members
---

<h1>{{ page.title }}</h1>

<!-- Faculty -->
<h2 class="member-subheader">Principal Investigator</h2>
<div class="members-list">
  {% for member in site.data.member_data %}
    {% if member.role == "Principal Investigator" %}
    <div class="member-card">
      <img src="{{ '/assets/images/' | append: member.image | relative_url }}" alt="{{ member.name }}" />
      <div class="member-info">
        <h3>{{ member.name }}</h3>
        <p><strong>Position:</strong> {{ member.position }}</p>
        <p><strong>Address:</strong> QR822, The Hong Kong Polytechnic University, Hung Hom, Kowloon, Hong Kong, China</p>
        <p><strong>Publications:</strong> <a href="https://scholar.google.com/citations?user=fEbEiLoAAAAJ&hl=en" target="_blank">Google Scholar</a></p>
        <p><strong>Email:</strong> <a href="mailto:{{ member.email }}">{{ member.email }}</a></p>
      </div>
    </div>
    {% endif %}
  {% endfor %}
</div>

<!-- Postgraduate Students -->
<h2 class="member-subheader">Postgraduate Students</h2>
<div class="members-list">
  {% for member in site.data.member_data %}
    {% if member.role == "postgraduate" %}
    <div class="member-card">
      <img src="{{ '/assets/images/' | append: member.image | relative_url }}" alt="{{ member.name }}" />
      <div class="member-info">
        <h3>{{ member.name }}</h3>
        <p><strong>Position:</strong> {{ member.position }}</p>
        <p><strong>Expertise:</strong> {{ member.expertise }}</p>
      </div>
    </div>
    {% endif %}
  {% endfor %}
</div>

<!-- Undergraduate Students -->
<h2 class="member-subheader">Undergraduate Students</h2>
<div class="members-list">
  {% for member in site.data.member_data %}
    {% if member.role == "undergraduate" %}
    <div class="member-card">
      <img src="{{ '/assets/images/' | append: member.image | relative_url }}" alt="{{ member.name }}" />
      <div class="member-info">
        <h3>{{ member.name }}</h3>
        <p><strong>Position:</strong> {{ member.position }}</p>
        <p><strong>Expertise:</strong> {{ member.expertise }}</p>
      </div>
    </div>
    {% endif %}
  {% endfor %}
</div>

<!-- Visiting Scholars -->
<h2 class="member-subheader">Visiting Scholars</h2>
<div class="members-list">
  {% for member in site.data.member_data %}
    {% if member.role == "visiting" %}
    <div class="member-card">
      <img src="{{ '/assets/images/' | append: member.image | relative_url }}" alt="{{ member.name }}" />
      <div class="member-info">
        <h3>{{ member.name }}</h3>
        <p><strong>Position:</strong> {{ member.position }}</p>
        <p><strong>Expertise:</strong> {{ member.expertise }}</p>
      </div>
    </div>
    {% endif %}
  {% endfor %}
</div>

<!-- Alumni -->
<h2 class="member-subheader">Alumni</h2>
<div class="members-list">
  {% for member in site.data.member_data %}
    {% if member.role == "alumni" %}
    <div class="member-card">
      <img src="{{ '/assets/images/' | append: member.image | relative_url }}" alt="{{ member.name }}" />
      <div class="member-info">
        <h3>{{ member.name }}</h3>
        <p><strong>Research Period:</strong> {{ member.period }}</p>
        <p><strong>Expertise:</strong> {{ member.expertise }}</p>
      </div>
    </div>
    {% endif %}
  {% endfor %}
</div>