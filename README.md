# Cepstral_analysis_Python
 Strain mapping using cepstral transformation

We recommend using the cepstral analysis code within the Anaconda framework. It is also recommended to create a new virtual environment, follow the instructions below.
 ```
conda update conda
conda create -n cepstral
conda activate cepstral
```

Required packages - numpy, matplotlib, scipy, scikit-learn, ipympl, tqdm, opencv. These can be installed by running the following commands in the conda terminal.

 ```
conda install -c conda-forge matplotlib
conda install -c conda-forge scipy
conda install -c conda-forge ipympl
conda install -c conda-forge scikit-learn
conda install -c conda-forge tqdm
conda install -c conda-forge notebook
conda install -c conda-forge opencv
conda update --all
```

The MATLAB version of the code can be found at https://github.com/muller-group-cornell/PC-STEM. The paper introducing the exit wave power cepstrum is : E. Padgett, M. E. Holtz, P. Cueva, Y. T. Shao, E. Langenberg, D. G. Schlom, and D. A. Muller. “The Exit-Wave Power-Cepstrum Transform for Scanning Nanobeam Electron Diffraction: Robust Strain Mapping at Subnanometer Resolution and Subpicometer Precision” Ultramicroscopy 214, (2020): 112994. doi:10.1016/j.ultramic.2020.112994, Available at http://www.sciencedirect.com/science/article/pii/S0304399119303377