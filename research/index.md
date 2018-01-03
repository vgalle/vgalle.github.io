---
layout: page
title: Research
permalink: /research/
---

### Working Paper

{% for paper in site.data.publications.working_paper %}
 * {{paper.author}}. [{{paper.title}}]({{paper.url}}). *{{paper.working_paper}}*. Volume {{paper.volume}}-{{paper.number}}. Pages {{paper.pages}}. {{paper.year}}
{% endfor %}

### Journal

{% for paper in site.data.publications.journal %}
 * {{paper.author}}. [{{paper.title}}]({{paper.url}}). *{{paper.journal}}*. Volume {{paper.volume}}-{{paper.number}}. Pages {{paper.pages}}. {{paper.year}}
{% endfor %}

### Unpublished Manuscript

{% for paper in site.data.publications.unpublished_manuscript %}
 * {{paper.author}}. [{{paper.title}}]({{paper.url}}). *{{paper.unpublished_manuscript}}*. {{paper.year}}
{% endfor %}

### Conference

{% for paper in site.data.publications.conference %}
 * {{paper.author}}. [{{paper.title}}]({{paper.url}}). *{{paper.conference}}*. {{paper.year}}
{% endfor %}
