# Directed evolution of drug-like Aβ conformation-specific antibodies
This repo contains the code used in the paper

This repo uses `uv` as a package manager, which can be installed following these [instructions](https://docs.astral.sh/uv/getting-started/installation/).
For Unix systems,
```
curl -LsSf https://astral.sh/uv/install.sh | sh
```
For Windows,
```
powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"
```

Create a virtual environment using:
```
uv venv
```

To setup the needed dependencies, run 
```
uv pip install -r pyproject.toml
```

The analyses and figure generation are located in `/notebooks/figures-x.ipynb`
