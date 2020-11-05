---
title: Home
---

# Workshop Template!

{% include figure.html img="uidaho-workshop.jpg" alt="intro image here" caption="NLP Workshop 1960" width="75%" %}


*Add your workshop abstract here!*

In this workshop we are going to explore various approaches to dealing with natural language aka text data. Due to time constraints I will keep things rather "shallow" but hopefully you will get inspired to go deeper with some of this on your own.


## 2 ways of working with text

* ### Element level (from long texts or collections of text) e.g. network of entities from a book or collection of news articles

* ### Representations of short text 
  * Supervised approches: e.g. classification of many short texts
  * Unsupervised approaches: e.g. topic modelling (clustering)

## Corresponding questions:

* Are there some central elements/concepts? Can we identify interesting patterns of interaction?
* Can we develop a model that maps text inputs to a specific output given labeled data?
* Can we identify some coherent latent topics/themes in a given corpus?

*See also:* [workshop-template-b](https://evanwill.github.io/workshop-template-b/), Bootstrap version.

<div class="toc" markdown="1">
## Contents:

{% for lesson in site.pages %}
{% if lesson.nav == true %}- [{{ lesson.title }}]({{ lesson.url | absolute_url }}){% endif %}
{% endfor %}
</div>

Hosted by [University of Idaho Library](http://www.lib.uidaho.edu/), {{ site.pub_year }}.
 
> built using [Jekyll](https://jekyllrb.com/) and [GitHub Pages](https://pages.github.com/)
>
> images and content: cc-by-sa <a href="https://github.com/{{ site.github_username }}">{{ site.author }}</a> {{ site.pub_year}} (get [source code]({{ site.repo }})).
> Last build date: {{ site.time | date: "%Y-%m-%d" }}.
>
> <a href="http://creativecommons.org/licenses/by-sa/4.0/" rel="license"><img style="border-width: 0;" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" alt="Creative Commons License" /></a>
