---
layout: page
title: 'Our People '
subtitle: 'Staff and steering group '
scripts: ''
---

{% for person in site.data.people.people %}
  {{ person.name }}
{% endfor %}