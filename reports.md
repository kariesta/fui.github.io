---
layout: page
title: Referater
permalink: /reports
modeline: " vim: set spl=nb: "
---

# Referater

---

Alle referater fra før 2019 finner du [her](http://fui.ifi.uio.no/referater/).

{% for report in reports %}
  <h2>{{ report.name }} - {{ report.type }}</h2>
  <p>{{ report.content | markdownify }}</p>
{% endfor %}