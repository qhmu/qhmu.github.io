---
title: People
nav:
  order: 2
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

We’re an interdisciplinary team of researchers who strive to be rigorous, reproducible, and transparent. Our core values include learning from each other and celebrating the success of others.

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}

{% include section.html background="images/background.jpeg" dark=true %}
