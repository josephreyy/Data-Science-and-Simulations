# Data Science and Simulations – Assignment 2

This repository contains materials for Assignment 2 of the *Data Science and Simulations* course. The project focuses on the comparison of molecular dynamics simulations performed with different force fields and supports both analysis work and report writing.

## Repository purpose

The repository is currently organized as a notebook-first project.  
At this stage, most of the work is stored in Jupyter notebooks, while a more formal structure with dedicated `src/`, `data/`, and `results/` folders may be added later as the project becomes more mature.

## Main working files

The primary assignment work is contained in:

- `notebooks/assignment/assignment2_main.ipynb`
- `docs/assignment/assignment2_method_clarifications.tex`
- `docs/assignment/assignment2_plan.md`

These files should be treated as the main project context.

## Repository structure

```text
ds-simulations-assignment2/
├── README.md
├── .gitignore
├── docs/
│   ├── assignment/
│   │   ├── assignment2_description.pdf
│   │   ├── assignment2_method_clarifications.tex
│   │   ├── assignment2_plan.md
│   │   └── report_outline.tex
│   └── course_materials/
│       ├── lecture_slides/
│       └── notes/
├── notebooks/
│   ├── assignment/
│   │   └── assignment2_main.ipynb
│   └── reference/
│       ├── this_course/
│       └── other_courses/
└── archive/
```

This structure separates the active assignment notebook from supplementary notebooks and background materials, which is a practical way to keep notebook-heavy repositories understandable and maintainable.

## Folder descriptions

### `docs/assignment/`
Contains assignment-specific documents, such as the task description, methodological clarification notes, project planning text, and report-related files.

### `docs/course_materials/`
Contains general background material from the course, including lecture slides and additional notes. These files are included as reference context and not as the core graded deliverables.

### `notebooks/assignment/`
Contains the main notebook used for the actual assignment work.  
Only notebooks directly relevant to the graded project should be placed here.

### `notebooks/reference/this_course/`
Contains supporting notebooks from the same course, such as demonstrations, examples, or exploratory notebooks that may help with implementation or interpretation.

### `notebooks/reference/other_courses/`
Contains notebooks from other courses that cover related topics, such as molecular dynamics workflows, RMSD/RMSF analysis, force-field-related examples, or general data analysis patterns. These notebooks are included strictly as reference material and are not part of the graded assignment itself.

### `archive/`
Contains outdated, duplicated, or experimental files that should be kept for traceability but are not part of the active workflow.

## Working principle

The assignment should be developed primarily from the files in `notebooks/assignment/` and `docs/assignment/`.  
Reference notebooks and lecture materials may be consulted for ideas, background knowledge, or implementation patterns, but they should not be treated as direct assignment instructions unless explicitly confirmed in the official assignment documents.

## Notes on repository status

This repository is still in an early working phase.  
At the moment, it mainly contains notebooks and supporting documents. If the project grows, analysis code may later be extracted into reusable Python scripts or modules, and outputs may later be organized into separate `data/` and `results/` directories.

## Suggested usage with Claude Code

When using Claude Code or other coding assistants, the following priority should be assumed:

1. Use `notebooks/assignment/assignment2_main.ipynb` as the primary working notebook.
2. Use files in `docs/assignment/` as the authoritative project context.
3. Use lecture slides and reference notebooks only as supplementary background material.
4. Do not assume that notebooks from other courses are directly applicable without checking relevance to this assignment.

## Naming conventions

Suggested naming style for notebooks:

- `assignment2_forcefield_comparison.ipynb`
- `assignment2_analysis_clean.ipynb`
- `reference_md_rmsd_rmsf_example.ipynb`
- `reference_forcefield_background.ipynb`

Clear and descriptive file names improve readability and repository navigation, especially in notebook-heavy projects.

## Future extensions

Possible future additions include:

- `src/` for reusable Python functions and analysis scripts
- `data/` for structured input files
- `results/` for exported figures, tables, and processed outputs

For now, the notebook-first structure is sufficient for the current stage of the project.
