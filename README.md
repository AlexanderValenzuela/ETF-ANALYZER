# Project Title - ETF Analyzer

## Project Description 
The objective of this project is to perform analysis on a Fintech ETF consisting of four stocks: GDOT, GS, PYPL and SQ. All the stocks daily returns were analyzed individually and as a whole.  Finally, the visualizations were deployed to a web application using the Voila library.

## Project Breakdown and Summary

- Analyze a Single Asset in the ETF - Use SQL queries with Python, Pandas and hvPlot to analyze the performance of a single asset from ETF.<br>
- Optimize Data Access with Advanced SQL Queries - Access closing prices of PYPL great than $200 and sorting out the top ten daily returns.<br> 
- Analyze the ETF Portfolio - Build the ETF portfolio by using SQL joins to combine all the data from each asset.<br>
- Deploy the notebook as a web application.

## Technologies
**Python Libraries**

`python 3.9.12`<br>
`pandas 1.4.2`<br>
`Path 16.2.0`<br>
`numpy 1.21.5`<br>
`sqlalchemy 1.4.32`<br>
`hvplot 0.73`<br>
`voila 0.4.0`

## Installation Guide

[Install anaconda](https://www.anaconda.com/download/)

To clone and run this application, you'll need Git installed on your computer.
From your command line:
```
#Create a new conda environment
conda create -n dev python=3.7 anaconda

#Activate the new environment with the following command
conda activate dev

# Install dependencies in conda environment
pip install jupyter lab
conda install -c pyviz hvplot geoviews
pip install SQLAlchemy
conda install -c conda-forge voila

# Clone this repository
git clone https://github.com/AlexanderValenzuela/ETF-Analyzer

# Activate conda environment
conda activate dev

# In the conda environment, run Jupyter Lab
jupyter lab 

# Browse to the ETF-Analyzer directory and launch `etf_analyzer.ipynb`
```

## Usage

> Deploy Jupyter Notebook as a Web Application via the Voila Library

 1. In Terminal, browse to the web application, `etf_analyzer.ipynb`.  
 2. Activate conda development, `conda activate dev`.
 3. Deploy the web application, `voila etf_analayzer.ipynb`.
 ![Screenshot 2023-05-01 at 11 51 27 PM](https://user-images.githubusercontent.com/111409358/235600048-d5ffd897-ef61-4322-ade7-71b12c7f9095.png)
 
 4. The web application file, etf_analayzer.ipynb, is shown in the Jupyter notebook. 
![Screenshot 2023-05-02 at 12 04 10 AM](https://user-images.githubusercontent.com/111409358/235601397-00d7da8b-00c2-48ef-9adb-fd587ffe7681.png)
 
 5. *Analyze a Single Asset in the Fintech ETF* - PYPL daily returns and cumulative returns.<br>
![Screenshot 2022-11-13 at 9 23 33 PM](https://user-images.githubusercontent.com/111409358/201625631-d18c8cb2-92f6-4d16-869e-a1c336d82fd9.png)
![Screenshot 2023-05-02 at 1 02 49 AM](https://user-images.githubusercontent.com/111409358/235615050-f367888e-757a-4992-94a2-415088b375e2.png)

 6. *Optimize the SQL Queries* - SQL query result read into a Pandas dataframe for closing prices for PYPL greater than $200.<br>

![Screenshot 2023-05-02 at 1 16 02 AM](https://user-images.githubusercontent.com/111409358/235615127-23dc9ace-c11c-43f7-99de-3da4735c0ea3.png)


 Continuation of an SQL query result read into a Pandas dataframe for closing prices for PYPL greater than $200 and an SQL query for top 10 PYPL daily returns read into a Pandas dataframe and an SQL query for inner joined tables of GDOT, GS, PYPL and SQ, read into a Pandas dataframe.
 ![Screenshot 2022-11-13 at 9 24 33 PM](https://user-images.githubusercontent.com/111409358/201626117-aa0f575c-8dff-445f-b7f4-c91a5baa94f4.png)
 
Continuation of SQL query for inner joined tables of GDOT, GS, PYPL and SQ, read into a Pandas dataframe and ETF portfolio returns.<br>                    7. *Analyze ETF Portfolio* - ETF portfolio returns, annualized ETF portfolio returns and ETF cumulative returns. 
![Screenshot 2022-11-13 at 9 24 55 PM](https://user-images.githubusercontent.com/111409358/201626140-cccf3374-ae3e-4534-b1d3-2397598482e2.png)

Visualization of ETF portfolio cumulative returns.
![Screenshot 2022-11-13 at 9 25 22 PM](https://user-images.githubusercontent.com/111409358/201626164-cccd0cb2-edad-4c2f-aee4-c7a512c75fe2.png)

## CREDITS
- Data Team<br>
- Fintech Team<br>
- Product Development<br>
- Web Development<br>
- Alexander Valenzuela<br>
[LinkedIn Profile](<https://www.linkedin.com/in/alex-valenzuela-97826842/>)

## LICENSE
Licensed under the MIT License




















