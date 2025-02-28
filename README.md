### Environment setup
Using micromamba you should be able to read the environment.yaml file as `micromamba env create -f environment.yaml`.

You should then be able to activate the environment with `micromamba activate rsas_env`.

Then, packages can be added with `micromamba install -c conda-forge x`

Finally, the environment can be exported with `micromamba env export > environment.yaml`

Instructions for installing micromamba are here: https://mamba.readthedocs.io/en/latest/installation/micromamba-installation.html

### Linting
This project uses ruff to lint. Make sure `ruff check` returns no errors before making a pull request

### Using APIs
API keys should be read from your environment variables, and can be added to the program via the constants.py file