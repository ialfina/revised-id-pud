# The Revised UD Indonesian PUD Treebank
**(Korpus Gold Standard Dependency Treebank dalam Bahasa Indonesia)**

We proposed revisions to [UD Indonesian PUD Treebank](https://github.com/UniversalDependencies/UD_Indonesian-PUD) provided by Universal Dependencies (UD) so that it conforms to Indonesian grammar.

**Note: We donated this dataset to UD in 2020 and will maintain the dataset on the [UD repository](https://github.com/UniversalDependencies/UD_Indonesian-PUD/tree/master). Hence, the newest version of the dataset can be found there.

# Documentation

The short annotation guidelines for this revision can be found on the [UD website](https://universaldependencies.org/id/index.html).

# Changelog
* 2020-10-27 v2.0
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
   
* 2019-08-17 v1.0
  * revised tokenization (major revision, especially reduplicated words)
  * revised UPOS (major revision)
  * proposed changes to language specific dependency relation for Indonesian
  * revised syntactic annotation (major revision)

# Acknowledgments


## Contributors of Revision v2.0: 
* Designing Indonesian annotation guidelines: Ika Alfina, Daniel Zeman, and Arawinda Dinakaramani
* Annotators: Ika Alfina, Arawinda Dinakaramani, Muhammad Yudistira Hanifmuti, Jessica Naraiswari Arwidarasti, Yogi Lesmana Sulestio

## Contributors of Revision v1.0:
* Ika Alfina 
* Arawinda Dinakaramani

## Reference
* Ika Alfina, Daniel Zeman, Arawinda Dinakaramani, Indra Budi, and Heru Suhartanto. "**Selecting the UD v2 Morphological Features for Indonesian Dependency Treebank**". In the Proceeding of the 2020 International Conference of Asian Language Processing (IALP)  in Kuala Lumpur, Malaysia, 4-6 Desember 2020. (_accepted_)
* Ika Alfina, Arawinda Dinakaramani, Mohamad Ivan Fanany, and Heru Suhartanto. ["**A Gold Standard Dependency Treebank for Indonesian**"](https://waseda.repo.nii.ac.jp/?action=repository_action_common_download&item_id=48059&item_no=1&attribute_id=101&file_no=1). In the Proceeding of 33rd Pacific Asia Conference on Language, Information and Computation (PACLIC) 2019 in Hakodate, Japan, 13-15 September 2019. 

## Licence
You can use this dataset for free. You don't need our permission to use it. Please cite our paper if your work uses our data in your publication.
Please note that you are not allowed to create a copy of this dataset and share it publicly in your own repository without our permission.

## Contact
ika.alfina [at] cs.ui.ac.id
