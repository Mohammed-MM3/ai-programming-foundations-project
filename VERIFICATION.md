# C2 delivery verification

Verified on 29 October 2026 with Python 3.12 on Windows.

- The supplied CSV contains 891 rows, 12 columns, no duplicate rows, and missingness of Age 177, Cabin 687, and Embarked 2.
- All seven notebook code cells executed successfully in a clean virtual environment. No error outputs remain. The saved notebook embeds three rendered figures and its displayed tables.
- Two cleaning functions and one exploratory analysis function are defined, applied, and documented. Assertions check important cleaning invariants.
- The first notebook cell identifies Mohammed (MM), the dataset, the project, and AI assistance. The notebook has all seven sections and ends with a narrative summary.
- The PDF has four pages, a readable text layer, all nine prescribed section headings, numbered figure interpretations, five Future Integration Reflections sentences, and APA-style in-text citations and references. Its pages were rendered and visually inspected.
- `requirements.txt` was produced using `pip freeze` only after successful notebook execution. `pip check` found no broken dependencies. Its 101 entries include the actual dependencies of modern Jupyter Notebook, rather than the brief's estimated 20–40 lines. There are no local `file:` references or unrelated model-training libraries.
- The local repository has incremental commits with explicit AI-assistance author metadata and both `main` and `development` branches. The ZIP includes `.git` so history is preserved.
- `data_workflow.html` is an additional self-contained preview of the executed notebook; `module_summary.md` is an editable report text companion.

## Measured correction to the brief

Overall-median and class/sex-median age filling do not produce different under-18 survival rates for this CSV. Both place every filled age in the adult group. They do yield different mean ages by outcome. These actual results are reported explicitly in both the notebook and report.

## Publication verified

The public repository is https://github.com/Mohammed-MM3/ai-programming-foundations-project.

Both `main` and `development` have been pushed. Unauthenticated GitHub API requests confirm public visibility and both branches. The five required files were fetched without credentials from the public raw URLs and matched the delivered copies (text line endings normalized). The PDF includes the real repository URL, and its updated layout was visually inspected.

## Before submission

Review and understand the AI-assisted implementation, adapt it as needed, and establish whether the course permits this assistance. The brief's independent-authorship requirement has not been certified.
