---
layout: page
permalink: /publications/
title: publications
description:
nav: true
nav_order: 2
---

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<!-- _pages/publications.md -->

<div class="publications">

 {% bibliography --group_by type,year --group_order ascending,descending %}

</div>


