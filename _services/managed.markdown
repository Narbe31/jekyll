---
title: Managed
date: 2019-02-14 14:16:00 Z
collectionKey: Collection value
numbers:
- un
- deux
- trois
- quatre
obj:
  firstName: Maxence
  lastName: BESNARD
  image: "/uploads/capgemini-logo.jpg"
  isFeatured: true
---

# Provisioning packages

## Titre 2

Content ..
..
..

Contact us

KEY : {{ page.collectionKey }}

{% for number in page.numbers %}

    number : {{ number }}

{% endfor %}

Object :

{{ page.obj.firstName }} {{ page.obj.lastName }}\
<img src="{{ page.obj.image }}" />\
{{ page.obj.isFeatured }}