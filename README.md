# ALPHAFOLIO

### Prerequisites

1. python 3.12

2. Install pipx :

```
/usr/bin/python3.12 -m pip install pipx
```

3. Install poetry from pipx:

```
pipx install poetry
pipx ensurepath
```

4. Inject additional dependencies to poetry : [poetry-plugin-bundle](https://github.com/python-poetry/poetry-plugin-bundle) (Optional)

```
pipx inject poetry poetry-plugin-bundle
```

5. Restart vscode to take into effect

### How to run the repo

1. Optional: select python version (if multiple installed)

```
poetry env use python312
```

2. Install dependencies from poetry.lock

```
poetry install
```

3. Run project

```
poetry run
```
