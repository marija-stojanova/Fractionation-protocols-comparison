# Fractionation Protocols Comparison

## Overview

This project compares different soil fractionation protocols that are used to separate soil components by presumed biogeochemical stability. The main goal is to evaluate whether results obtained from one method can be harmonized or “translated” into those obtained via another method.
It accompanies the paper by Kpemoua et al. 2025.
Contact Stojanova or Barré with any inquiries regarding the code and implementations, and Kpemoua and Barré regarding the paper and fractionation protocols.

## Contents

* **paper\_notebook.ipynb** — central notebook with analyses, figures, and results.
* **data/** processed data.
* **results/** outputs and final figures.

## Objectives

1. Compare outcomes (e.g., fraction yields, composition) across multiple fractionation protocols.
2. Test whether a *transfer function* can correct or calibrate results from one protocol to match another.

## Requirements & Setup

You’ll need:

* Python ≥ 3.8
* install the required libraries in *requirements.txt*
* Jupyter or JupyterLab to run the notebook

Clone and start:

```bash
git clone https://github.com/marija-stojanova/Fractionation-protocols-comparison.git
cd Fractionation-protocols-comparison
jupyter notebook paper_notebook.ipynb
```

## Usage

1. Load the soil fractionation datasets.
2. Run the notebook cells in order to perform exploratory plots and statistical comparisons.
3. Fit and validate transfer functions mapping results between methods.
4. Apply to external data.

