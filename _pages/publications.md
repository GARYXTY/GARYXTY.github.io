---
title: "Publications"
layout: gridlay
sitemap: false
permalink: /publications/
---

## Publications

<input type="text" class="pub-search" id="pubSearch" placeholder="Filter by title, author, or year...">

<div class="section-card publication-list" id="pubList" markdown="1">
{% capture publication_list %}{% include publications-list.md %}{% endcapture %}
{{ publication_list | markdownify }}
</div>
