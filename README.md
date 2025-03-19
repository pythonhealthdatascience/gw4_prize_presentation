# GW4 prize presentation

[![ORCID: Heather](https://img.shields.io/badge/ORCID-0000--0002--6596--3479-brightgreen)](https://orcid.org/0000-0002-6596-3479)
[![GitHub pages](https://github.com/pythonhealthdatascience//gw4_prize_presentation/actions/workflows/quarto_publish.yaml/badge.svg)](https://github.com/pythonhealthdatascience//gw4_prize_presentation/actions/workflows/quarto_publish.yaml)

Amy Heather's presentation for the GW4 Open Research Prize 2024/25 (Improving Quality category).

View at: https://pythonhealthdatascience.github.io/gw4_prize_presentation/

<br>

## 🛠️ Viewing slides locally

Clone the repository:

```
git clone https://github.com/pythonhealthdatascience/gw4_prize_presentation
cd gw4_prize_presentation
```

Set-up the environment:

```
conda env create --file environment.yaml
conda activate gw4-prize-presentation
```

Render the presentation:

```
quarto render index.qmd
```

A `requirements.txt` file is also provided (as required by the GitHub action), which can alternatively be used to set up the development environment with virtualenv, but it will not get the same Python version (the specific version used is listed in the `environment.yaml`).

<br>

## 📜 Licence

This presentation is licensed under a [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://github.com/pythonhealthdatascience/stars_wp1_summary/blob/1a7e932013abd8e4810764b8925e98e9a6473844/LICENSE) licence.

[![Licence: CC BY 4.0](https://licensebuttons.net/l/by/4.0/80x15.png)](https://creativecommons.org/licenses/by/4.0/)
[![Licence: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

<br>

## 📝 Citation

If you wish to cite this presentation, please refer to the `CITATION.cff`. As an example:

> Heather, A. (2025). Improving Reproducibility in Open Healthcare Simulation. Presentation for the GW4 Open Research Prize 2024/25 Improving Quality. https://github.com/pythonhealthdatascience/gw4_prize_presentation.

<br>

## 💰 Funding

This project is supported by the Medical Research Council [grant number [MR/Z503915/1](https://gtr.ukri.org/projects?ref=MR%2FZ503915%2F1)].