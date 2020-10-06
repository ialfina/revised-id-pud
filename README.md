# The Revised UD Indonesian PUD Treebank
**(Korpus Gold Standard Dependency Treebank dalam Bahasa Indonesia)**

We proposed revisions to [UD Indonesian PUD Treebank](https://github.com/UniversalDependencies/UD_Indonesian-PUD) provided by Universal Dependencies (UD) so that it conforms to Indonesian grammar.

## Revision 2.0
Last update: October 6th, 2020

### Change log:
* adding lemma
* adding features (13 features, 25 feature tags)
* revising compound word annotations
  * removed _compound:prt_
  * UPOS correction for compound words
  * used _compound:v, compound:a, compound:n_  again
* revising word segmentation for words ended with clitic _-nya_, especially for predicate nominalisation cases
* revising annotations of multiword token, especially for words ended with clitic  _-nya_ or particles  _lah/kah/pun_, including revising the annotation for _**SpaceAfter=No**_
* changed the UPOS of personal pronouns for possessiveness from DET to PRON
* _nmod:npmod_ used only for locative nouns, for other cases nmod is used.
* renamed _flat:range_ to just _flat_.

### Contributors: 
* Designing Indonesian annotation guidelines: Ika Alfina, Daniel Zeman, and Arawinda Dinakaramani
* Annotators: Ika Alfina, Arawinda Dinakaramani, Muhammad Yudistira Hanifmuti, Jessica Naraiswari Arwidarasti, Yogi Lesmana Sulestio

### Annotation Guidelines
The short annotation guidelines for this revision can be found on [UD website](https://universaldependencies.org/id/index.html).

## Revision 1.0
Last update: August, 2019

### Change log:
* revising tokenization (major revision, especially reduplicated words)
* revising UPOS (major revision)
* propose changes to language specific dependency relation for Indonesian
* revising syntactic annotation (major revision)

### Contributors: 
* Ika Alfina 
* Arawinda Dinakaramani

### Reference
The details of why and how we revised the treebank was explained in our paper below.

* Ika Alfina, Arawinda Dinakaramani, Mohamad Ivan Fanany, and Heru Suhartanto. ["**A Gold Standard Dependency Treebank for Indonesian**"](https://waseda.repo.nii.ac.jp/?action=repository_action_common_download&item_id=48059&item_no=1&attribute_id=101&file_no=1). In The 33rd PACLIC (Pacific Asia Conference on Language, Information and Computation) 2019. 

If you use our revised treebank, please cite that publication.
