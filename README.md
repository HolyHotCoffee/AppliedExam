# Applied Machine Learning Exam (DS807) — Problem 1 & Problem 2

**One-liner:** Exam tasks → implemented ML solutions (notebook + Python scripts) → clear, reviewable structure.

## Why it matters
This repo shows how I structure and implement applied ML solutions under exam constraints: data preprocessing, model design, evaluation, and clear separation of tasks.

## Data
- **Source:** Provided as part of the DS807 exam (see `DS807_Exam24.pdf`).
- **Sharing constraints:** The original exam dataset is not included in the repository.
- **Reproduce locally:** Place the exam data files according to each problem’s README (see `Problem1/README.md` and `Problem2/README.md`).

## Method
- **Problem 1**
  - Data utilities: `Problem1/data.py`
  - Model code: `Problem1/models.py`
  - Main analysis: `Problem1/main.ipynb`
- **Problem 2**
  - Entrypoint: `Problem2/main.py`
  - Preprocessing: `Problem2/data_preprocessing.py`
  - Models: `Problem2/modelClass.py` and `Problem2/shallow_learning.py`
  - Visualization: `Problem2/visualization.py`

## Results
- Results/figures are produced when running the notebook/script locally.
- No results are committed to the repository.

## Repo structure
```text
.
├── DS807_Exam24.pdf
├── Problem1/
│   ├── README.md
│   ├── data.py
│   ├── models.py
│   └── main.ipynb
├── Problem2/
│   ├── README.md
│   ├── main.py
│   ├── data_preprocessing.py
│   ├── modelClass.py
│   ├── shallow_learning.py
│   └── visualization.py
└── README.md
