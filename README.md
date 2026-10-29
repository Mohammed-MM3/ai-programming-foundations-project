# AI Programming Foundations Project

This C2 project uses Python to audit, clean, and explore Titanic passenger records. The notebook includes reusable functions, an age-imputation sensitivity comparison, and three visualizations with saved outputs.

## Dataset

Titanic: 891 rows and 12 columns. The supplied `titanic.csv` is included beside the notebook.

[Dataset source](https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv)

## How to install

Use Python 3.12. From this project directory on Windows:

```powershell
python -m venv .venv
.venv\Scripts\python -m pip install -r requirements.txt
```

`requirements.txt` contains the five imported packages and their runtime dependencies. Notebook editor and kernel tools are installed separately below. On macOS or Linux, use `.venv/bin/python` in place of `.venv\Scripts\python`.

## How to run

```powershell
.venv\Scripts\python -m pip install notebook ipykernel
.venv\Scripts\python -m notebook data_workflow.ipynb
```

Select the environment's Python kernel, then choose **Restart Kernel and Run All Cells** and save. Run from the project directory so `titanic.csv` is found. Figures are also saved in `figures/`; the report is `module_summary.pdf`.
