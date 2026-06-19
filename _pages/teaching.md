---
layout: page
permalink: /teaching/
title: Teaching
description: Teaching and tutoring activities.
nav: true
nav_order: 6
calendar: false
---

{% assign teachings = site.teachings | sort: "date" | reverse %}

{% for item in teachings %}

## {{ item.title }}

**Institution:** {{ item.venue }}  
**Location:** {{ item.location }}  
**Semester:** {{ item.semester }}

{{ item.content }}

---

{% endfor %}
