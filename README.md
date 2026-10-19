# Computational modelling for cancer: a hands-on lesson

Beginner-friendly Jupyter notebooks introducing two sides of computational cancer biology:
mechanistic tumour growth models, and data-driven discovery of cancer dependencies with DepMap.

| Notebook | Topic |
|---|---|
| `lesson1_cancer_modelling/01_tumour_growth_models.ipynb` | Exponential, logistic and Gompertz growth; drug treatment; resistance; fitting a model to data |
| `lesson1_cancer_modelling/02_finding_dependencies_depmap.ipynb` | Finding leukemia-selective gene dependencies in DepMap CRISPR screens |

## How to run (no setup)
1. Open [Google Colab](https://colab.research.google.com), choose **File > Open notebook > GitHub**, and paste this repository's URL.
2. Pick a notebook and run cells one by one with Shift+Enter.
3. For notebook 02 with real data, upload `CRISPRGeneEffect.csv` and `Model.csv` (see `data/README.md`) with the folder icon in Colab's left sidebar (or into `data/` locally). Without them, the notebook uses a clearly labelled simulated dataset.

## How to run locally
```bash
python3 -m pip install -r requirements.txt
jupyter lab
```
