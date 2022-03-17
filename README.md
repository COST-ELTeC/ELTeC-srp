[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3524056.svg)](https://doi.org/10.5281/zenodo.3524056)

# ELTeC-srp

This is the Serbian novel collection for the ELTeC, the European Literary Text Collection, produced by the COST Action Distant Reading for European Literary History (CA16204, https://distant-reading.net).

## Level 1

### Release notes
General information about ELTeC releases is available at https://github.com/COST-ELTeC/ELTeC.

* v0.9.0, April 2021: This release contains 90 novels encoded at level 1. DOI: https://doi.org/10.5281/zenodo.4662604. 
* v0.7.0, November 2020: This release contains 67 texts encoded at level 1. DOI: https://doi.org/10.5281/zenodo.4271662. 
* v0.3.0, October 2019: The ELTeC-srp collection as it stands contains 30 novels encoded at level 1. The corpus composition criteria are not yet fully fulfilled.

### Contributors

* Collection editor: Cvetana Krstev, JeRTeH & University of Belgrade;
* Contributors: Ranka Stanković, JeRTeH & University of Belgrade; Aleksandra Trtovac, Vasilije Milnović, University Library “Svetozar Marković”; volunteers of Jerteh (Society for Language Resources and Technologies - http://jerteh.rs/), the most active Duško Vitas and Ivan Obradović;
* Sources: University Library “Svetozar Marković”, National Library of Serbia, "Matica srpska" Library, Library of SASA, Library of Serbian Literature Department at the Faculty of Philology UB, private library Cvetana Krstev & Duško Vitas

### Citation suggestions

* Trtovac, A., Milnović, V., & Krstev, C. (2021). The Serbian Part of the ELTeC - from the Empty List to the 100 Novels Collection. *Infotheca - Journal For Digital Humanities*, 21(2), 7-25. doi:10.18485/infotheca.2021.21.2.1

```
@article{IJDH,
	author = {Aleksandra Trtovac and Vasilije Milnović and Cvetana Krstev},
	title = {The Serbian Part of the ELTeC - from the Empty List to the 100 Novels Collection},
	journal = {Infotheca - Journal for Digital Humanities},
	volume = {21},
	number = {2},
	year = {2021},
	issn = {2217-9461},	
	pages = {7--25},
  	doi = {10.18485/infotheca.2021.21.2.1},
	url = {https://infoteka.bg.ac.rs/ojs/index.php/Infoteka/article/view/2021.21.2.1_en}
}
```

* Krstev, C. (2021). The Serbian Part of the ELTeC Collection Through the Magnifying Glass of Metadata. *Infotheca - Journal For Digital Humanities*, 21(2), 26-42. doi:10.18485/infotheca.2021.21.2.2

```
@article{IJDH,
	author = {Cvetana Krstev},
	title = {The Serbian Part of the ELTeC Collection Through the Magnifying Glass of Metadata},
	journal = {Infotheca - Journal for Digital Humanities},
	volume = {21},
	number = {2},
	year = {2021},
	issn = {2217-9461},	
	pages = {26--42},	
	doi = {10.18485/infotheca.2021.21.2.2},
	url = {https://infoteka.bg.ac.rs/ojs/index.php/Infoteka/article/view/2021.21.2.2_en}
}
```

## Level 2

### Description

* Tokanization and sentence segmentation was performed with Unitex corpus processing suite (https://unitexgramlab.org/);
* UD morphosyntactic tagging and lemmatisation with Treetagger model trained for Serbian (http://obrada.jerteh.rs/) and integrated into TXM tool (http://textometrie.ens-lyon.fr/), 
* Named entity tagging with SrpNER implemented in Unitex (http://ner.jerteh.rs/), 
* The output of SrpNER was simplified and mapped to ELTEC NER tagset described in the Annotation guidelines for ELTEC NER using NER & Beyond (http://nerbeyond.jerteh.rs/).

### Contributors

* Annotation leader: Ranka Stanković, JeRTeH & University of Belgrade;
* Contributors: Cvetana Krstev, Mihailo Škorić, Branislava Šandrih Todorović, Milica Ivković Nešić, JeRTeH & University of Belgrade.

### Citation suggestions

* Stanković, R., Krstev, C., Šandrih Todorović, B., & Škorić, M. (2021). Annotation of the Serbian ELTeC Collection. *Infotheca - Journal For Digital Humanities*, 21(2), 43-59. doi:10.18485/infotheca.2021.21.2.3

```
@article{IJDH,
	author = {Ranka Stanković and Cvetana Krstev and Branislava Šandrih Todorović and Mihailo Škorić},
	title = { Annotation of the Serbian ELTeC Collection},
	journal = {Infotheca - Journal for Digital Humanities},
	volume = {21},
	number = {2},
	year = {2022},
	issn = {2217-9461},	
	pages = {43--59},	
	doi = {10.18485/infotheca.2021.21.2.3},
	url = {https://infoteka.bg.ac.rs/ojs/index.php/Infoteka/article/view/2021.21.2.3_en}
}

```

* Stanković, R., Šandrih, B., Krstev, C., Utvić, M., & Skoric, M. (2020, May). Machine Learning and Deep Neural Network-Based Lemmatization and Morphosyntactic Tagging for Serbian. In *Proceedings of The 12th Language Resources and Evaluation Conference* (pp. 3954-3962).

```
@inproceedings{stankovic2020machine,
  title={Machine Learning and Deep Neural Network-Based Lemmatization and Morphosyntactic Tagging for Serbian},
  author={Stanković, Ranka and Šandrih, Branislava and Krstev, Cvetana and Utvić, Miloš and Škorić, Mihailo},
  booktitle={Proceedings of The 12th Language Resources and Evaluation Conference},
  pages={3954--3962},
  year={2020}
}
```

* Krstev, C., Obradović, I., Utvić, M., & Vitas, D. (2014). A system for named entity recognition based on local grammars. *Journal of Logic and Computation*, 24(2), 473-489.

```
@article{krstev2014system,
  title={A system for named entity recognition based on local grammars},
  author={Krstev, Cvetana and Obradović, Ivan and Utvić, Miloš and Vitas, Duško},
  journal={Journal of Logic and Computation},
  volume={24},
  number={2},
  pages={473--489},
  year={2014},
  publisher={OUP}
}
```

## Licence

All texts included in this collection are in the public domain. The textual markup is provided with a Creative Commons Attribution International 4.0 licence (CC BY, https://creativecommons.org/licenses/by/4.0/).

