---
layout: archive
title: "Curriculum vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
  - /cv-json/
  - /resume-json
---

<p><a href="{{ '/files/CV_26_09.pdf' | relative_url }}" class="btn btn--primary" target="_blank" rel="noopener">CV (PDF)</a></p>

## Education

**2023–present — PhD in Mathematics**  
Scuola Normale Superiore, Pisa.  
Advisor: [Michele D'Adderio](https://people.dm.unipi.it/dadderio/).

**2018–2024 — Corso Ordinario, Faculty of Sciences (Mathematics)**  
Scuola Normale Superiore, Pisa.  
Final grade: 100/100 cum laude.

**2021–2023 — Master's degree in Mathematics**  
Università di Pisa. Final grade: 110/110 cum laude.  
Advisor: [Michele D'Adderio](https://people.dm.unipi.it/dadderio/).  
Thesis: *A generalisation of the Shuffle Theorem*.

**2021–2023 — Erasmus**  
Université Paris-Saclay.

**2018–2021 — Bachelor's degree in Mathematics**  
Università di Pisa. Final grade: 110/110 cum laude.  
Advisor: [Giovanni Gaiffi](https://people.dm.unipi.it/gaiffi/).  
Thesis: *Littlewood–Richardson rule*.

## Research visits

**09–10/2025 — Research visit**  
Université du Québec à Montréal, Montréal, Canada.  
Hosted by [Christophe Hohlweg](https://hohlweg.math.uqam.ca/).

**02–03/2026 — Research visit**  
University of Galway, Galway, Ireland.  
Hosted by [Angela Carnevale](https://angelacarnevale.github.io/).

## Publications and preprints

{% assign publications = site.publications | sort: "sort_order" | reverse %}
{% for entry in publications %}
  {% include academic-entry.html compact=true %}
{% endfor %}

## Talks

{% assign talks = site.talks | sort: "sort_order" | reverse %}
{% for entry in talks %}
  {% include academic-entry.html compact=true %}
{% endfor %}

## Professional experience

**2021–2022 — Revision of the Italian translation of Gauss's [*Disquisitiones Arithmeticae*](https://edizioni.sns.it/prodotto/ricerche-aritmetiche/)**  
Revision of the Italian translation edited by S. Graffi and C. Larese, published by Edizioni della Normale, Pisa.

## Computer skills

- **Good:** Python, C, SageMath.
- **Basic:** \\(\\text{\LaTeX a}\\).

## Languages

- **Native:** Italian and Sicilian.
- **Advanced:** English.
- **Basic:** French.
