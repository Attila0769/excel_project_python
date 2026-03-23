# Installation : 

## Requirements 
python 3.8+ with pip

## Downloading
Download the project as .zip with gihub or if you have git : 
`git clone https://github.com/Attila0769/excel_project_python`

Create the venv environment : 
- Open a powershell terminal in the project folder :
- Run the commands :
-   `python -m venv .venv`
-   `.venv\Scripts\Activate.ps1`
-   `pip install -r requirements.txt`

Now you can run the python files without any problem with jupyter notebook, vs code with jupyter extension or any software to run .ipynb files. 

## What is all that for ?
These python scripts are meant to analyze data from a csv file exported from an Excel workbook. As this is a team project, the Excel part isn't on the Git Hub as I didn't do it. I have no rights on it. 
The scripts analyze data from a company in US that's selling furnitures across the whole country. 
One ![script](python_part.ipynb) is purely data analysis and the ![other one](analyse_remises) is focused towards data science as it tries to predict whether a discount is profitable or not.

The plots created can all be found in the folder ![plots](plots/).

![This](carte_ventes.html) shows a map of the US with the cities where the company sold the most in terms of revenue. 

### Side note

As you may see, the csv file is really short, so the model has issues predicting correctly and only have about 68% accuracy. And what makes it even less accurate is the fact that we lack data to determine if it's profitable or not AND so lack data for the model to train. So even if it has a 68% accuracy it could be lower. 

## Further possible improvements
- Add data
- Make a script so the user just enters parameters and the model decides of the discount rate.
