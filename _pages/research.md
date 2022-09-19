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

<a href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4010282">Shifts in ECB Communication: A Textual Analysis of the Press Conferences </a> 
(with Robin Lumsdaine)
*Forthcoming, International Journal of Central Banking*. 

<a href="https://doi.org/10.3390/vaccines10081190">Attitudes toward COVID-19 Vaccination on Social Media: A Cross-Platform Analysis </a>  (with Dominik Wawrzuta, Mariusz Jaworski, Joanna Gotlib and Mariusz Panczyk) *Vaccines*. 2022; 10(8):1190. 

**Policy papers:**

<a href="https://www.gov.pl/web/finanse/no-72022-p-chrostek-j-klejdysz-m-skawinski-wybrane-aspekty-systemu-podatkowo-skladkowego-na-podstawie-danych-administracyjnych-2018">P. Chrostek, J. Klejdysz, M. Skawiński: Wybrane aspekty systemu podatkowo-składkowego na podstawie danych administracyjnych 2018</a> 
 (English title: Selected aspects of the Polish tax and social contributions system based on administrative data 2018). *Polish Ministry of Finance Essays and Analyses Series*. 2022. Also earlier editions of this report for years <a href="https://www.gov.pl/web/finanse/no-4-2020-pchrostek-j-klejdysz-mskawinski">2017</a> , <a href="https://www.gov.pl/web/finanse/wybrane-aspekty-systemu-podatkowo-skladkowego-na-podstawie-danych-pit-i-zus-2016">2016</a> .

<a href="https://www.gov.pl/web/finanse/no-5-2021-j-klejdysz">J. Klejdysz: Dlaczego liczba osób prowadzących działalność gospodarczą wzrosła w czasie pandemii?</a> (English title: Why did the number of self-employed increased during the pandemic?)  *Polish Ministry of Finance Essays and Analyses Series*. 2021. 




{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
