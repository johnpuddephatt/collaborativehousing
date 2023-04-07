---
title: 'Our People '
layout: page
subtitle: ''
scripts: ''
---

{% for person in site.data.people.people %}
<div class="person">
  <img class="person--image" src="{{ person.image }}">
  <div class="person--text">
    <h3 class="person--name">{{ person.name }}</h3>
    {{ person.body }}
  </div>
</div>
{% endfor %}