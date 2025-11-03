# Summary

UD_Polish-MPDT is a treebank of Middle Polish (17th–18th centuries). It is a rule-based conversion of the [Middle Polish Dependency Treebank](https://korba.edu.pl/treebank?lang=en) (Wieczorek, 2025) from its original annotation to the Universal Dependencies format. The MPDT sentences are sourced from the [KorBa corpus](https://korba.edu.pl/overview?lang=en) (Gruszczyński et al., 2022). 

# Introduction

The UD_Polish-MPDT treebank contains sentences from the Middle Polish period (17th–18th centuries). The material is drawn from the [KorBa corpus](https://korba.edu.pl/overview?lang=en) – The Electronic Corpus of 17th- and 18th-century Polish Texts – a large and diverse collection of Polish literature, scientific texts, official documents, press releases, and more from 1601–1772.

The syntactic annotations originate from the [Middle Polish Dependency Treebank](https://korba.edu.pl/treebank?lang=en), a project led by Aleksandra Wieczorek, which adds a dependency layer to a selected part of KorBa. The original MPDT annotation follows the conventions of the [Polish Dependency Bank (PDB)](https://zil.ipipan.waw.pl/PDB).

This initial UD release contains 2,018 sentences and approximately 47K tokens, with plans for further expansion in future versions.

# Data

## Data Split

In line with the guidelines for treebanks of 20K–110K words, approximately 10K words were allocated to the test set, ~10% of the remaining data to the development set, and the rest to the training set. The sentences were randomly shuffled (using seed 42) and then assigned to the three subsets based on token-count quotas:

| Set   | Sentences | Tokens |
|-------|-----------|--------|
| Train | 1 433     | 33 520 |
| Dev   | 162       | 3 748  |
| Test  | 423       | 10 005 |

## Genres / Document Structure

This treebank **does not** separately label genres or domains by the sentence IDs, and the sentences are **not complete documents**. The corpus sentences have been shuffled randomly at the sentence level to form the splits.

# Development Team

We thank the original Middle Polish Dependency Treebank team, led by Dr. Aleksandra Wieczorek. The data was annotated by Aleksandra Wieczorek, Bożena Itoya, Emanuel Modrzejewski, and Martyna Sabała-Bolek. Programming support for data preparation was provided by Dorota Komosińska.

The conversion to the UD format was developed by Kamil Tomaszek as part of his M.A. thesis at the University of Warsaw, under the supervision of Dr. Alina Wróblewska (Institute of Computer Science, Polish Academy of Sciences).

# References

* Gruszczyński, Włodzimierz; Adamiec, Dorota; Bronikowska, Renata; Kieraś, Witold; Modrzejewski, Emanuel; Wieczorek, Aleksandra; Woliński, Marcin. 2022. “The Electronic Corpus of 17th- and 18th-century Polish Texts.” *Language Resources and Evaluation*, 56(1): 309-332. https://doi.org/10.1007/s10579-021-09549-1  
* Wieczorek, Aleksandra. 2025. “Towards the Middle Polish Dependency Treebank.” In *Native Language in the 21st Century: System, Communication Practices and Education*. V & R Unipress.

# Changelog

* 2025-11-15 v2.17
  * Initial release in Universal Dependencies.


<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.17
License: CC BY-SA 4.0
Includes text: yes
Parallel: no
Genre: nonfiction bible legal fiction
Lemmas: manual native
UPOS: converted from manual
XPOS: automatic with corrections
Features: converted from manual
Relations: converted from manual
Contributors: Tomaszek, Kamil; Wróblewska, Alina; Wieczorek, Aleksandra
Contributing: here
Contact: kt.tomaszek@student.uw.edu.pl
===============================================================================
</pre>
