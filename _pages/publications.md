---
title: Sairam Tabibu's publications
layout: default
excerpt: Sairam Tabibu's publications
permalink: /publications

---
## Journal papers

{% for publication in site.data.journal_papers %}

{% include publications.html %}

{% endfor %}

<p>&nbsp;</p>

<!-- {% assign numOfJournals = loopindex %}
{% endcomment %} -->

<!-- ## Thesis / Reports

{% for publication in site.data.reports %}

{% include publications.html %}

{% endfor %}
 -->
---
{% comment %}
## Conference papers

{% for publication in site.data.conference_papers %}

{% include publications.html %}

{% endfor %}

<p>&nbsp;</p>

<!-- ## Under review

{% for publication in site.data.under_review_papers %}

{% include publications.html %}

{% endfor %}

<p>&nbsp;</p> -->

