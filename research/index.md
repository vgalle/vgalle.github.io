---
layout: page
title: Research
permalink: /research/
---

### Article

{% for paper in site.data.publications.article %}
 * {{paper.author}} ({{paper.year}}). [{{paper.title}}]({{paper.url}}). submitted to *{{paper.journal}}*.
{% endfor %}

### Journal

{% for paper in site.data.publications.journal %}
 * {{paper.author}} ({{paper.year}}). [{{paper.title}}]({{paper.pdfurl}}). *{{paper.journal}}*. {{paper.volume}} ({{paper.number}}): {{paper.pages}}. [Journal Link]({{paper.url}}).
{% endfor %}

### Unpublished Manuscript

{% for paper in site.data.publications.unpublished_manuscript %}
 * {{paper.author}} (last revised in {{paper.year}}). [{{paper.title}}]({{paper.url}}).
{% endfor %}

### Conference

{% for paper in site.data.publications.conference %}
 * {{paper.month}} {{paper.year}}: [{{paper.title}}]({{paper.url}}). *{{paper.name}}*.
{% endfor %}
