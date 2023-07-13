---
title: "Security and Artificial Intelligence Lab - Pictures"
layout: piclay
excerpt: "Security and Artificial Intelligence Lab -- Pictures"
permalink: /pictures/
---

# Pictures

<!-- Jump to: [Security and Artificial Intelligence Lab](#Information-Security-Lab), [VinUni-Illinois Smart Health Center](#shc) -->
<!-- , [Cornell](#cornell), [St Andrews](#st-andrews) -->

<!-- Jump to: [Leiden](#leiden), [ETHZ](#ethz), [Cornell](#cornell), [St Andrews](#st-andrews) -->

## Security and Artificial Intelligence Lab

<!-- #### Timelapse of our STM assembling [(see LION news item)](https://www.physics.leidenuniv.nl/index.php?id=11573&news=867&type=lion&ln=EN):
<iframe width="560" height="315" src="https://www.youtube.com/embed/3iKvUMv1h5A" frameborder="0" allowfullscreen></iframe> -->

<!-- #### Welcome to VinUniversity:

<iframe width="560" height="315" src="https://www.youtube.com/embed/RFikpr2jHJo" frameborder="0" allowfullscreen></iframe> -->

#### Gallery

<!-- (Right-click _'view image'_ to see a larger image.) -->
{% assign number_printed = 0 %}
{% for pic in site.data.pictures_sail %}

{% assign even_odd = number_printed | modulo: 4 %}

{% if even_odd == 0 %}

<div class="row">
{% endif %}

<div class="col-sm-3 clearfix">
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/Gallery/{{ pic.image }}" class="img-responsive" width="95%" style="float: left" /> 
<!-- <img src="{{ site.url }}{{ site.baseurl }}/images/home/{{ pic.image }}" class="img-responsive" width="95%" style="float: left" /> -->

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

<!-- First advertisement.
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/WebpageLeiden_red.jpg" width="60%" >
</figure> -->

<!-- ## VinUni-Illinois Smart Health Center -->

<!-- From the [group of Seamus JC Davis](http://davisgroup.lassp.cornell.edu). -->
<!-- <figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/Gallery/Teacher-01.jpeg" width="60%">
</figure> -->

<!-- <figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/Gallery/team-bonding-1.jpg" width="60%">
</figure> -->
<!-- /Volumes/tuan/phd/vinuni/infosecvinuni/images/picpic/Gallery/team-bonding-1.jpg -->
<!-- /Volumes/tuan/phd/vinuni/infosecvinuni/images/picpic/Gallery/Teacher-01.jpeg -->
<!-- ## ETHZ
From the [group of Andreas Wallraff](http://www.qudev.ethz.ch/).
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/WebpageETH_red.jpg" width="60%">
</figure>

<!-- ## Cornell

From the [group of Seamus JC Davis](http://davisgroup.lassp.cornell.edu).

<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/WebpageCornell_red.jpg" width="60%">
</figure>

## St Andrews

From the [group of Felix Baumberger](http://dqmp.unige.ch/baumberger/) (now at University of Geneva).

<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/WebpageSTA_red.jpg" width="60%">
</figure> -->
