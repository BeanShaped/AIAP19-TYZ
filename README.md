# AIAP19-TYZ
Repo template:

project-title/
├── README.md
├── LICENSE
├── .gitignore
├── environment.yml        # conda or requirements.txt
├── /data
│   ├── raw/               # original, immutable data dumps
│   └── processed/         # cleaned, feature-engineered data
├── /notebooks
│   ├── 01_exploration.ipynb
│   └── 02_modeling.ipynb
├── /src                   # production-quality code
│   ├── __init__.py
│   ├── data.py            # data loading & cleaning functions
│   ├── features.py        # featurization
│   ├── models.py          # model training & persistence
│   └── evaluate.py        # scoring & plots
├── /reports
│   └── figures/           # generated plots
├── /tests                  # pytest unit tests for your functions
└── setup.py or pyproject.toml  # if you want to pip-install your code

