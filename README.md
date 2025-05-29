# Network Analysis of Movie and Actor Relationships on IMDb

This repository stores all relevant pieces of code and analysis related to the Network Science course project. The authors of the project are all from the Data Science Masters curriculum at the Tartu University: Markus Rene Pae, Desiree Himuškin, and Toomas Kangur.

Our initial analysis work was spread into separate notebooks and the final `analysis_final.ipynb` was obtained by merging some of the best results. If you wish to recreate our analysis, feel free to follow the steps below. In case you have any questions, feel free to contact the repository owner. Good luck!

# Project Structure

The basic project structure should look like this.

```
imdb-duckdb-local/
├── data/
│   ├── name.basics.tsv
│   ├── title.akas.tsv
│   ├── title.basics.tsv
│   ├── title.crew.tsv
│   ├── title.episode.tsv
│   ├── title.principals.tsv
│   └── title.ratings.tsv
├── analysis_final.ipynb
├── setup.ipynb
├── eric roberts ego graph.PNG
├── star power top5 graph.PNG
├── project_poster.png
├── final_report.pdf
├── README.md
└── requirements.txt
```

The repo does not contain the .tsv files as they are too large. You should download them from [HERE](https://datasets.imdbws.com/), unzip the downloads and copy them to the data/ folder.

## Installation Steps

Create a virtual environment:

```bash
python -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

# Setup notebook

By running all cells in `setup.ipynb`, you will create a DuckDB schema with 7 tables.

# Analysis notebook

After completing the setup, you should proceed to `analysis_final.ipynb` and see what we have done.
