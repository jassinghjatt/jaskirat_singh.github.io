---
layout: page
permalink: /teaching/
title: Teaching
description: Teaching and tutoring activities.
nav: true
nav_order: 6
calendar: false
---

<div class="row">

{% assign teachings = site.teachings | sort: "date" | reverse %}

{% for item in teachings %}

<div class="col-sm-12 mb-4">
  <div class="card">
    <div class="card-body">

      <h3>{{ item.title }}</h3>

      <p>
        <strong>Institution:</strong> {{ item.venue }}<br>
        <strong>Location:</strong> {{ item.location }}<br>
        <strong>Semester:</strong> {{ item.semester }}
      </p>

      {{ item.content }}

    </div>
  </div>
</div>

{% endfor %}

</div>
