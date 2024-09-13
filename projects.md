---
layout: page
title: Projects
permalink: /projects/
---

Here are some project ideas:

### Project 1: Portfolio Website

Built a personal portfolio website using HTML, CSS, and JavaScript.

### Project 2: Machine Learning with Python

Developed a machine learning model to predict customer churn using Python and scikit-learn.

### Project 3: Business Analytics Dashboard

Created a data analytics dashboard using Power BI to analyze and visualize company performance.

## Display

Here are some of those ideas with their own pages:

<ul>
  {% for project in site.projects %}
    <li>
      <h3><a href="{{ project.url }}">{{ project.title }}</a></h3>
      <p>{{ project.description }}</p>
    </li>
  {% endfor %}
</ul>
