---
permalink: /trainees.html
layout: default
title: TAC-HEP Traineeship Program
---

# TAC-HEP Traineeship Program

{% assign today = site.time | date: "%Y-%m-%d" %}

{% assign current_trainees = site.trainees | where_exp: "item", "item.end_date == '' or item.end_date > today" | sort: "name" %}
{% assign former_trainees = site.trainees | where_exp: "item", "item.end_date != '' and item.end_date <= today" | sort: "name" %}

<h1>Current TAC-HEP Trainees</h1><br>

<div class="container-fluid">
  <div class="row">
    {% for person in current_trainees %}
      {% include standard_person_card.md person=person %}
    {% endfor %}
  </div>
</div>

<h1>Former TAC-HEP Trainees</h1><br>

<div class="container-fluid">
  <div class="row">
    {% for person in former_trainees %}
      {% include standard_person_card.md person=person %}
    {% endfor %}
  </div>
</div>
