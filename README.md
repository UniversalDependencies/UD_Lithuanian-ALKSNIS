# Summary

The Lithuanian dependency treebank ALKSNIS.

# Introduction

This is a conversion of the ALKSNIS treebank to Universal Dependencies.
The original treebank was annotated in a style derived from the Prague Dependency Treebank of Czech.
The original treebank is available in the CLARIN LT repository at
[http://hdl.handle.net/20.500.11821/10](http://hdl.handle.net/20.500.11821/10).
(Some users experience DNS errors when trying to access the repository;
configuring the client machine to use 8.8.8.8 as the DNS server may help.
See also [http://clarin-lt.lt/?page_id=86](http://clarin-lt.lt/?page_id=86).)

ALKSNIS v2 consists of 2,355 syntactically annotated sentences.
Each node of a tree corresponds to a word, a punctuation mark or other text
element (symbol, digit etc.) within a sentence. The following information is
presented for each node: 1) a used form; 2) a lemma; 3) a morphology tag,
and 4) a syntactic function (subject, object, etc.). Dependencies are shown
by links between words.

<!--The morphology tag set Jablonskis is used in ALKSNIS v2.2 and in the XPOS
column of the UD conversion. This is a change from ALKSNIS 2 where a version
of the MULTEXT-East tag set was used-->
A version of the MULTEXT-East
(http://nl.ijs.si/ME/V4/msd/html/index.html)
tag set is used in ALKSNIS v2 and in the XPOS column of the UD conversion.
Syntactically annotated sentences
are corrected according to guidelines that were created by scientists of
VMU CCL, following rules of Prague Dependency Treebank. All the sentences are
being manually checked and corrected by a group of linguists.

# Acknowledgements

## References

* Agnė Bielinskienė, Loïc Boizou, Jolanta Kovalevskaitė, Erika Rimkutė (2016): Lithuanian Dependency Treebank ALKSNIS.
  In: I. Skadiņa and R. Rozis (Eds.): Human Language Technologies – The Baltic Perspective, pp. 107–114. Amsterdam: IOS Press.
  doi:10.3233/978-1-61499-701-6-107
  [http://fcim.vdu.lt/~erika_rimkute/straipsniai/Alksnis_HLT.pdf](http://fcim.vdu.lt/~erika_rimkute/straipsniai/Alksnis_HLT.pdf),
  [http://ebooks.iospress.nl/volumearticle/45523](http://ebooks.iospress.nl/volumearticle/45523).


# Changelog

* 2019-05-15 v2.4
  * Initial UD release.


<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.4
License: CC BY-SA 4.0
Includes text: yes
Genre: news nonfiction legal fiction
Lemmas: manual native
UPOS: converted from manual
XPOS: manual native
Features: converted from manual
Relations: converted from manual
Contributors: Rimkutė, Erika; Bielinskienė, Agnė; Kovalevskaitė, Jolanta; Boizou, Loïc; Aleksandravičiūtė, Gabrielė; Brokaitė, Kristina; Zeman, Daniel
Contributing: elsewhere
Contact: zeman@ufal.mff.cuni.cz
===============================================================================
</pre>
