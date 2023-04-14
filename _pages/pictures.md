---
title: "GM2M - Gallery"
layout: piclay
excerpt: "GM2M - Gallery"
permalink: /pictures/
---

<!-- # Pictures -->
<!-- Jump to: [Leiden](#leiden), [ETHZ](#ethz), [Cornell](#cornell), [St Andrews](#st-andrews) -->

# Videos

Prof. Hing-Ho Tsang's Guest Lecture "Geotechnical Seismic Isolation". Delivered on March 3<sup>rd</sup>, 2023 to our MSc students. 
<iframe width="560" height="315" src="https://www.youtube.com/embed/7d73nlwwA8A" frameborder="0" allowfullscreen></iframe>


# RSm trenches - shaking table testing
(Right-click *'view image'* to see a larger image.)
{% assign number_printed = 0 %}
{% for pic in site.data.pictures_RSm %}

{% assign even_odd = number_printed | modulo: 4 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-3 clearfix">
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/Gallery/{{ pic.image }}" class="img-responsive" width="95%" style="float: left" />
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd > 2 %}
</div>
{% endif %}


{% endfor %}

{% assign even_odd = number_printed | modulo: 4 %}
{% if even_odd == 1 %}
</div>
{% endif %}

{% if even_odd == 2 %}
</div>
{% endif %}

{% if even_odd == 3 %}
</div>
{% endif %}

<p> &nbsp; </p>


<!-- Example image insertion 
## ETHZ
From the [group of Andreas Wallraff](http://www.qudev.ethz.ch/).
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/WebpageETH_red.jpg" width="60%">
</figure>  -->
