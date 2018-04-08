# Summary

The Serbian UD treebank is based on the SETimes-SR corpus.

# Data Split

The first 2935 sentences (65764 tokens) are designated as training data.
The next   465 sentences (10099 tokens) are designated as development data.
The final  491 sentences (10891 tokens) are designated as test data.

The corpus is parallel with a subset of UD Croatian-SET. In release 2.2, the
Croatian treebank was re-split so that training, development and test sets
are compatible (corresponding sentences are in the same section in both
languages). For the time being, the ids of the Croatian sentences have been
left intact. The correspondences below thus hold, as far as sentence ids are
involved, but Croatian sentence "train-s2852" now resides in the Croatian
development data file. The sentence ids may be harmonized in future releases.

* Serbian training data corresponds to first part of Croatian training data
  * SR: s1 to s2935
  * HR: train-s1 to train-s2851
* Serbian development data corresponds to second part of Croatian training data
  * SR: s2936 to s3400
  * HR: train-s2852 to train-s3300
* First part of Serbian test data corresponds to third part of Croatian training data
  * SR: s3401 to s3670
  * HR: train-s3301 to s3557
* Second part of Serbian test data corresponds to first part of Croatian dev data
  * SR: s3671 to s3891
  * HR: dev-s1 to dev-s200

# Changelog

* 2018-04-15 v2.2
  * Repository renamed from UD_Serbian to UD_Serbian-SET.

<pre>
=== Machine-readable metadata =================================================
Data available since: UD v2.1
License: CC BY-SA 4.0
Includes text: yes
Genre: news
Contributors: Samardžić, Tanja; Ljubešić, Nikola
Contact: tanja.samardzic@uzh.ch
===============================================================================
</pre>
