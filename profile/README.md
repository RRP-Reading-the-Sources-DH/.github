<img src="https://github.com/RRP-Reading-the-Sources-DH/.github/blob/main/profile/rrp-logo-teal-bg.png" alt="RRP logo" width="420" align="left"/>

*A digital corpus of 16th-century commentaries on the exegesis of Paul, from the SNSF project "16th Century Exegesis of Paul".*

<br clear="left"/>

## Website

> **Note:** This is a beta release. Content, structure, and features are still under development.
>
> Migration to TEI Publisher is scheduled for **autumn 2026**.

## Project

The digital component of the project on the exegesis of Paul aims to build a corpus of commentaries dating from the 16th century.

This digital corpus will make it possible to develop textual analysis tools specifically for **16th-century printed texts in Latin**, as well as models for the automatic processing of printed material from this period. A major digital dimension is therefore planned for this project, involving on the one hand the digitisation of a large number of printed documents, and on the other hand the computational exploitation of this data — in particular through distant reading and topic modelling.

## Funder

This project is funded by the Swiss National Science Foundation (SNSF). Project number: [207696](https://data.snf.ch/grants/grant/207696)

## Table of Contents

- [Data](#data)
- [Models](#ai-models)
- [Documentation](#documentation)
- [Publication](#publication)
- [Citations](#citations)
- [About the Project](#about-the-project)

---

## Data

### TEI-Publisher

The following repository contains the files for the TEI-Publisher application powering the website **RRP | Reading the Sources**.

- [Reading-the-Sources-App](https://github.com/RRP-Reading-the-Sources-DH/Reading-the-Sources-App)

### TEI

The following repository contains the XML-TEI texts from the *16th Century Exegesis of Paul* project.

- [TEI-RRP-RS](https://github.com/RRP-Reading-the-Sources-DH/TEI-RRP-RS)

### HTR

The following repositories contain the OCR data in XML/ALTO from the *16th Century Exegesis of Paul* project.

- [HTR-Corpus-A](https://github.com/RRP-Reading-the-Sources-DH/HTR-Corpus-A)
- [HTR-Corpus-B](https://github.com/RRP-Reading-the-Sources-DH/HTR-Corpus-B)
- [HTR-Corpus-C](https://github.com/RRP-Reading-the-Sources-DH/HTR-Corpus-C)

| Corpus | Quality | Segmentation | OCR |
|--------|---------|--------------|-----|
| **Corpus A** | Gold  | Full human correction | Full human correction |
| **Corpus B** | Silver | Full human correction | Human correction limited to verse-level OCR |
| **Corpus C** | Bronze | Partial human correction | Human correction limited to verse-level OCR |

---

## AI Models

**Layout Analysis:**
- [Repository — Segmentation-model](https://github.com/RRP-Reading-the-Sources-DH/Segmentation_model)
- Our model *Layout-16th-Print-Lat* is available on Zenodo: [10.5281/zenodo.18492102](https://doi.org/10.5281/zenodo.18492102)

**HTR:**
- Best model currently available (trained by colleagues on a subset of our data; link forthcoming)
- Earlier model trained for the project:
  - [Repository — OCR-model](https://github.com/RRP-Reading-the-Sources-DH/OCR-model)
  - Earlier model (25.05.2024), *gallicorpora_ajust*, available on Zenodo: [10.5281/zenodo.19218113](https://doi.org/10.5281/zenodo.19218113)

---

## Documentation

Documentation on the project's digital development, pipeline, scripts, timeline, etc.

- [Documentations](https://github.com/RRP-Reading-the-Sources-DH/Documentations)

---

## Publication

Floriane Goy, Noemi Schürmann, Benjamin Manig, Matteo Colombo, Ueli Zahnd, and Stefan Krauter. "Données et modèles pour le traitement des documents en néolatin : le cas Lambert Daneau." *Humanistica 2026*, Paris, France, Anthology of Computers and the Humanities, vol. 4, pp. 120–133, ⟨10.63744/5TcizCXUUTmJ⟩.

```bibtex
@incollection{10.63744@5TcizCXUUTmJ,
  title = {Données et modèles pour le traitement des documents en néolatin: le
cas Lambert Daneau},
  author = {Floriane Goy and Noemi Schürmann and Benjamin Manig and Matteo Colombo and Ueli Zahnd and Stefan Krauter},
  year = {2026},
  booktitle = {Actes de la Conférence Humanistica},
  publisher = {Anthology of Computers and the Humanities},
  pages = {120--133},
  editor = {Serena Crespi and Simon Gabay and Martin Grandjean and Ariane Pinche and Marie Puren and Léa Saint-Raymond},
  doi = {10.63744/5TcizCXUUTmJ}
}
```

---

## Citations

### Citation: Digital Framework

```bibtex
@misc{Goy_RRP-ReadingtheSources_2023,
  author={Floriane Goy},
  title={RRP Reading the Sources, Digital Framework},
  address={Geneva; Zürich},
  publisher={University of Geneva; University of Zürich},
  year={2023-2026},
  url={[project URL, to be added once the site is online]},
  note={Grant number SNSF: 207696},
}
```

### Citation: Project, 16th Century Exegesis of Paul

Ueli Zahnd, Stefan Krauter, Matteo Colombo, Floriane Goy, Benjamin Manig, Noemi Schürmann, *16th Century Exegesis of Paul*, Geneva; Zürich, Universities of Geneva and Zürich, 2023.

```bibtex
@misc{Goy_exegesisofPaul_2023,
  author={Ueli Zahnd and Stefan Krauter and Matteo Colombo and Floriane Goy and Benjamin Manig and Noemi Schürmann and Béatrice Dupuis},
  title={16th Century Exegesis of Paul},
  address={Geneva; Zürich},
  publisher={University of Geneva; University of Zürich},
  year={2023},
  url={https://www.theologie.uzh.ch/de/faecher/neues-testament/Professur-f%C3%BCr-neutestamentliche-Wissenschaft/16th_century_exegesis_of_paul.html},
  note={Grant number SNSF: 207696},
}
```

---

## About the Project

- Reformation Readings of Paul: [RRP](https://rrp.zahnd.be/) — database of 16th-century printed commentaries on Paul.
- In Zürich: [Exegesis of Paul](https://www.theologie.uzh.ch/de/faecher/neues-testament/Professur-f%C3%BCr-neutestamentliche-Wissenschaft/16th_century_exegesis_of_paul.html)
- In Geneva: [L'exégèse des épîtres pauliniennes](https://www.unige.ch/ihr/fr/accueil/exegese-paulinienne/)
