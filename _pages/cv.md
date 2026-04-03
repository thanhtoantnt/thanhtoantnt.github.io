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
* Ph.D. in Computer Science, National University of Singapore, 2016 - 2022
* B.S. in Computer Science, VNU University of Engineering and Technology, 2011 - 2015

Work experience
======
* October 2023 - Present: Researcher
  * Huawei, Hong Kong SAR
  * Applying formal methods to solve practical problems, including TLA+ for modeling distributed systems, VeriFast for verifying data structure programs, and property-based testing

* April 2022 - October 2023: Research Fellow
  * National University of Singapore

* September 2019 - December 2019: Applied Scientist Intern
  * Amazon, London, United Kingdom

* February 2016 - July 2016: Research Assistant
  * NUS Computing, Singapore

* July 2015 - January 2016: Internship Student
  * National University of Singapore

* January 2015 - March 2015: Research Student
  * JAIST, Ishikawa, Japan

* April 2014 - October 2014: Software Developer
  * FPT Software, Hanoi, Vietnam
  
Skills
======
* Static Analysis
* TLA+
* Formal Verification

Languages
======
* English (Full Professional)
* Vietnamese (Native or Bilingual)
* Chinese (Professional Working)
* Cantonese (Elementary)

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
