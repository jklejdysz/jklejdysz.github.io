---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

**Current Projects:**

Employment and Self-Employment Transitions in Response to Differential Taxation (with Tom Zawisza)

Attitudes towards private and public debt (with Cevat Aksoy, Mathias Dolls, Andreas Peichl and Lisa Windsteiger) 

**Publications in Refereed Journals:**

Shifts in ECB Communication: A Textual Analysis of the Press Conferences (with Robin Lumsdaine)
Forthcoming, International Journal of Central Banking. https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4010282

Attitudes toward COVID-19 Vaccination on Social Media: A Cross-Platform Analysis (with Dominik Wawrzuta, Mariusz Jaworski, Joanna Gotlib and Mariusz Panczyk) Vaccines. 2022; 10(8):1190. https://doi.org/10.3390/vaccines10081190

**Policy papers:**

Polish Ministry of Finance paper series: https://www.gov.pl/web/finanse/mf-opracowania-i-analizy

No 7-2022, P. Chrostek, J. Klejdysz, M. Skawiński: Wybrane aspekty systemu podatkowo-składkowego na podstawie danych administracyjnych 2018

No 5-2021, J. Klejdysz: Dlaczego liczba osób prowadzących działalność gospodarczą wzrosła w czasie pandemii?

No 4-2020, P. Chrostek, J. Klejdysz, M.Skawiński: Wybrane aspekty systemu podatkowoskładkowego na podstawie danych administracyjnych 2017

No 1-2019, P. Chrostek, J. Klejdysz, D. Korniluk, M. Skawiński: Wybrane aspekty systemu podatkowo-składkowego na podstawie danych PIT i ZUS 2016



{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
