<img src="https://github.com/RRP-Reading-the-Sources-DH/.github/blob/main/profile/rrp-logo-teal-bg.png" alt="RRP logo" width="420" align="left"/>

*A digital corpus of 16th-century commentaries on the exegesis of Paul, from the SNSF project 16th Century Exegesis of Paul.*

<br clear="left"/>

## Website

* Website: https://16thexegesisdh.github.io/ReformingPaul/

  > **Note:** This is a beta release. Content, structure, and features are still under development.

* Migration to TEI Publisher scheduled for **autumn 2026**.

## Project

The digital component of the project on the exegesis of Paul aims to build a corpus of commentaries dating from the 16th century.

This digital corpus will make it possible to develop specific textual analysis tools for **printed texts in Latin from the 16th century**, as well as models for the automatic processing of printed material from this period. A major digital dimension is therefore planned for this project, involving on the one hand the digitisation of a large number of printed documents, and on the other hand the computational exploitation of this data, in particular through distant reading and topic modelling.

## Funder

This project is funded by the Swiss National Science Foundation (SNSF). Project number: [207696](https://data.snf.ch/grants/grant/207696)

## Table of Contents

- [Data](#data)
- [Corpus](#corpus)
- [Models](#models)
- [Workflow](#workflow)
  - [I. Processing Pipeline](#i-processing-pipeline)
  - [II. Web Application: TEI Publisher](#ii-web-application-tei-publisher)
- [Guidelines](#guidelines)
  - [I. Segmentation](#i-segmentation)
  - [II. Transcription](#ii-transcription)
- [Documentation](#documentation)
- [Project Timeline](#project-timeline)
- [Citations](#citations)

---

## Data

The following repositories contain the XML-TEI texts from the 16th Century Exegesis of Paul project.

* **TEI-Publisher**
  - [Reading-the-Sources-App](https://github.com/RRP-Reading-the-Sources-DH/Reading-the-Sources-App)

---

* **TEI**
  - [TEI-RRP-RS](https://github.com/RRP-Reading-the-Sources-DH/TEI-RRP-RS)

---

The following repositories contain the HTR texts from the 16th Century Exegesis of Paul project.

* **HTR**
  - [HTR-Corpus-A](https://github.com/RRP-Reading-the-Sources-DH/HTR-Corpus-A)
  - [HTR-Corpus-B](https://github.com/RRP-Reading-the-Sources-DH/HTR-Corpus-B)
  - [HTR-Corpus-C](https://github.com/RRP-Reading-the-Sources-DH/HTR-Corpus-C)

---

## Corpus

| Corpus | Description | File |
|--------|-------------|------|
| **Corpus A** | Gold-standard corpus, manually corrected; used as a training dataset for the models. | [Corpus_A.csv](https://github.com/RRP-Reading-the-Sources-DH/HTR-Corpus-A/blob/main/corpus/Corpus_A.csv) |
| **Corpus B** | Bronze-standard corpus, automatically corrected; manual corrections limited to verse-level OCR. | [Corpus_B.csv](https://github.com/RRP-Reading-the-Sources-DH/HTR-Corpus-B/blob/main/corpus/Corpus_B.csv) |
| **Corpus C** | Silver-standard corpus; reviewed segmentation, corrected verse-level OCR. | [Corpus-C_priority_1_v2.csv](https://github.com/RRP-Reading-the-Sources-DH/HTR-Corpus-C/blob/main/corpus/Corpus-C_priority_1_v2.csv) |

---

## Models

* **Layout Analysis:**
  - [Repository – Segmentation-model](https://github.com/RRP-Reading-the-Sources-DH/Segmentation_model)
  - Our model _Layout-16th-Print-Lat_ is available on Zenodo: [10.5281/zenodo.18492102](https://doi.org/10.5281/zenodo.18492102)
* **HTR:**
  - Best model currently available (trained by colleagues on a subset of our data; link forthcoming)
  - Earlier model trained for the project:
    - [Repository – OCR-model](https://github.com/RRP-Reading-the-Sources-DH/OCR-model)
    - Earlier model (25.05.2024), _gallicorpora_ajust_, available on Zenodo: [10.5281/zenodo.19218113](https://doi.org/10.5281/zenodo.19218113)

---

## Citations

### Citation: Project

Ueli Zahnd, Stefan Krauter, Matteo Colombo, Floriane Goy, Benjamin Manig, Noemi Schürmann, _16th Century Exegesis of Paul_, Geneva; Zürich, Universities of Geneva and Zürich, 2023.

```bibtex
@misc{Goy_exegesisofPaul_2023,
  author={Ueli Zahnd, Stefan Krauter, Matteo Colombo, Floriane Goy, Benjamin Manig, Noemi Schürmann, Béatrice Dupuis},
  title={16th Century Exegesis of Paul},
  address={Geneva; Zürich},
  publisher={University of Geneva; University of Zürich},
  year={2023},
  url={https://www.theologie.uzh.ch/de/faecher/neues-testament/Professur-f%C3%BCr-neutestamentliche-Wissenschaft/16th_century_exegesis_of_paul.html},
  note={Grant number SNSF: 207696},
}
```

## On the Project

- Reformation Readings of Paul: [RRP](https://rrp.zahnd.be/) – database of 16th-century printed commentaries on Paul.
- In Zürich: [Exegesis of Paul](https://www.theologie.uzh.ch/de/faecher/neues-testament/Professur-f%C3%BCr-neutestamentliche-Wissenschaft/16th_century_exegesis_of_paul.html)
- In Geneva: [L'exégèse des épîtres pauliniennes](https://www.unige.ch/ihr/fr/accueil/exegese-paulinienne/)
