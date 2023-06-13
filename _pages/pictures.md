---
title: "GM2M - Gallery"
layout: piclay
excerpt: "GM2M - Gallery"
permalink: /pictures/
---

Jump to: [Lectures](#guest-lectures), [RSm](#rsm-trenches---shaking-table-testing), [Conferences](#conferences), [Teaching](#teaching-aids)

# Guest lectures #

Presentation delivered by Mariola Zielinska and Michael Reed from Atkins to our MSc students on March 31<sup>st</sup>. "Offshore Geotechnics - Basic Considerations and Jacket Foundation Design
<iframe width="560" height="315" src="https://www.youtube.com/embed/vcOsJWrBLM0" frameborder="0" allowfullscreen></iframe>

Prof. Hing-Ho Tsang's Guest Lecture "Geotechnical Seismic Isolation". Delivered on March 3<sup>rd</sup>, 2023 to our MSc students. 
<iframe width="560" height="315" src="https://www.youtube.com/embed/7d73nlwwA8A" frameborder="0" allowfullscreen></iframe>

# RSm trenches - shaking table testing #
(Right-click *'view image'* to see a larger image.)
{% assign number_printed = 0 %}
{% for pic in site.data.pictures_RSm %}

{% assign even_odd = number_printed | modulo: 4 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-3 clearfix">
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/Gallery/RSm/{{ pic.image }}" class="img-responsive" width="95%" style="float: left" />
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

<iframe width="560" height="315" src="https://www.youtube.com/embed/ZmgNIcaucdg" frameborder="0" allowfullscreen></iframe>

# Conferences #

[NANGE 2023](http://www.nange.info/).
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/Gallery/Conferences/Assisi2023.jpg" width="60%">
</figure>  -->

# Teaching aids #

Effect of short and high frequency earthquakes on multi-storey buildings
<iframe width="560" height="315" src="https://www.youtube.com/embed/bIqV95gIf9o" frameborder="0" allowfullscreen></iframe>

Cyclic triaxial test on SRm
<iframe width="560" height="315" src="https://www.youtube.com/embed/5z-nPGQiF1k" frameborder="0" allowfullscreen></iframe>


<!-- Example image insertion 
## ETHZ
From the [group of Andreas Wallraff](http://www.qudev.ethz.ch/).
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/WebpageETH_red.jpg" width="60%">
</figure>  -->
