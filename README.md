# How to install gridencoder

1. create conda environment `conda create -n name python=3.7`
2. install dependencies within conda environment : `conda activate ... ; pip install -r requirements.txt`
3. install package `pip install -e .`

Note that your CUDA version on your machine should match the CUDA version used to compile pytorch.

- If you have CUDA 11.8 (not recommended anyway) replace `+cu121` with `+cu118` with an appropriate torch version (find here: https://download.pytorch.org/whl/torch/) . Use C++17 
- try to use torch>2.0, CUDA 12.1+ 
- installation should be fairly simple
