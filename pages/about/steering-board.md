---
permalink: /about/steering-board.html
layout: default
title: Steering Board
---

<div class="container-fluid">
  <h1>Steering Board</h1><br>
  
  <p><b>The IRIS-HEP Steering Board represents the Institute’s stakeholders to 
        provide, to the Executive Board, the stakeholder’s input on the 
        priorities, execution, and strategy of the Institute.</b></p>
  <div class="row">
  {% for member in site.data.orgs.steering-board.personnel  %}
       {% assign person = site.data.people[member] %}
       {% include standard_person_card.md %}
  {% endfor %}
  </div>
  <br>

  <h2>Meetings</h2>

Meetings of the Steering Board take place approximately quarterly. Agendas,
presentation material and the minutes for each meeting can be found in the 
<a href="https://indico.cern.ch/category/10989/">IRIS-HEP Steering Board Area in Indico</a>. 
  
</div>
