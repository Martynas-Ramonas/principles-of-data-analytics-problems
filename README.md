# Principles of Data Analytics Problems

This repository is for assesment purposes for Principles of Data Analytics

## Contents

### Problem 1: Creating Your Repository
On github.com, create a new repository for this assessment.

Repository Name: Choose a meaningful, lowercase name (e.g., principles-of-data-analytics-problems).
Initialize: Select the option to Add a README file and select Python from the Add .gitignore dropdown menu.
Submission: Copy your repository URL (e.g., https://github.com/username/reponame) and submit it via the official module submission form above.

### Problem 2: The README.md
Open your repository in Visual Studio Code (or whatever way you prefer). Edit the README.md file to include:

A Level 1 heading with the project title.
A brief description of the repository's purpose.
A Level 2 heading for Contents followed by a list of the problems you will solve.
Save your changes, commit them with a meaningful message (e.g., Initialize README), and push/sync them to GitHub.

### Problem 3: gitignore
While GitHub provides a basic .gitignore, professional projects often require more detail to prevent temporary or other unnecessary files being added to your repository.

Go to Toptal's gitignore.io website and generate a comprehensive .gitignore file for Python, Visual Studio Code, and Jupyter Notebooks.
Replace the contents of the .gitignore in your repository with this generated text.
Save, commit, and push these changes.

### Problem 4: The Notebook
In the root of your repository, create a new file named problems.ipynb.

Add a Markdown cell at the top with a Level 1 heading title for the notebook.
Add a Code cell to import the necessary libraries: pandas, numpy, and matplotlib.pyplot.
Add another Markdown cell explaining what these libraries do in the context of data analytics.
Save, commit, and push your notebook.

### Problem 5: The Penguins
For the remaining problems, you will use the Palmer Penguins dataset.

In your notebook, add a Level 2 heading for Problem 5.
Search for the raw URL of the penguins.csv file (e.g., from this repository or a reputable GitHub source) and use pandas to load it into a DataFrame.
Use the describe() method to calculate descriptive statistics for the numeric variables (bill length, bill depth, flipper length, and body mass).
In a Markdown cell, explain what information the mean, std, and quartiles (or percentiles) provide about the penguin populations.
Save, commit, and push your notebook.

### Problem 6: Visualizing Distributions
Select one numeric variable from the dataset.

In your notebook, add a Level 2 heading for Problem 6.
Create a Histogram of this variable to show its distribution.
Create a Box Plot of the same variable to identify the median and potential outliers.
In a Markdown cell, compare these two plots. What does the box plot tell you that the histogram does not?
Save, commit, and push your notebook.

### Problem 7: Investigating Relationships
Do larger penguins have longer bills?

In your notebook, add a Level 2 heading for Problem 7.
Create a Scatter Plot comparing body_mass_g (X-axis) and bill_length_mm (Y-axis).
Use the species column to colour-code the dots, allowing you to see if the relationship differs between Adelie, Chinstrap, and Gentoo penguins.
In a Markdown cell, describe any trends or patterns you observe in the plot.
Save, commit, and push your notebook.

### Problem 8: Modelling the Data
Finalize your analysis by fitting a straight line to the data.

In your notebook, add a Level 2 heading for Problem 8.
Use numpy.polyfit to find the best-fit straight line for the relationship between body mass and bill length.
Calculate the R-squared value to evaluate how well this line fits the data.
Plot the best-fit line on top of a scatter plot of the two variables.
In a final Markdown cell, interpret the R-squared value: Does body mass accurately predict a penguin's bill length?
Save, commit, and push your notebook.