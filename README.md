# GIS-Project
Spatial data analysis using Python

## 1. Software Installation
To run the code, both Git and Conda need to be installed on your computer. <br>
The Git installer can be downloaded from the official website for your operating system: https://git-scm.com/downloads <br>
To install Conda, Anaconda can be downloaded from the official website: https://www.anaconda.com/download/success. <br>
Jupyter Notebook is included as part of the Anaconda distribution.

## 2. Clone the Project Repository
Open Anaconda Prompt. Navigate to the desired directory using the cd command, then clone the repository. For example, <br> 
```bash
cd C:\Users\YourUsername\Documents\ GIS-Project
```
Then run the following command:
```bash
git clone https://github.com/chaoxiadeng24-crypto/GIS-Project
```
This will download the repository to your computer.

## 3. Set Up the Conda Environment
After successfully cloning the repository, a Conda environment can be created to work on the project by using the provided environment.yml file. <br> 
If using Anaconda Navigator, select "Import" from the bottom of the Environments panel to create the environment. <br>
Alternatively, navigate to the project directory and run the following commands in Anaconda Prompt to create the environment: <br>
```bash
cd GIS-Project
conda env create -f environment.yml
```

## 4. Run the Project 
In Anaconda Navigator, launch JupyterLab and navigate to the folder containing the project files. Ensure that the GIS-Project environment is activated. <br>
Alternatively, in Anaconda Prompt, navigate to the project directory and activate the environment using command: <br>
```bash
conda activate gis-project
```
Then launch Jupyter Lab:
```bash
jupyter lab
```
This will open a web browser displaying the contents of the current directory. <br>
Open the notebook file (Landcover_Population_Analysis.ipynb) and run all cells from top to bottom.

