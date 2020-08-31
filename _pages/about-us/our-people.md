---
layout: page
title: 'Our People '
subtitle: 'Staff and steering group '
scripts: ''
---

{% for person in site.data.people %}
  {{ person.name }}
{% endfor %}