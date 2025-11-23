# Assignment 01 — Introduction to Parallel Programming

Elegant, concise documentation for the Assignment 1 submission by Mst. Aysa Siddika Meem (Student ID: 2220281).

## Abstract

This folder contains the materials and reproducible code for Assignment 01 of the "Introduction to Parallel Programming" course. The work demonstrates core parallel programming techniques through a documented Jupyter Notebook and an exported PDF suitable for submission.

## Files included

- `Assignment_1_2220281_Mst_Aysa_Siddika_Meem.ipynb` — Main Jupyter Notebook with narrative, code, results and figures.
- `Assignment_1-2220281-Mst. Aysa Siddika Meem.pdf` — Clean PDF export of the notebook (submission-ready).

## Key highlights

- Carefully commented examples of parallel programming constructs covered in class.
- Reproducible experiments and measured results presented inline.
- Visualizations and a short analysis summarizing observed behavior.

## Quick setup (recommended)

Prerequisites:

- Python 3.8 or later
- Jupyter Notebook or JupyterLab

Minimal environment (Windows with Git Bash / WSL; adapt activation for other shells):

```bash
# create a venv and activate it
python -m venv .venv
source .venv/Scripts/activate

# install core tools (add extras if needed)
pip install --upgrade pip
pip install jupyter numpy matplotlib

# open the notebook
jupyter notebook "Assignment_1_2220281_Mst_Aysa_Siddika_Meem.ipynb"
```

Notes:

- Inspect the top of the notebook for any additional imports or dataset links. Install those packages as required.
- Run the notebook cells in order to reproduce results. Some experiments may be CPU-bound and take longer depending on your machine.

## Reproducibility

- To make reproducing results easier, add a `requirements.txt` or `environment.yml`. I can generate one automatically by scanning the notebook for imports if you like.
- For automated validation or CI, run the notebook headlessly with `nbconvert` or `papermill` and compare outputs.

## Suggested next steps (optional)

1. Add `requirements.txt` with pinned versions.
2. Add a short `RESULTS.md` summarizing key findings and execution time / hardware used.
3. Add a small script to run the notebook headlessly for fast verification.

## Author & contact

Mst. Aysa Siddika Meem — Student ID: 2220281

If you want this README merged into the existing `README.md` or further customized (add badges, screenshots, an abstract of results, or a generated `requirements.txt`), tell me which items to include and I will update the repository accordingly.
Feel free to reach out via email at:aysasiddikameem3141@gmail.com
Thank you for reviewing my assignment submission !
