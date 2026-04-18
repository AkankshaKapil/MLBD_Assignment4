# CSL7110 – Assignment 4: Clustering, Web Search, PageRank

**Author:** M25CSA033  
**GitHub Repository:** [https://github.com/AkankshaKapil/MLBD-Assignment4](https://github.com/AkankshaKapil/MLBD-Assignment4)  
**Date:** April 2026

---

##  Overview

This assignment implements three independent big data tasks:

1. **Clustering** – Farthest‑First (k‑center) and k‑means++ seeding on the UCI Spambase dataset.
2. **Web Search** – Inverted index search engine with stop‑word removal, punctuation handling, and plural normalisation.
3. **PageRank on Spark** – Distributed PageRank using Spark RDDs (β = 0.8, 40 iterations) on a 1000‑node graph.

All code is in the Jupyter notebook `mlbd-assignment4.ipynb`. This document explains the algorithms, assumptions, results, and how to run the code.

---

##  Repository Contents

| File | Description |
|------|-------------|
| `mlbd-assignment4.ipynb` | Complete Python notebook with all code and outputs. |
| `README.md` | This file (report + instructions). |
| `M25CSA033_CSL7110_Assignment4.pdf` | PDF version of this report (submitted to portal). |

> **Note:** Datasets and webpage files are **not** stored in the repo due to size. See instructions below.

---

##  How to Run the Notebook

### Environment
- Python 3.12+ with `pyspark` and `numpy`:
```bash
pip install pyspark numpy
