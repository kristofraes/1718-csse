---
layout: revealjs
permalink: presentations/default/
title: Default presentation
title_long: Default presentation for Syllabi
description: Presentatie over de afstudeerrichting multimediaproductie (MMP). Nieuwe Keuzetrajecten Audiovideo Creation (AVC) en New Media Development (NMD). Overzicht van profiel, jobs, inhoud en programma.
keywords: default, syllabi, gdm
thumbnail_url: assets/mmp.png
---

{% assign page_path = page.path | split: '/' %}
{% capture page_path_folder %}{{ page_path[0] }}/{{ page_path[1] }}/{{ page_path[2] }}/{% endcapture %} 
{% assign page_url_parts = page.url | split: '/' %}
{% assign page_back_amount = page_url_parts.size | minus: 1 %}
{% assign page_back_str = '' %}
{% for i in (1..page_back_amount) %}
    {% assign page_back_str = page_back_str | append: '../' %}
{% endfor %}

<section class="slides__chapter">
    <section data-markdown="{{ page_back_str }}/{{ page_path_folder | append: 'content/intro.md' }}" class="slides__homepage"></section>
</section>