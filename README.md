# Project Structure

```plaintext
data/
│
├── raw/
│   └── hiv_2015_ors.csv              # Original raw dataset
│
└── processed/
    ├── impact_scores.csv             # Comparison between computed and actual impact scores
    └── updated_hiv_2015_ors.csv      # Dataset including all computed columns

src/
└── notebooks/
    └── HIV_2015_ORS.ipynb            # Primary processing and analysis notebook
```

# Methodology

The core logic is implemented in:

compute_impact_score_2015_dynamic()

# Usage Instructions

1. Place the raw dataset in:

data/raw/hiv_2015_ors.csv

2. Open the notebook:

src/notebooks/HIV_2015_ORS.ipynb

3. Run all cells sequentially.

4. Output files will be generated in:

data/processed/

5. Generated files:

impact_scores.csv

updated_hiv_2015_ors.csv

