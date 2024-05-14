---
title: People
nav:
  order: 2
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

We’re a computational biology laboratory working on human cancer. We aim to make computational tools and biomedical discoveries that are helpful for the patients, doctors, and researchers. As an interdisciplinary team, our core values include learning from each other and celebrating the success of others.

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}

{% include section.html background="images/background.jpeg" dark=true %}
