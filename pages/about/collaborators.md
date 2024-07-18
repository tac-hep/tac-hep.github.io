---
permalink: /about/collaborators.html
layout: people
title: TAC-HEP Collaborators
---


{% assign members = site.collaborators | where_exp:"item", "item.active and item.hidden != true"
                                     | last_name_sort: "name" %}
{% assign former_members = site.collaborators | where_exp: "item", "item.active == nil or item.active == false and item.hidden != true"
                                  | last_name_sort: "name" %}

<h1>TAC-HEP University Collaborators</h1><br>

<div class="container-fluid">
<div class="row">
{% for person in members %}
  {% assign institute = site.institutes | find: "shortname", person.institutionkey %}
    {% if institute.category == "university" %}
    {% include standard_person_card.md person=person %}
    {% endif %}
{% endfor %}
</div>
</div>

<h1>TAC-HEP DOE Laboratory Collaborators</h1><br>

<div class="container-fluid">
<div class="row">
{% for person in members %}
  {% assign institute = site.institutes | find: "shortname", person.institutionkey %}
    {% if institute.category == "lab" %}
    {% include standard_person_card.md person=person %}
    {% endif %}
{% endfor %}
</div>
</div>



<h1>TAC-HEP Industry Collaborators</h1><br>

<div class="container-fluid">
<div class="row">
{% for person in members %}
  {% assign institute = site.institutes | find: "shortname", person.institutionkey %}
    {% if institute.category == "industry" %}
    {% include standard_person_card.md person=person %}
    {% endif %}
{% endfor %}
</div>
</div>


