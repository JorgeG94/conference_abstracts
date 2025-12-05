# Instructions 

Dear MM2025 participant,

Here are the steps to prepare your laptop for the TranSIESTA + QM/MM electrochemistry tutorial.

Please try to complete them before the workshop. If you have difficulties, we will assist you during the session.
## Step 1: Install Conda in case you don't have it already

Go to: https://www.anaconda.com/download

Create an account and verify it (check Spam folder if needed).

Download the Linux installer: 64-Bit (x86) Installer
    File name: Miniconda3-latest-Linux-x86_64.sh
    
In your terminal, run: `./Miniconda3-latest-Linux-x86_64.sh`

Follow the instructions on the screen.

## Step 2: Create and activate a Conda environment

Run in your terminal:
```bash
conda create -n siesta_env
conda activate siesta_env
```

## Step 3: Install SIESTA, Sisl, and required packages

Run:
```bash
conda install -c conda-forge "siesta=*=*openmpi*"
conda install -c conda-forge numpy pybind11 sisl plotly ipywidgets netCDF4 scikit-image pathos nodify
pip install sisl[viz]
conda install -c conda-forge notebook
```

## Step 4: Download tutorial files and test

Download: https://github.com/edefreitas1/Tutorials/raw/refs/heads/main/Electrochemistry_Tutorial.zip

Unzip the file.

Run: `jupyter-notebook run.ipynb`

Try executing the cells. This is what we will do during the tutorial.

Please try to complete these steps before the workshop for a smooth experience.
