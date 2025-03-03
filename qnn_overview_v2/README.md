## A simple quantum model creation in PennyLane+PyTorch
- **Author:** Jacob Cybulski ([website](https://jacobcybulski.com/))
- **Aims:** *To explore the creation and use of a simple model in PennyLane and PyTorch.*
- **Start Date:** Oct 1, 2024
- **Updates:**
  - v1.7 (Oct 1, 2024): Created
  - v1.8 (Mar 3, 2025): Updated to PennyLane v0.40.0 and PyTorch v2.6.0

### Folders
- legacy: previous versions of files dated with the time of their removal
- plots: a collection of saved plots
- rsrc: repository of useful resources, e.g. pre-processed data 
  
### Important notebooks
- pl_simple_rsrc_vX_x.ipynb (prepares data downloaded from the archive)
- pl_simple_tiny_model_vX_x.ipynb (explains QML principles using PennyLane)
- pl_simple_cclassifier_vX_x.ipynb (creates and executes a quantum model)
- pl_simple_qclassifier_vX_x.ipynb (creates and executes a classical model)
- utilities.py (various functions used in model development and use)

### Requirements
- python, version 3.11 or above
- pip install pennylane pennylane-lightning-gpu (PennyLane for GPU), needs:
  - [NVidia CUDA Toolkit and Drivers](https://developer.nvidia.com/cuda-toolkit)
  - [NVidia cuQuantum](https://developer.nvidia.com/cuquantum-sdk)
- pip install pennylane pennylane-lightning (PennyLane for CPU)
- pip install pandas scipy pillow scikit-learn matplotlib plotly (various libraries)
- install jupyter jupyterlab (running jupyter notebooks)
- install pdflatex (to plot and export some plots and tables to latex)
- pip install ucimlrepo (access to UCI data sets)
- install [PyTorch](https://pytorch.org/get-started/locally/), as per instructions

### License
This project is licensed under the [Creative Commons CC-BY](https://creativecommons.org/licenses/by/4.0/).