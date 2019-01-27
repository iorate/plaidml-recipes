# PlaidML Recipes
Recipes to create conda packages of [PlaidML](https://github.com/plaidml/plaidml).
```shell
conda install conda-build

conda config --add channels file:///path/to/anaconda/conda-bld

cd /path/to/plaidml-recipes
conda build plaidml keras plaidml-keras onnx-plaidml plaidbench

conda install plaidml-keras onnx-plaidml plaidbench
```
