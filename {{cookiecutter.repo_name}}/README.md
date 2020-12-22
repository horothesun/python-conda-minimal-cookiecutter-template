# {{ cookiecutter.project_name }}

[![CI Linux](https://github.com/{{ cookiecutter.github_username }}/{{ cookiecutter.repo_name }}/workflows/CI%20Linux/badge.svg)](https://github.com/{{ cookiecutter.github_username }}/{{ cookiecutter.repo_name }}/blob/master/.github/workflows/ci-linux.yml)

## Requirements

- Python 3
- Conda

## Environment setup

```bash
conda env update --file environment.yml
conda activate {{ cookiecutter.repo_name }}-env
```

## Test

```bash
pytest -v
```
