---
layout: page
title: Source Codes
permalink: /projects/
description: A collection of some source codes.
nav: false
display_categories: [work, fun]
horizontal: false
---

#### InK: Reactive Kernel for Tiny Batteryless Sensors

InK is the first reactive kernel that provides a novel way to program  tiny energy harvesting devices. InK brings an event-driven paradigm shift for batteryless applications, introducing building blocks and abstractions that enable reacting to changes in available energy and variations in sensing data, alongside task scheduling, while maintaining a consistent memory and sense of time.
<br/>

[\[Source Code\]](https://github.com/TUDSSL/InK)

#### sim-it - Simulate it!

A Java language based simulator for the simulation of network protocols for wireless distributed systems.
<br/>

[\[Source Code\]](https://github.com/sinanyil81/sim-it)  

#### PISync - Proportional-Integral Clock Synchronization In Wireless Sensor Networks

A time synchronization protocol developed for Wireless Sensor Networks.   [\[NesC Source Code\]](http://tinyos.stanford.edu/tinyos-wiki/index.php/TinyOS_2.x_index_of_contributed_code#PISync_-_Proportional-Integral_Clock_Synchronization_In_Wireless_Sensor_Networks)  

[A video](https://www.youtube.com/watch?v=AOH-1_eehQ0) 

#### AVTS - Adaptive Value Tracking Time Synchronization Protocol

A time synchronization protocol developed for Wireless Sensor Networks based upon an adaptive search algorithm. In AVTS, each sensor node synchronizes the rate of its clock to that of a reference clock through successive feedbacks, and by adjusting time offset of the rate-synchronized clocks, the network-wide synchronization is established.  
[\[NesC Source Code\]](https://github.com/sinanyil81/avts)  

#### eGIS Embedded Operating System
Developed during master thesis. Many embedded applications need a real-time and embedded operating system that provides an simple operation environment. Embedded operating systems that give service to embedded applications must be configurable and restructurable in contrast to general purpose operating systems. In this work, eGİS (Ege Gömülü İşletim Sistemi) which is a real-time, portable, configurable, object oriented and embedded operating system is implemented.
[\[C Source Code\]](https://github.com/sinanyil81/egis)  

#### Zeugma - Simple and Small 32 Bit Kernel for 80386
Developed during bachelor thesis.
[\[C Source Code\]](https://github.com/sinanyil81/zeugma)


{% comment %}

<!-- pages/projects.md -->
<div class="projects">
{%- if site.enable_project_categories and page.display_categories %}
  <!-- Display categorized projects -->
  {%- for category in page.display_categories %}
  <h2 class="category">{{ category }}</h2>
  {%- assign categorized_projects = site.projects | where: "category", category -%}
  {%- assign sorted_projects = categorized_projects | sort: "importance" %}
  <!-- Generate cards for each project -->
  {% if page.horizontal -%}
  <div class="container">
    <div class="row row-cols-2">
    {%- for project in sorted_projects -%}
      {% include projects_horizontal.html %}
    {%- endfor %}
    </div>
  </div>
  {%- else -%}
  <div class="grid">
    {%- for project in sorted_projects -%}
      {% include projects.html %}
    {%- endfor %}
  </div>
  {%- endif -%}
  {% endfor %}

{%- else -%}
<!-- Display projects without categories -->
  {%- assign sorted_projects = site.projects | sort: "importance" -%}
  <!-- Generate cards for each project -->
  {% if page.horizontal -%}
  <div class="container">
    <div class="row row-cols-2">
    {%- for project in sorted_projects -%}
      {% include projects_horizontal.html %}
    {%- endfor %}
    </div>
  </div>
  {%- else -%}
  <div class="grid">
    {%- for project in sorted_projects -%}
      {% include projects.html %}
    {%- endfor %}
  </div>
  {%- endif -%}
{%- endif -%}
</div>

{% endcomment %}