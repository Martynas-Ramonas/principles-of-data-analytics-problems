# Principles of Data Analytics Assessment

This repository contains my assessment work for the Principles of Data Analytics module.

The work is completed in a Jupyter notebook called `problems.ipynb`. The notebook contains solutions to the assessment problems, including working with Python libraries such as pandas, numpy, and matplotlib, and analysing the Palmer Penguins dataset.


## Repository Contents

- `README.md` - describes the project and explains how to run it.
- `.gitignore` - lists files and folders that should not be tracked by Git.
- `requirements.txt` - lists the Python packages needed to run the notebook.
- `problems.ipynb` - contains the assessment work.


## Assessment Problems

This repository will contain solutions to the following problems:

- [Problem 1: Creating the Repository](#problem-1-creating-the-repository)
- [Problem 2: The README.md](#problem-2-the-readmemd)
- [Problem 3: gitignore](#problem-3-gitignore)
- [Problem 4: The Notebook](#problem-4-the-notebook)
- [Problem 5: The Penguins](#problem-5-the-penguins)
- [Problem 6: Visualizing Distributions](#problem-6-visualizing-distributions)
- [Problem 7: Investigating Relationships](#problem-7-investigating-relationships)
- [Problem 8: Modelling the Data](#problem-8-modelling-the-data)


## Problem 1: Creating the Repository

For this problem, I created a new GitHub repository to store my assessment work for the Principles of Data Analytics module.

The repository was set up with the following files:

- `README.md` to describe the project.
- `.gitignore` to prevent unnecessary files from being tracked.
- `requirements.txt` to list the Python packages needed to run the notebook.
- `problems.ipynb` to contain the completed assessment work.

The repository will be updated regularly as I complete each problem in the assessment.


## Problem 2: The README.md

For this problem, I updated the `README.md` file to describe the purpose of the repository and explain how to run the project.

The README includes a short project description, a list of the main files in the repository, instructions for installing the required Python packages, and instructions for opening the Jupyter notebook.


## Problem 3: gitignore

For this problem, I added a `.gitignore` file to the repository.

The `.gitignore` file is used to tell Git which files and folders should not be tracked. This helps keep the repository clean by ignoring files that are created automatically, such as Python cache files, Jupyter Notebook checkpoints, virtual environments, and system files.

This is useful because these files are not part of the main assessment work and do not need to be uploaded to GitHub.


## Problem 4: The Notebook

For this problem, I created the `problems.ipynb` Jupyter notebook.

The notebook contains a Level 1 title, imports the required Python libraries, and explains how pandas, numpy, and matplotlib.pyplot are used in data analytics.


## Problem 5: The Penguins

For this problem, I loaded the Palmer Penguins dataset into the notebook using pandas.

I used the `describe()` method to calculate descriptive statistics for the numeric variables, including bill length, bill depth, flipper length, and body mass.


## Problem 6: Visualizing Distributions

For this problem, I created histograms for the numeric variables in the Palmer Penguins dataset and bar charts for the categorical variables.

These plots help show how the data is distributed and make it easier to identify patterns in the dataset.


## Problem 7: Investigating Relationships

For this problem, I used scatter plots to investigate relationships between variables in the Palmer Penguins dataset.

I focused on the relationship between flipper length and body mass, and also compared this relationship across the different penguin species.


## Problem 8: Modelling the Data

For this problem, I used `numpy.polyfit` to create a simple straight-line model.

The model looks at whether body mass can be used to estimate bill length. I also calculated the R-squared value and plotted the straight line on a scatter plot.


## How to Run This Project

1. Clone this repository:

   ```bash
   git clone https://github.com/Martynas-Ramonas/principles-of-data-analytics-problems.git
   ```

2. Install the required packages:

   ```bash
   pip install -r requirements.txt
   ```

3. Open the notebook:

   ```bash
   jupyter notebook problems.ipynb
   ```

