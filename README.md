# Creating AI Agents

## Creating eviroenment from scratch

```bash
conda create -n agents python=3.11
conda activate agents
conda install -c conda-forge poetry
conda env export --from-history > environment.yml
```

## Creating environment from environment.yml

```bash
conda env create -f environment.yml
```