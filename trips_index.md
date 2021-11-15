---
layout: default
title: "All trips"
---

Дела молодости: [сайт биокласса](https://bioclass.ru/?d=117), [сайт южных практик](http://ashipunov.info/vesna/)

{% for trip in site.trips %}
###### [{{ trip.title }}]({{ trip.url }})
{% endfor %}
