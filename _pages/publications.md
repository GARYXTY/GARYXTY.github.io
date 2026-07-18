---
title: "Publications"
layout: gridlay
sitemap: false
permalink: /publications/
---

## Publications

<div class="section-card">
<p><strong>Research output:</strong> 19 first/co-first-author papers published or accepted, including eight journal papers, eleven international conference papers, and six IEEE Transactions papers. Three additional IEEE Transactions manuscripts are under review.</p>
<p><sup>+</sup> denotes equal contribution. Use the search box to filter the complete list by title, author, venue, or year.</p>
</div>

<input type="text" class="pub-search" id="pubSearch" placeholder="Filter by title, author, or year...">

<div class="section-card publication-list" id="pubList" markdown="1">
{% capture publication_list %}{% include publications-list.md %}{% endcapture %}
{{ publication_list | markdownify }}
</div>
