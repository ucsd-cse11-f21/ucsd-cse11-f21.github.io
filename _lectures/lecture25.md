---
layout: with-sidebar
index: 25
name: Class Hierarchy
released-on: "2021-11-19"
videos:
    - title: "Exceptions in Constructors"
      url: https://drive.google.com/file/d/18cK8aOJ5u2shclhOltpPwUoELer3vHgI
    - title: "Abstract Classes (31:00 to end)"
      url: https://drive.google.com/file/d/1p5wapPyh34kEMqNKxNZKH_RqSoFeV70m
    - title: "Abstract Classes 2 (First 2:00 - 20:00)"
      url: https://drive.google.com/file/d/1Xp7owWbOOTB4ubOQgiwyI-En6ubOiDzN
worksheets:
  - title: 2PM Discussion
    url: https://drive.google.com/file/d/1assLXGNd-DmR9toODYrE1ty12ghy1Gtq
  - title: 4PM Lecture
    url: https://drive.google.com/file/d/18WM17sRrgrt-O9fv_7sL95YMDOSypQ_F
  - title: 10AM & 2PM Lecture
    url: https://drive.google.com/file/d/1pgJMqvBEGCt-bVOKJeOK3ZoMzlLXjful
---


## Problem Session {{ page.index }} – {{ page.name }}

_{{ page.released-on }}_

Participation: [https://docs.google.com/forms/d/e/1FAIpQLSdjm5t_H911vAxxC_oJ5gtuZ95WABaaLPhckbuLHz2CbUzmbQ/viewform](https://docs.google.com/forms/d/e/1FAIpQLSdjm5t_H911vAxxC_oJ5gtuZ95WABaaLPhckbuLHz2CbUzmbQ/viewform)

## Pre-class Tasks

Stepik 12.2 (finish if you didn't for Wednesday): [https://stepik.org/lesson/578016/step/1?unit=572623](https://stepik.org/lesson/578016/step/1?unit=572623)

Videos:

{% for video in page.videos %}
[{{ video.title }}]({{ video.url }}){:target="_blank"}
<iframe src="{{ video.url }}/preview" width="640" height="480" allow="autoplay"></iframe>
{% endfor %}

## Handout

<iframe src="https://drive.google.com/file/d/1VFG7LCaqwV1Z8i9McN--0YlleUak4Km2/preview" width="640" height="480" allow="autoplay"></iframe>

## Completed Worksheets from Dicussion and Lecture

{% for worksheet in page.worksheets %}
<div class="worksheetBox">
{{ worksheet.title }}
<br>
<iframe src="{{ worksheet.url }}/preview" width="256" height="192" allow="autoplay"></iframe>
</div>
{% endfor %}
