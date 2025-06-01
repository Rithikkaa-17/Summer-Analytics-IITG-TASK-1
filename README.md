# Summer-Analytics-IITG-TASK-1
# Assignment 1: Car Dataset Analysis
# Overview
This assignment involves exploratory data analysis and visualization on the "Cars.csv" dataset. The dataset contains information about various car models, including their miles per gallon (mpg), cylinders, horsepower, weight, acceleration, model year, origin and name.

# Dataset
Filename: Cars.csv

Number of rows: 398

Number of columns: 9

Columns:

mpg

cylinders

displacement

horsepower

weight

acceleration

model_year

origin

name

# Objectives
Import and preprocess the dataset.

Perform basic data exploration:

Display shape and columns.

Set meaningful index.

Extract unique values.

Create new features (horsepower per weight ratio).

Analyze the dataset to answer specific queries:

Identify car with highest horsepower.

Count cars with mpg ≥ 35.

Find the most common origin for cars with horsepower > 100 and weight < 3000.

Calculate mean acceleration for cars from Japan.

Determine which model year had the highest average mpg.

Additional exercises include:

Finding cars with best horsepower-to-weight ratio among high mpg cars.

Visualizing average mpg trends by year and origin.

Creating scatterplots with multi-dimensional encoding.

Identifying "consistent" car models with low mpg variation over multiple years.

# How to Run
Ensure Python 3.x is installed.

Install required libraries if not already available:

nginx
Copy
Edit
pip install numpy pandas matplotlib seaborn
Place Cars.csv in the same directory as the script or notebook.

Run the provided Python notebook or script to perform the analysis.

# Outputs
Printed summaries for shape, columns, unique values.

Dataframe previews after processing.

Answers to quiz questions printed to the console.

Visualizations showing trends and relationships within the data.

Notes
Missing or non-numeric horsepower values were converted to NaN and handled appropriately.

The assignment demonstrates data manipulation using pandas and visualization with Matplotlib and Seaborn.
