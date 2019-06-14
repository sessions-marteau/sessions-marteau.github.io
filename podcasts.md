---
layout: page
title: Podcasts
permalink: /podcasts/
published: true
---

<div class="page" markdown="1">

{% capture page_subtitle %}
<img
    class="me"
    alt="{{ author.name }}"
    src="{{ site.author.photo | relative_url }}"
    srcset="{{ site.author.photo2x | relative_url }} 2x"
/>
{% endcapture %}

{% include page/title.html title=page.title subtitle=page_subtitle %}

<!-- ## Some heading  -->

<iframe src="https://embed.iono.fm/epi/699906" width="100%" height="135" frameborder="0"><a href="https://iono.fm/e/699906">Content hosted by iono.fm</a></iframe>

<iframe src="https://embed.iono.fm/epi/699907" width="100%" height="135" frameborder="0"><a href="https://iono.fm/e/699907">Content hosted by iono.fm</a></iframe>

</div>
