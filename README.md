# imdb_network

Network analysis project (spring 2025)

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
├── setup.ipynb
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

After completing the setup, you should proceed to `analysis.ipynb` and explore the dataset.
