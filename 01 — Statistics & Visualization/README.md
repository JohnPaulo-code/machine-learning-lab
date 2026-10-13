# 01 — Statistics & Visualization

**Course:** Machine Learning Lab — Exercise Sheet 01
**Topic:** Descriptive statistics, histograms, correlation from scratch
**Status:** ✅ Complete

## Overview
Analyzed a dataset of individuals' weights and heights: computed descriptive statistics, visualized distributions, and implemented Pearson correlation using only basic NumPy operations.

## Key Techniques
- Mean & standard deviation (NumPy)
- Histogram plotting (Matplotlib)
- Pearson correlation implemented from scratch

## Files
| File | Description |
|------|-------------|
| `Paulo - 1747579 - Exercice 1.ipynb` | Full analysis and plots |
| `data/heights_weights.csv` | Input dataset |

## Results
- Mean & std computed for both `weight` and `height` columns
- Distributions visualized as histograms
- Correlation between height and weight computed manually (no `np.corrcoef`)

## How to Run
```bash
pip install -r ../requirements.txt
jupyter notebook exercise01.ipynb
