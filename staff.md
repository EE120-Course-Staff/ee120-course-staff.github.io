---
layout: page
title: Staff
nav_order: 3
description: A listing of all the course staff members.
---

# Staff

## Instructors

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

{% assign head_tas = site.staffers | where: 'role', 'Head TA' %}
{% assign num_teaching_assistants = head_tas | size %}

{% if num_teaching_assistants != 0 %}
## Teaching Assistants

{% for staffer in head_tas %}
{{ staffer }}
{% endfor %}
{% endif %}

<!-- ## UCS2s -->

{% assign teaching_assistants = site.staffers | where: 'role', 'TA' %}
{% assign num_teaching_assistants = teaching_assistants | size %}
{% if num_teaching_assistants != 0 %}

{% for staffer in teaching_assistants %}
{{ staffer }}
{% endfor %}
{% endif %}

{% assign ucs1s = site.staffers | where: 'role', 'UCS1' %}
{% assign num_ucs1s = ucs1s | size %}
{% if num_readers != 0 %}
## UCS1s

{% for staffer in ucs1s %}
{{ staffer }}
{% endfor %}
{% endif %}
