# Data Split

The first 2935 sentences (65764 tokens) are designated as training data.
The next   465 sentences (10099 tokens) are designated as development data.
The final  491 sentences (10891 tokens) are designated as test data.

WARNING: At present, the data cannot be split in a way that is compatible with
the data split of the partially parallel Croatian UD treebank. This poses a
problem for evaluation of any tools that are trained on Croatian and applied
to Serbian.

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

<pre>
=== Machine-readable metadata =================================================
Data available since: UD v2.1
License: CC BY-SA 4.0
Includes text: yes
Genre: news wiki
Contributors: Samardžić, Tanja; Ljubešić, Nikola
Contact: tanja.samardzic@uzh.ch
===============================================================================
</pre>
