# Python Data Science Basics

Hands-on notebooks designed to build data science and machine learning intuition for business leaders and executives. No prior coding experience required — just run the cells.

---

## Notebooks

### From Spreadsheets to Algorithms
An end-to-end tour of the data science workflow — from raw data to a live predictive pricing tool — illustrated through an insurance dataset.

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rgarzonj/python_data_science_basics/blob/main/notebooks/from_spreadsheets_to_algorithms.ipynb)

---

### Data Science Libraries Tour
A breadth-first walkthrough of the 8 core Python libraries every data scientist uses: pandas, numpy, matplotlib, seaborn, plotly, scikit-learn, statsmodels, and PyTorch.

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rgarzonj/python_data_science_basics/blob/main/notebooks/data_science_libraries_tour.ipynb)

---

### Machine Learning Fundamentals — Executive Interactive
An interactive walkthrough of core ML concepts with decision points for the reader: supervised vs unsupervised vs reinforcement learning, overfitting, feature selection, tree algorithms, and interpretability.

> **Coming soon** — notebook will be added to the `notebooks/` folder.

---

## Running locally

Requires [Miniconda](https://docs.conda.io/en/latest/miniconda.html).

```bash
git clone https://github.com/rgarzonj/python_data_science_basics.git
cd python_data_science_basics

# Create and activate the environment
conda env create -f environment.yml
conda activate ds-basics

# Register the kernel and launch JupyterLab
python -m ipykernel install --user --name ds-basics --display-name "Python (ds-basics)"
jupyter lab
```

## Web versions

Static HTML versions (no installation required, Python runs in the browser via Pyodide) are available in the [`web_version/`](web_version/) folder.
