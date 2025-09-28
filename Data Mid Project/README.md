# Comparison of Gender in Total and Average Movie Revenue

This mini project explores the role of gender on the revenue of the IMDb Top 10,000 movies dataset. 


Gender data was sourced from: https://datasets.imdbws.com/ You may need to download the file name.basics.tsv.gz to run this project. The file may be too large to be included in the repo.

The main data set came from Kaggle: https://www.kaggle.com/datasets/moazeldsokyx/imdb-top-10000-movies-dataset

## Virtual Environment (macOS, zsh)

Follow these exact commands to create a reproducible virtual environment and run the notebook.

1) Create and activate the venv (from the project root):

```bash
cd "/Users/amyamos/my_projects/Data Mid Project"
python3 -m venv venv
source venv/bin/activate
```

2) Upgrade pip and install runtime dependencies:

```bash
pip install --upgrade pip
pip install -r requirements.txt
```

3) (Optional) Pin the current environment to `requirements.txt` for exact reproducibility:

```bash
# after activating the venv and installing packages
pip freeze > requirements.txt
git add requirements.txt
git commit -m "chore: pin dependencies"
git push origin main
```

4) (Optional) Register the venv as a Jupyter kernel so the notebook uses the same interpreter:

```bash
pip install ipykernel
python -m ipykernel install --user --name="data-mid-venv" --display-name="Data Mid Project (venv)"
```

5) Start Jupyter Lab and open `mini_project_amos.ipynb`:

```bash
jupyter lab
```

Notes:
- The `venv/` directory is intentionally ignored by git; do not add it to the repo. Instead, use `requirements.txt` to share dependencies.
- The dataset `name.basics.tsv` is large and excluded from the repository. Download it from the IMDb datasets page or place a local copy at `Data Mid Project/name.basics.tsv` before running the merge steps in the notebook.

## No API is included in this project.


## Appendix

We hope you enjoyed this comparison of revenue and actor gender.

## Author

- [Amy Amos](https://github.com/Pepper445)


## Demo

Sorry, we're not that fancy.


## Contributing

Contributions are always welcome!

See `contributing.md` for ways to get started.

Please adhere to this project's `code of conduct`.
