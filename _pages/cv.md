---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D in Computer Science, University of Maryland College Park, 2025
* M.S. in Computer Science, University of Maryland College Park, 2023
* B.S. in Computer Science, The College of William and Mary, 2020

Work experience
======
* January 2023 - November 2025: Research Journeywoman
  * Army Research Lab, Content Understanding Branch
  * Duties includes: Leading basic research in Artificial Intelligence, coordinating and collaborating with a research team, publishing and presenting work at conferences 
  * Supervisor: Claire Bonial

* Summer 2022: Research Intern
  * Army Research Lab
  * Duties included: Developing and running experiments to test LLM understanding, Presenting Work to the lab during a 3 minute thesis challenge
  * Supervisor: Claire Bonial

* Fall 2022-Spring 2025: Teaching Assistant, Programming Languages
  * University of Maryland, College Park
  * Duties included: Leading discussion sessions, holding office hours, grading quizzes and exams
  * Supervisor: Cliff Bakalian
  
Skills
======
* Annotation Task Development
* Ontology Development
* Synthetic Data Generation
* Transformers
  * Supervised LLM fine-tuning with HuggingFace
  * PEFT and LoRA
  * Retrieval Augmented Generation
* LLM evaluation development

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
