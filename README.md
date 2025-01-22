# Creating AI Agents

## Creating eviroenment from scratch

```bash
conda create -n agents python=3.11  # Name of the environment is agents
conda activate agents
conda install -c conda-forge poetry # Dependency manager
conda env export --from-history > environment.yml # Exporting environment to environment.yml like package.json in npm
```

## Creating environment from environment.yml

```bash
conda env create -f environment.yml
```

## VSCode settings
Remember to set the python interpreter to the conda environment you created. i.e. `agents`

In the bottom left corner of the VSCode, you will see the python interpreter. Click on it and select the conda environment you created.


## Initialize poetry

Whith this command, you will create a `pyproject.toml` file which is like `package.json` in npm.

The name of the project has to be the same as the name of the folder in our case `app`

```bash
poetry init
poetry install
```

