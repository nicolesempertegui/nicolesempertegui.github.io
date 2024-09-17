---
layout: page
permalink: /publications/
title: publications
description: most entries follow alphabetical authorship. preprints are at the bottom of the page.
nav: true
nav_order: 2
---

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<!-- _pages/publications.md -->

<div class="publications">

 {% bibliography --group_by type,year --group_order ascending,descending %}

</div>


