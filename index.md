---
layout: home
title: Home
nav_exclude: false
nav_order: 1
permalink: index.html
seo:
  type: Course
  name: COS 324 - Introduction To Machine Learning
---

# {{ site.tagline }}
{: .mb-2 }
{{ site.description }}
{: .fs-6 .fw-300 }

## About
This website contains the course notes for COS 324 - Introduction to Machine Learning at Princeton University. The notes were prepared by professors Sanjeev Arora, Danqi Chen and undergraduates Simon Park, and Dennis Jacob.

If you find any typos or mistakes, or have any comments or feedback, please submit them [here](https://bit.ly/cos324-notes-feedback). It will be helpful if you specify the version of the notes. The last modified date can be found on the copyright page.

## Errata
The currently maintained version of the errata can be found [here](files/errata.pdf){:targe="_blank"}.

## Full Version
[Introduction to Machine Learning](files/COS324_Course_Notes.pdf){:target="_blank"}

## Individual Chapters
{% for module in site.modules %}
{{ module }}
{% endfor %}

<a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/2.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-nd/2.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/2.0/">Creative Commons Attribution-NonCommercial-NoDerivs 2.0 Generic License</a>
