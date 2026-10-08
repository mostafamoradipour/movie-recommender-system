# Movie Recommender System

A notebook-based movie recommendation project that explores content-based recommendations using textual movie metadata. The project uses TF-IDF features and cosine similarity to identify movies with similar descriptions and attributes.

## Notebooks

- `features.ipynb`: feature preparation and exploration.
- `tmdb_movie.ipynb`: TMDB movie-data analysis and recommendation workflow.

## Data

The notebook workflow is built around TMDB movie metadata, including fields such as genres, keywords, and overview text. The dataset itself is not listed among the repository's tracked root files. Obtain the data from its source and follow the input paths and column names used in the notebooks.

## Requirements

The repository includes `requirements.txt`. Install dependencies in a virtual environment:

```bash
python -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip
pip install -r requirements.txt
```

## Run

Start Jupyter from the repository root and open the notebooks:

```bash
jupyter lab
```

Execute cells in order. The recommender workflow uses TF-IDF vectorization and cosine similarity; recommendation results depend on the dataset and preprocessing choices in the notebook.

## Limitations

This repository provides an exploratory notebook workflow rather than a packaged application or command-line recommender. No benchmark or recommendation-quality metrics are claimed here.

## License

No license file is currently listed. Respect the applicable terms for the source dataset and contact the repository owner before reusing or redistributing this code.
