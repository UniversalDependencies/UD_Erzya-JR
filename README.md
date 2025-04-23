# Summary

UD Erzya is the original annotation (CoNLL-U) for texts in the Erzya language,
it originally consists of a sample from a number of fiction authors writing originals in Erzya.

# Introduction

UD Erzya is the	original annotation (CoNLL-U) for texts	in the Erzya language. Texts will date back to the 1880s

# Acknowledgements

The original annotation has been performed by Jack Rueter at the University of Helsinki using morphological tools
facilitated at the Norwegian Arctic University in Tromsø and with continuous consultation from Francis Tyers. 
The idea and funding for the first three months of the project came from Anssi Yli-Jyrä, Research Fellow at
the Academy of Finland (dec. No 270354 - A Usable Finite-State Model for Adequate
Syntactic Complexity), who made it possible to work with Erzya UD.
Without the Erzya writers themselves, we would be no where…

Annotation work is simultaneous to finite-state transducer development by Olga Erina and Jack Rueter in the [GiellaLT](https://giellalt.uit.no/lang-myv) infrastucture, which also works with Constraint Grammar disambiguation of the morphological analysis.

If you use this data in your work, please cite:

   @inproceedings{rueter2018towards,
   title={Towards an open-source universal-dependency treebank for Erzya},
   author={Rueter, Jack and Tyers, Francis},
   booktitle={Proceedings of the Fourth International Workshop on Computational Linguistics of Uralic Languages},
   pages={106--118},
   year={2018}
   }

## References

- Anoshkin, V. (Аношкин, В.) Валскень гудок. Сятко 1936, №2 лл 44–61.
- Bryzhinski, M. I. (Брыжинский, М.И.) Кирдажт (manuscript)
- Chetvergov, E. V. (Четвергов, Е. В.) Велень вайгельть: Ёвтнемат. -- Саранск, Мордовской книжной издательствась, 1992. -- 160 с. -- Мордов./эрзя яз.
- Dunjashin, Alek (Дуняшин, Алек) Пици-палакст. Ёвтнемат ды фельетонт. -- СССР-энь Наротнэнь Центрань Издательствась, 1930.
- Erina, O. (Ерина, О.) *Частицы в мордовских языках*. -- Тарту 1997. [Dissertation.]
- Evsevʹev, M. (М. Евсевьев) Эрзянь ёвкст (скаскат). -- Москва 1928.
- Gluxov, P. (Глухов, П.) Кедровонь пештть. Ёвтнемат. 1929.
- Kutorkin, A. (Куторкин, А.) Лажныця Сура II. Роман. Мордовской Государственной Издательствась, 1967.
* 
- Nujanj Vidjaz (Нуянь Видяз) 2007. *Erzjanj Mastorontj sedejsè (Эрзянь Масторонть седейсэ)*. Имена их буссмертны : Килангонь тешкст, нурька статьят ине эрзятнеде. -- Saransk. русский и мордов.-эрзя яз.
- *Эрзянь кель, Синтакс: тонавтнемапель.* [Erzya language, syntax: reader]. //  Агафонова, Н. А.; Алёшкина, Р. А.; Беспалова, Г. Ф.; Водясова, Л. П.; Клементьева, Е. Ф.; Рябов, И. Н.; Рябова, Г. В.; Харитонова, А. М.; Цыпкайкина, В. П.; анокстазь Д. В. Цыганкинэнь ветямонзо ало. -- Саранск : Изд-во Мордов. ун-та, 2011. -- 208 с. -- На мордов.-эрзя яз.  


 In release 2.7 example sentences used in the Erzya-language grammar *Эрзянь кель, синтакс* (2011) were included. These sentences are marked with sent_id-s that contain the components `EKS:2011:page:n-th sentence:original author`. It is hoped that the inclusion of these sentences will help cover various grammatical phenomena in Erzya syntax. When refering to these sentences, we advise you also cite the original source:

- Агафонова, Н. А.; Алёшкина, Р. А.; Беспалова, Г. Ф.; Водясова, Л. П.; Клементьева, Е. Ф.; Рябов, И. Н.; Рябова, Г. В.; Харитонова, А. М.; Цыпкайкина, В. П.; Цыганкин, Д. В. (Гл. ред.) 2011: *Эрзянь кель, синтакс: тонавтнемапель.* [Erzya language, syntax: reader]. -- Саранск : Изд-во Мордов. ун-та.
- Agafonova, N. A.; Alëškina, R. A.; Bespalova, G. F.; Vodâsova, L. P.; Klement'eva, E. F.; Râbov, I. N.; Râbova, G. V.; Kharitonova, A. M.; Cypkajkina, V. P.; Cygankin, D. V. (Chief ed.) 2011: *Èrzân' kel', sintaksis: tonavtnemapel'.* [Erzya language, syntax: reader]. -- Saransk : Izd-vo Mordov. un-ta.

# Changelog

* 2025-04-30
  * Add ExtPos feature
  * Align :tmod and :lmod in advmod and obl to practice with :unmarked for alignment with issue 1028
  * remove :tcl
  * correct OrdSets, OrdMult to individual values, i.e., Ord,Sets; Mult,Ord
* 2024-11-01
  * Correct DET children
  * Add Nomzr Ag
* 2024-04-29
  * Add compound:nn
  * Replace Mood=Proh with Mood=Imp and Polarity=Neg
* 2023-10-29
  * Add CCC variant to train.conllu
* 2023-04-29
  * Work with Valency, Diminutive, present participle
* 2022-10-31
  * Grammar research input
  * Splitting into test (104518 tokens) and train (10151 tokens)
  * Migrating :lmp, :lto, :lfrom into :lmod, and :comp to :cmp
  * Existential word of negation is now adjective
* 2022-04-29
  * Deprel correction and documentation
  * Trouble shooting in dependencies
* 2021-10-31
  * Auxiliary, feature and deprel documentation
* 2021-04-29
  * Auxiliary, feature and deprel documentation
  * Language tag systematization.
  * Grammar research input.
* 2021-04-29
  * Auxiliary, feature and deprel documentation
  * Language tag systematization.
* 2020-11-15 v2.7
  * 68 new sentences added from grammar Эрзянь кель, синтакс: тонавтнемапель
  * Relator nouns with paradigms including the nominative singular are now annotated as nouns to avoid a three way coding as ADV, ADP and NOUN.
* 2020-05-15 v2.6
  * Adding more material from E. Chetvergov with direct indication of page, paragraph and sentence.
  * Expanding advmod:mmod, :lmod, :tmod and adding NameTypes.
* 2019-10-30 v2.5
   * Work has been done with AUX types including aux:neg, aux:imp, aux:cnd for dealing with what were  earlier modal particles. This work also included balancing with the beginning Moksha-JR, Komi_Permyak-UH, Skolt_Sami-Giellagas as well as the Komi_Zyrian projects and Livvi-KKPP. 
* 2019-05-15 v2.4
  * Fixed errors found by new validation tests.
* 2018-11-15 v2.3
  * Initial release in Universal Dependencies.


=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.3
License: CC BY-SA 4.0
Includes text: yes
Genre: fiction
Lemmas: converted from manual
UPOS: converted from manual
XPOS: manual native
Features: converted from manual
Relations: manual native
Contributors: Rueter, Jack; Tyers, Francis; Klementieva, Elena; Erina, Olga; Riabov, Ivan
Contributing: here
Contact: rueter.jack@gmail.com
===============================================================================
