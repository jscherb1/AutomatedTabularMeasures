# AutomatedTabularMeasures
Demo project to create tabular measures using python

# Initial Setup
Assumptions: 
- You have Visual Studio installed with all necessary extensions for Analysis Services projects
- You have SSMS installed and can run a local version of Analysis Services Server
- You have SSDT (SQL Server Data Tools) installed for SSMS
- You have Python 3.7 installed and can run Jupyter Notbeooks
- A working knowledge of tabular models and Python

## Tabular Model
### Refreshing existing tabular model
Using Visual Studio you can open the "TestTabular" Analysis Services solution.

In the solution explorer you can deploy the model to your localhost

Note: if you want to refresh the data, you'll need to modify the data source in the model to repoint to the "Orders" table that exists in the Data folder of this repo.

## Python Script
You should be able to clone this repository and run the script to generate new measures.

## Power BI
The Power BI file should be pointing to your localhost analysis services instance. Just be sure you have deployed the Tabular model solution to your localhost before connecting.

After you run the python script, deploy the model again, refresh the Power BI report and you should see the new measures.
