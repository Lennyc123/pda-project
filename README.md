# Programming for Data Analysis - Project 2020, by Leonard Curtin

The project itself was conducted within a jupyter notebook and written in the langauge of python version 3.8 . The working enviornment was setup using anaconda which was downloaded and installed from https://www.anaconda.com/.

## Contents of the notebook
Within the following notebook, the pheonomenon of the likelihood that ones is to find themselves in a road accident has been examined. The overarching aim of the project itself, is to view the relationship between the collaborative effects of several variables and their relationship with the likelihood of one being in a road accident.

The various factors that are suggested to increase or decrease the likelihood of a road accident occuring have been proposed within this project.

## Examining the factors related to the pheonomenon of one's potential to be in a road accident
A segment of the notebook is dedicated to research on the various factors that influence of likelihood of one being in a road accident. The aim of the research section is to provide grounds as to why particular variables were selected to be examied within the project.

## Creation of variables:
Regarding the sample size of the dataset, 1000 particpants were selected in order to remove factors such as the data being swayed  in a particular manner or being influenced by the effect of outliers.

## The following varibles were selected:

### Age

### Age category

### Gender


### Driver experience (Years)


### Numbers of wheels on a participants primary vehicle

### Human factors
<br>
<hr>

## A ranking system was created based on the data of the variables listed above.
The ranking system is designed to estimate the likelihood of a participant getting into a road accident by looking at the collaborative effects of the variables and their potential impact.

A forumla was created to calculate an approximate categorical value of ones potential of being in a road accident.
<hr>

### Visualisation of the simulated dataset
Graphical depictions of the dataset were created through the usage of matplotlib and seaborn

<br>

## The following python libraries were imported and utilised throughout the course of the project
Pandas - which acts as a data manipulation and analysis tool

NumPy - a library for the Python programming language, with support for large, multi-dimensional arrays and matrices, along with a large collection of high-level mathematical functions to operate on these arrays.

Matplotlib - a plotting library for the Python programming language

seaborn - a data visualization library based on matplotlib. It provides a high-level interface for drawing attractive and informative statistical graphics.

## Various python libraries were imported using the following commands
``` python
# Commands for importing the various python libraries
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
```

 - Pandas allowed for the csv file to be read, for the dataframe to be created and for summaries of the dataset to occur.

 - NumPy was used primarily for calculations regardings linear regression and polynomial regression.

 - Matplotlib and Seaborn allowed for the creation of vivid depictions to occur based on the information within the dataframe, through the usage of its plotting functions.
