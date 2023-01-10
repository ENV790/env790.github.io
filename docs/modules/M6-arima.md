---
title: "M6 - Behind-the-Meter (BTM) Energy Management Systems: PV + battery"
layout: single
permalink: /docs/modules/M6d/
sidebar:
 nav: modules
---

## Learning Objectives

In this module we will talk about distributed energy resources with focus on electrical energy storage (EES). The learning outcomes of this module are:

* Learn how to manage a system with PV + storage;
* More on linear programming (LP);
* More on how to solve LP models in Python using PYOMO library (or R using lpsolve).

## Slides

Here is a <a href="/docs/modules/PPTS/PSE_M6_DER_StorageManagement.pdf" > link </a> to the slide deck used in class.


## Recordings
  <ul>
  {% for row in site.data.Recordings %}
  {% if row.M == "M1" %}
  <li> <a href="{{ row.link }}" target="_blank">{{ row.Task }}</a></li>
  {% endif %}
  {% endfor %}
  </ul>


## Resources

And here is a similar version of the model but incorporating uncertainty, i.e., a stochastic version of the model we explored.

* <a href="/docs/modules/readings/M6_PVStorage_Stochastic.pdf" > Stochastic PV + Storage </a>


## Topics for Discussion/Reflection



## Deliverables

For this module you will complete [Assignment 3](https://sakai.duke.edu/portal/site/fc198b90-9d77-4c6b-8708-c9d0d044be5b/tool/bf736605-42a0-41a8-987a-754e3066d785?panel=Main). The due date for A3 is Friday Oct 21st.
