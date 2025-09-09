# Summary

The Lithuanian dependency treebank ALKSNIS v3.0 (Vytautas Magnus University).

# Introduction

This is a conversion of the ALKSNIS treebank to Universal Dependencies.
The original treebank was annotated in a style derived from the Prague Dependency Treebank of Czech.
The original treebank is available at
[https://github.com/Semantika2/Alksnis-v.3.0](https://github.com/Semantika2/Alksnis-v.3.0).
ALKSNIS v2.1 is published in the CLARIN LT repository at
[http://hdl.handle.net/20.500.11821/10](http://hdl.handle.net/20.500.11821/10).
(Some users experience DNS errors when trying to access the repository;
configuring the client machine to use 8.8.8.8 as the DNS server may help.
See also [http://clarin-lt.lt/?page_id=86](http://clarin-lt.lt/?page_id=86).)

ALKSNIS v3 consists of 3,643 syntactically annotated sentences.
Each node of a tree corresponds to a word, a punctuation mark or other text
element (symbol, digit etc.) within a sentence. The following information is
presented for each node: 1) a used form; 2) a lemma; 3) a morphology tag,
and 4) a syntactic function (subject, object, etc.). Dependencies are shown
by links between words.

The morphology tag set Jablonskis is used since ALKSNIS v2.2 and in the XPOS
column of the UD conversion. This is a change from ALKSNIS 2 where a version
of the MULTEXT-East tag set was used.
<!--A version of the MULTEXT-East
(http://nl.ijs.si/ME/V4/msd/html/index.html)
tag set is used in ALKSNIS v2 and in the XPOS column of the UD conversion.-->
Syntactically annotated sentences
are corrected according to guidelines that were created by scientists of
VMU CCL, following rules of Prague Dependency Treebank. All the sentences are
being manually checked and corrected by a group of linguists.

# Acknowledgements

From v2.1 to v3.0 the treebank was developed within the project "Semantika2"
(Nr. 02.3.1-CPVA-V-527-01-0002). The project was funded by European Structural Funds.

## References

* Agnė Bielinskienė, Loïc Boizou, Jolanta Kovalevskaitė, Erika Rimkutė (2016): Lithuanian Dependency Treebank ALKSNIS.
  In: I. Skadiņa and R. Rozis (Eds.): Human Language Technologies – The Baltic Perspective, pp. 107–114. Amsterdam: IOS Press.
  doi:10.3233/978-1-61499-701-6-107
  [http://fcim.vdu.lt/~erika_rimkute/straipsniai/Alksnis_HLT.pdf](http://fcim.vdu.lt/~erika_rimkute/straipsniai/Alksnis_HLT.pdf),
  [http://ebooks.iospress.nl/volumearticle/45523](http://ebooks.iospress.nl/volumearticle/45523).


# Changelog

* 2025-11-15 v2.17
  * Relation subtype flat:foreign merged with flat after newly run conversion.
* 2025-05-15 v2.16
  * Adjectives heading clauses are acl(:relcl) rather than amod.
* 2024-05-15 v2.14
  * Added the enhanced relation subtype nsubj:xsubj.
  * More restrictive use of orphans and empty nodes: Not in non-verbal coordinated sentences.
  * Improved form and position of abstract predicates in gapping.
* 2021-05-15 v2.8
  * Fixed order of lemmas in enhanced deprels.
* 2020-11-15 v2.7
  * Improved conversion of subordinate clauses headed by a nominal predicate.
* 2020-05-15 v2.6
  * Genitive, dative and instrumental nominals are now considered oblique.
  * Added enhanced relations with case information.
  * Added enhanced relations around relative clauses.
  * Added enhanced external subjects in control verb constructions.
  * Added empty nodes to enhanced graphs (but orphans are just converted to dep).
  * Improved conversion of Pred_Sub, Pred_Obj, Pred_Adj, Pred_Adv, Pred_Atr.
* 2019-11-15 v2.5
  * The existing data underwent full review of syntactic information based on improved guidelines to enhance annotation quality.
  * Added new data: scientific abstracts and reviews, additional administrative texts.
  * Jablonskis tagset is used instead of the MULTEXT-East tagset in the XPOS column.
* 2019-05-15 v2.4
  * Initial UD release.


<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.4
License: CC BY-SA 4.0
Includes text: yes
Parallel: no
Genre: news nonfiction legal fiction
Lemmas: manual native
UPOS: converted from manual
XPOS: manual native
Features: converted from manual
Relations: converted from manual
Contributors: Utka, Andrius; Rimkutė, Erika; Bielinskienė, Agnė; Kovalevskaitė, Jolanta; Boizou, Loïc; Aleksandravičiūtė, Gabrielė; Brokaitė, Kristina; Zeman, Daniel; Perkova, Natalia; Griciūtė, Bernadeta
Contributing: elsewhere
Contact: semantikalt@gmail.com, andrius.utka@vdu.lt, zeman@ufal.mff.cuni.cz
===============================================================================
</pre>
