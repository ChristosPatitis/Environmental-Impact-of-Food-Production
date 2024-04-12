# Understanding the Environmental Impact of Food Production: 
## Task: 
In this project we have collected data on food production, consumption and emissions then we alazysed these datasets trying to find patterns between food choiches and the enviromental impact of those choiches thes as a result we tried to uncover how food productions and consumption affects carbon emissions to the enviroment.
# Deliverables:

* the repository contains a Power Point presentation as pdf in which I have summarised and presented the findings from the EDA
There are also 1 Jupyter notebooks:
the notebook contains the EDA including the plots I created for the presentation

### You will need : 

Set up the Environment:

This repo contains a requirements.txt file with a list of all the packages and dependencies you will need. Before you install the virtual environment, make sure to install postgresql if you haven't done it before.

* Pandas:Installation: pip install pandas
* Matplotlib:Installation: pip install matplotlib
* Seaborn:Installation: pip install seaborn
* NumPy:Installation: pip install numpy
* Plotly Express:Installation: pip install plotly
* Geopandas: Installation: pip install geopandas

macOS type the following commands :
Install the virtual environment and the required packages by following commands:

'''pyenv local 3.11.3
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt'''
For PowerShell CLI :

'''python -m venv .venv
.venv\Scripts\Activate.ps1
pip install --upgrade pip
pip install -r requirements.txt'''
For Git-Bash CLI :

'''python -m venv .venv
source .venv/Scripts/activate
pip install --upgrade pip
pip install -r requirements.txt'''
Note: If you encounter an error when trying to run pip install --upgrade pip, try using the following command:

python.exe -m pip install --upgrade pip
