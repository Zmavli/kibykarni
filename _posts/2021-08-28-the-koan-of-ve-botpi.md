---
title: The Koan of Ve Botpi
layout: post
date: 2021-08-28
description: A koan concerning the semantics of unfilled selbri.
tags: lojban conlangs
---

{% epigraph "The simple believe anything, but the prudent give thought to their steps." "The Bible, Proverbs 14:15" "NIV"%}

Let us examine the word "botpi".

> botpi: x1 is a bottle/jar/urn/flask/closable container for x2, made of material x3 with lid x4. [(Vlasisku)](https://vlasisku.lojban.org/botpi)

We know from [CLL 7.7](https://la-lojban.github.io/uncll/uncll-1.2.14/xhtml_section_chunks/section-zohe-cohe-series.html) that unfilled selbri places default to `zo'e`. 

> The cmavo of the zo'e-series represent indefinite, unspecified sumti. The cmavo zo'e represents an elliptical value for this sumti place; it is the optional spoken place holder when a sumti is skipped without being specified.

{% marginfigure 'otpi' '/assets/img'/otpi.jpeg ".i xu botpi?" %} This has very serious implications. Suppose I wished to refer to this bottle here. Were I to say...

> `to mibypre toi ti botpi` <br>
> `(Me): This is a bottle.`

...I would be lying. Were I in court, I would be charged with perjury. All of my friends will turn their backs on me for my deceitful character. 

Why is this so? It is because when I say `.i ti botpi`, I am actually saying `.i ti botpi zo'e zo'e zo'e`. I am claiming that there exists at least one thing that satisfies `ve botpi`, or the cap. Given that the bottle has no cap, it is therefore not `botpi`, but `botpi fo zi'o`{% sidenote 'ziho' "The cmavo `zi'o` deletes a place from a selbri. See [CLL 7.7](https://la-lojban.github.io/uncll/uncll-1.2.14/xhtml_section_chunks/section-zohe-cohe-series.html)" %}. The wise jbopre ought to consider carefully the terbri of their selbri. {% marginnote 'otpi' "There exists a jbofuvi `otpi`, meaning simply `x1 is a bottle/jar/urn/flask.`" %}

In contemporary Lojban as is spoken in [La Roljbogu'e](https://discord.gg/6Gt9YXwJEX), unfilled places usually are taken to mean `zo'e jonai zi'o`. This "forces" one to obey [Grice's Maxims of Quantity and Relation](https://www.sas.upenn.edu/~haroldfs/dravling/grice.html). If a place is truly important, one ought to explicitly say `zo'e`.

## Other loglangs
{% marginnote 'latin' "I have sometimes described Lojban as being the \"Latin of Loglangs\", because of many reasons, this being one of them." %} The idea of predicate place structures is something that basically all loglangs have some version of. 

 {% marginnote 'eberban' "As of the writing of this article, Eberban is very early in its development and its documentation is being rewritten. It is very possible that this will change." %} In [Eberban](https://mia-entropy.github.io/eberban/), unfilled places are even more extreme than in Lojban. Unfilled places are not filled with `zo'e` (i.e. simply an unspecified argument) but are instead considered to permit all arguments (i.e. everything can fulfill it).

{% marginnote 'help' "These are languages I'm familiar with. If you have knowledge of other loglangs like Gua\\spi, please email me so I can add to this section."%} In [Toaq](http://toaq.org/), unfilled places are simply deleted, akin to `zi'o`-ing away all unfilled places in Lojban selbri. 

## Further reading

[all places equally important gotcha](https://mw.lojban.org/papri/all_places_equally_important_gotcha): Partly the source of this post.
[inconsistent Place Structures Gotcha](https://mw.lojban.org/papri/inconsistent_Gismu_Place_Structures_Gotcha): Especially annoying given standard place semantics.



