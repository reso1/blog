---
layout: default
---

## About Me
I am a Ph.D. candidate in the <a href="https://airob-group.github.io/">AIRob</a> Lab at Simon Fraser University, advised by Professor <a href="https://www2.cs.sfu.ca/~hangma/">Hang Ma</a>. I develop structure-exploiting AI planning methods, combining heuristic search, combinatorial optimization, and Graphs of Convex Sets (GCS). My work applies these methods to multi-robot systems and automated engineering design. I am also interested in automated planning applications in transportation, manufacturing, and construction. My earlier research at the Shenzhen Institute of Artificial Intelligence and Robotics for Society and East China Normal University was advised by Professors <a href="https://www.freeformrobotics.org/tllam/">Tin Lun Lam</a> and <a href="https://faculty.ecnu.edu.cn/_s43/zxy2/main.psp">Xinyu Zhang</a>.
<hr>

## Research
<table class="research-projects">
<tbody>
  {% for project in site.data.projects %}
    {% include research_project.html project=project %}
  {% endfor %}
</tbody>
</table>
