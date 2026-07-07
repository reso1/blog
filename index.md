---
layout: default
---

## About Me
I am a Ph.D. candidate in the <a href="https://airob-group.github.io/">AIRob</a> Lab at Simon Fraser University, advised by Professor <a href="https://www2.cs.sfu.ca/~hangma/">Hang Ma</a>.
Previously, I worked at the Shenzhen Institute of Artificial Intelligence and Robotics for Society, advised by Professor <a href="https://www.freeformrobotics.org/tllam/?_gl=1*1la65no*_ga*MTMyNzg5ODg1NC4xNzcxNDgzNTUz*_ga_9Q50NCRYN7*czE3NzE0ODM1NTIkbzEkZzAkdDE3NzE0ODM1NTIkajYwJGwwJGgw">Tin Lun Lam</a>, and studied in the Intelligent Motion Planning and Vision Lab at East China Normal University (ECNU), advised by Professor Xinyu Zhang.
My research centers on multi-robot motion and coverage planning, with a focus on mixed discrete/continuous optimization on Graphs of Convex Sets (GCS) and scalable Multi-Robot Coverage Path Planning (MCPP). I am also interested in deployment-oriented planning for real-world robotic and autonomous building-design systems.
<hr>

## Research
<table class="research-projects">
<tbody>
  {% for project in site.data.projects %}
    {% include research_project.html project=project %}
  {% endfor %}
</tbody>
</table>
