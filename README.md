# ND2 Nikon file processing

Based on [ND2 package](https://pypi.org/project/nd2/).

## Jupyter Lab
```
conda install mamba -c conda-forge
mamba create --name ND2_processing python=3.9 jupyterlab -c conda-forge
conda activate ND2_processing
pip install nd2 lxml
```
optional: Code Formatting Jupyter Notebooks with Black
```
mamba install -c conda-forge jupyterlab_code_formatter black isort
```
