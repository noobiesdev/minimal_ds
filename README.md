## Download Miniconda
  - https://docs.conda.io/en/latest/miniconda.html
  - conda config --set channel_priority strict
  - conda install <package-name>
## Don't set Anaconda to PATH you should just use the Anaconda Prompt Application
  - Press windows and search for "Anaconda Prompt"
## Update Anaconda
  - conda update conda
## Create "minimal_ds" Environment:
  - conda create --name minimal_ds
## Active "minimal_ds" Environment:
  - conda activate minimal_ds
## Add conda-forge As a Channel:
  - conda config --add channels conda-forge
    conda config --set channel_priority strict
    conda install <package-name>
## Add basic DS Packages:
  - conda install pandas scikit-learn matplotlib notebook statsmodels openpyxl xlrd
