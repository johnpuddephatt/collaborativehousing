---
layout: page
title: 'Our People '
subtitle: 'Staff and steering group '
scripts: ''
---

{% for person in site.data.people.people %}
<div class="person">
  <img src="{{ person--image }}">
  <div class="person--text">
    <h3 class="person--name">{{ person.name }}</h3>
    <p class="person--title">{{ person.title }}</p>
    {{ person.body }}
  </div>
{% endfor %}