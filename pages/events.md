---
permalink: /events.html
layout: default
title: TAC-HEP Events
---
<center>
<h3> TAC-HEP Events</h3>
</center>

<br>
Events that TAC-HEP team is organizing

{% assign yearlist = "2027, 2026, 2025, 2024, 2023, 2022, 2021, 2020, 2019, 2018, 2017, 2016" | split: ", " %}
{% assign monthlist= "12, 11, 10, 09, 08, 07, 06, 05, 04, 03, 02, 01" | split: ", " %}

{% comment %}
Go through the list and produce a breakdown of the events in reverse
chronological order, grouped by months
{% endcomment %}

{%- include get_all_events.html -%}

{% assign grouping = all_events | group_by_exp: "item", "item.startdate | date: '%B, %Y'"%}

{% for pair in grouping %}
  <h5>{{ pair.name }}</h5>
  <ul>
    {% for event in pair.items %}
      <li> {{event.startdate | date: "%-d %b" }}{{event.enddate | date: " - %-d %b" }}, {{event.startdate | date: "%Y" }} - <a href="{{ site.baseurl }}{{event.meetingurl}}">{{event.name}}</a> (<i>{{event.location}}</i>)
      {% if event.abstractdeadline != nil %}
        {% assign abs_date = event.abstractdeadline | date_to_long_string %}
        (Abstract deadline: {{abs_date}})
      {% endif %}
      </li>
    {% endfor %}
  </ul>
{% endfor %}

