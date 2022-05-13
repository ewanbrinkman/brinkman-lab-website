---
title: Publications
subtitle:
description: "{{ site.data.settings.basic_settings.site_title }} publications."
# featured_image: /images/scenery/sfu-library.jpg
featured_image: /images/publications/publications-banner.jpg
---

# Publications

See an up-to-date list of most Brinkman Lab publications in the following resources:

[PubMed]({{ site.data.settings.urls.pubmed }}) (doesn’t include non-medical papers)

[Google Scholar]({{ site.data.settings.urls.google_scholar }}) (includes more publications but not those before my surname changed from Lawson to Brinkman in 1997)

#### Selected Publications

<ul>
  {% for publication in site.data.publications %}
  <div class="publication">
  <li>
    {{ publication | link_pubmed: 'PMID: ', 'PMCID: ' | markdownify }}
  </li>
  </div>
  <br>
  {% endfor %}
</ul>
