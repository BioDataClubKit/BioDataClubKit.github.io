---
title: Lessons
layout: single
---

Here are past topics and lessons from BioData Club. If you want us to do another workshop, please let us know!

{% assign sorted_events = site.events | sort: 'date' | reverse %}

<div>

{% for event in sorted_events %} 
      {% include events2.html %}
{% endfor %}
