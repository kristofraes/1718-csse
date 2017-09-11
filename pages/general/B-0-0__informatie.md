---
layout: course
permalink: informatie/
#
title: Informatie
---
{%- assign syllabus = site.data.shared.syllabi | where: 'id', site.syllabus-id | first %}
{% include course/content/abbreviations-education.md %}
{% include course/content/abbreviations-computer.md %}
{% include course/content/hyperlinks-education.md %}

ECTS
----

### Fiche

{% include course/content/info-ects.md %}

### Studieomvang

{% include course/content/info-workload.md %}

### Begincompetenties

{% include course/content/info-competences-start.md %}

### Eindcompetenties

{% include course/content/info-competences-end.md %}

### Inhoud

{% include course/content/info-content.md %}

### Doelstellingen

{% include course/content/info-objectives.md %}

### Studiemateriaal

{% include course/content/info-course-materials.md %}

Evaluatie
---------

### Beoordelingsschaal

{% include course/content/info-grading-scale.md %}

### Bijkomende voorwaarden

{% include course/content/info-additional-conditions.md %}

Professionele houding
---------------------

{% include course/content/info-attitude.md %}