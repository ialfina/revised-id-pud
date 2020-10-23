# The Revised UD Indonesian PUD Treebank
**(Korpus Gold Standard Dependency Treebank dalam Bahasa Indonesia)**

We proposed revisions to [UD Indonesian PUD Treebank](https://github.com/UniversalDependencies/UD_Indonesian-PUD) provided by Universal Dependencies (UD) so that it conforms to Indonesian grammar.

## Revision 2.0
Last update: October 27th, 2020

### Change log:
* added lemma
* added features (14 features, 27 feature tags)
* revised MWE words annotation
  * removed _compound:prt_
  * UPOS correction for MWE words
* revised word segmentation
  * for words ended with clitic _-nya_, especially for predicate nominalisation cases
* revised annotations of multiword token (MWT), especially for words ended with clitic  _-nya_ or particles  _lah/kah/tah/pun_, including revising the annotation for _**SpaceAfter=No**_
* changed the UPOS:
  * of personal pronouns for possessiveness from DET to PRON
* added and removed subtypes:
  * _nmod:lmod_ used for locative nouns
  * renamed _flat:range_ to just _flat_.
  * renamed some flat tokens to flat:name (for PROPN-PROPN pairs)

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
* Ika Alfina, Daniel Zeman, Arawinda Dinakaramani, Indra Budi, and Heru Suhartanto. "**Selecting the Universal Dependencies Morphological Features for Indonesian Dependency Treebank**". In the Proceeding of the 2020 International Conference of Asian Language Processing (IALP)  in Kuala Lumpur, Malaysia, 4-6 Desember 2020. (_accepted_)
* Ika Alfina, Arawinda Dinakaramani, Mohamad Ivan Fanany, and Heru Suhartanto. ["**A Gold Standard Dependency Treebank for Indonesian**"](https://waseda.repo.nii.ac.jp/?action=repository_action_common_download&item_id=48059&item_no=1&attribute_id=101&file_no=1). In the Proceeding of 33rd Pacific Asia Conference on Language, Information and Computation (PACLIC) 2019 in Hakodate, Japan, 13-15 September 2019. 

If you use our revised treebank, please cite those publications.
