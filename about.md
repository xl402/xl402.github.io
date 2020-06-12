---
layout: page
title: About
permalink: /about/
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

## I am Tom,

A Data Scientist at [SeamlessML](https://www.seamlessml.com/), utilizing Machine Learning to forecast alternative financial markets. In 2020, I graduated with an MEng from the University of Cambridge, specializing in Information Engineering and Computational Neuroscience.

My interests involve developing principled Bayesian models. Specifically, models that are well-calibrated and ‘know what they don’t know’, and models which are able to inherently deal with missing features and scarce/unlabelled data. I am also keen on investigating how model performance can be boosted to state-of-the-art using innovative feature-engineering and ensembling methods.

</div>
