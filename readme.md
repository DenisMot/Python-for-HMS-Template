# A minimal template for data analysis with python 

This is a minimal template for data analysis with python.  
It is intended to researchers in human movement sciences that are new to python.   
Cloning this template for each new data analysis problem should facilitate data analyses with python and minimize potential errors.   

## Usage (without Git)
1. Download as a zip file (button `< > Code` next to the green button `Use this template`)
1. Expand the archive on your computer (e.g., in your `Download` folder). 
1. Rename the extracted folder with the name of your new project (e.g., `ECG_analysis`)
1. Move the new `ECG_analysis` folder where it should be located (e.g., in your `Documents/CodeProjects/` directory)
1. In VSCode :
    1. open the new project in a new window. 
    1. open `main.ipynb` and click `Run all`


## Data analysis with python 
The logic is to organize the data, code and results in separate folders, with everything inside the `Project-Folder`. The minimal structure is as follows:   

    Project-Folder
       ├── readme.md     # description of the project 
       ├── data          # data used as input in the project  
       ├── results       # results of the analyses 
       ├── notebooks     # analyses with jupyter notebooks 
       └── main.ipynb    # entry point: to run all analyses 

## Install python on your laptop 
Before using this template, you need to install python on your laptop.

### Minimal install 
The minimal requirements to start with a human movement analysis project are :  
- `python` : the language 
  - `numpy` and `matplotlib` : the python packages for scientific data analyses
  - `ipykernel`: to run jupyter notebooks mixing python and markdown blocks 
- `VSCode` : the development environment (editor, debugger...)  
- `conda` : the environment to manage your python environment 

#### Install python 
We here use `miniconda` to get a minimal python install (https://conda.io/miniconda.html). You will need approximately 2.5 GB of free space on your hard drive to install all the needed tools.
- Install `miniconda` 
    - Download the **Latest Miniconda Installer** appropriate for your computer (Mac users: prefer the `pkg` version)
    - Install `miniconda`, accepting all defaults 
- Check you installation 
    - Open a shell window (shell is here a generic term for `Terminal` on Macs and `Powershell` on Windows)
        1. The shell prompt should look like: 
        `(base) `userName`@`computerName` `currentDirectory `%`  
        (e.g., `(base) denismottet@MacBook-Pro-de-Denis % `  )  
        The prefix `(base) ` indicates that conda has activated the `base` environment automatically (default miniconda behavior). 

        1. At the shell prompt, ask where is the python software located  
        i.e., type  `which python` (Terminal) or `where python` (Powershell). The answer should be :   
        youHomeDirectory`/miniconda3/bin/python `  (Terminal)   
        youHomeDirectory`\miniconda3\bin\python `  (Powershell) 
- If you do not get the previous results :
    - double check the options you selected when installing `miniconda`
    - double check the version of the installer you have chosen 

### Install VSCode 
VSCode is a development environment well suited for python. 
- Install `VSCode` 
    - download the appropriate version for you computer from https://code.visualstudio.com/
    - install `VSCode`, accepting all defaults
- Open `VSCode` and install the required extensions for python
    - `VS Code Python extension`, to edit,run and debug the python code. 
    - `Jupyter Extension for Visual Studio Code`, to edit,run and debug the jupyter notebooks. 

### Install the required python packages
The goal is to install the packages in the `base` environment (i.e., your default python environment).  
Open a shell window to run the install commands
- install numpy, to manipulate data series and matrices
    - `conda install numpy`
- install matplotlib, to plot data
    - `conda install matplotlib`
- install ipykernel and nbformat, to run jupyter notebooks in VSCode
    - `conda install ipykernel nbformat`
