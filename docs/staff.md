---
layout: page
title: Instructors
description: Instructors that can help you for the implementation
nav_order: 5
---


# Scientific instructors

Scientific instructors prepared the technical content hosted on this website. They can guide you through the tutorials and your final project implementation.

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

# Lecturers

{% assign teaching_assistants = site.staffers | where: 'role', 'Teaching Assistant' %}
{% assign num_teaching_assistants = teaching_assistants | size %}

# Organizer

{% if num_teaching_assistants != 0 %}
## Teaching Assistants
{% for staffer in teaching_assistants %}
{{ staffer }}
{% endfor %}
{% endif %}
