---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Complete, printable version can be found [here](https://jncwinner.github.io/files/J.Carpenter_CV.pdf).

Education
======
* Ph.D. in Computing, emphasis in Computer Science, Boise State University, 2024
  * Specialization: Machine Learning, Graph Representation Learning, Graph Neural Networks
* B.S. in Computer Science, Boise State University, 2020

Work experience
======
* December 2020 - December 2024: Graduate Research Assistant
  * Boise State University
  * Duties include:
    * Conducting research in AI-based Security (AIbS) Lab on machine learning algorithms and graph representations
    * Publishing research papers (IEEE Big Data, VLDB) on topics such as Temporal SIR-GN, 2FWL-SIRGN, and Inferential SIR-GN
    * Developing a structural graph partitioning algorithm to improve processing efficiency
    * Designing multi-threaded and Spark-based implementations for algorithm optimization
  * Supervisor: Dr. Edoardo Serra

* January 2023 - May 2023: Teaching Assistant for CS 535 Large Scale Data Analysis
  * Boise State University
  * Duties included:
    * Assisting in teaching large-scale data analysis topics such as MapReduce, Hadoop, and Spark
    * Grading assignments and providing weekly tutoring sessions on debugging and exam preparation

* August 2022 - December 2022: Teaching Assistant for CS 534 Machine Learning
  * Boise State University
  * Duties included:
    * Supporting machine learning course instruction on algorithms such as Graph Neural Networks, SVM, and decision trees
    * Grading assignments, exams, and projects, and offering daily tutoring sessions

* August 2021 - May 2022: Teaching Assistant for CS 361 Theory of Computation
  * Boise State University
  * Duties included:
    * Teaching topics such as regular languages, finite automata, and Turing machines
    * Grading assignments, exams, and proofs, and providing tutoring sessions

* August 2020 - May 2021: Teaching Assistant for CS 321 Data Structures
  * Boise State University
  * Duties included:
    * Teaching data structure design and implementation, including hash tables and binary search
    * Grading assignments across two sections and providing tutoring

* January 2020 - May 2020: Lab Assistant for CS 121
  * Boise State University
  * Duties included:
    * Assisting with debugging and project comprehension
    * Supporting transition to online learning through collaboration with tutors and professors

Skills
======
* Programming Languages: Python, Java, C#, SQL
* Machine Learning Frameworks: TensorFlow, PyTorch, Jupyter Notebook
* Data Analysis and Visualization: Pandas, Matplotlib, Seaborn
* Agile Development Methodologies: Scrum
* Strong teamwork, problem-solving, and critical thinking skills

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

Service and leadership
======
* Mentored students in machine learning and data structures courses
* Collaborated with peers on research and publication preparation
