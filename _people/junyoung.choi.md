---
layout: people
background: /assets/images/kaist.jpg
title: Junyoung Choi (최준영)
---

{%- assign person_id = "junyoung.choi" %}
{%- assign person = site.data.people | where:"id",person_id | sample %}

<img align="right" style="width: 30%; padding-left: 3%;" src="{{ site.baseurl }}/assets/images/people/jungin.rhee.jpg" alt="{{ person.name }}">

I am a **Undergraduate Student at KAIST [School of Computing](https://cs.kaist.ac.kr)**.


{% include person_contact.md person_id=person_id %}


{% include person_education.md person_id=person_id %}
