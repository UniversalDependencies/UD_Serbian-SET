# Summary

The Serbian UD treebank is based on the [SETimes-SR](http://hdl.handle.net/11356/1200) corpus and 
additional news documents from the Serbian web.

# Annotation Source

* Lemmas: automatic pretagging + manual correction (there's no format/annotation style for this)
* UPOS, features: converted from [MULTEXT-East](http://nl.ijs.si/ME/V6/msd/html/msd-hbs.html)
* Dependency realations: automatic preprocessing + manual correction, all directly in UD.

# Data Split

Training data: 80% of pseudorandom documents from SETimes-SR (sentence ids ```set*```) and 
13 web news documents (sentence ids ```news*```), comprising 3497 sentences (77,334 tokens).

Development data: 10% of pseudorandom documents from SETimes-SR (sentence ids ```set*```) and 
13 web news documents (sentence ids ```news*```), comprising 476 sentences (11,460 tokens).

Test data: 10% of pseudorandom documents from SETimes-SR (sentence ids ```set*```) and 
13 web news documents (sentence ids ```news*```), comprising 411 sentences (8,879 tokens).

The corpus is parallel with a subset of UD Croatian-SET. In release 2.4, the Serbian
and Croatian treebanks were re-split so that training, development and test sets
are compatible (corresponding documents are in the same section in both languages).

# Changelog

* 2019-04-30 v2.4
  * New data split
  * 13 web news documents added

* 2018-04-15 v2.2
  * Repository renamed from UD_Serbian to UD_Serbian-SET.

<pre>
=== Machine-readable metadata =================================================
Data available since: UD v2.1
License: CC BY-SA 4.0
Includes text: yes
Genre: news
Lemmas: manual native
UPOS: converted from manual
XPOS: not available
Features: converted from manual
Relations: manual native
Contributors: Samardžić, Tanja; Ljubešić, Nikola
Contributing: elsewhere
Contact: tanja.samardzic@uzh.ch
===============================================================================
</pre>
