# CRISP DM on Seattle Airbnb Dataset

# Introduction

Since 2008, guests and hosts have used Airbnb to travel in a more unique, personalized way. As part of the Airbnb Inside initiative, this dataset describes the listing activity of homestays in Seattle, WA.
Content

### The following Airbnb activity is included in this Seattle dataset:

Listings, including full descriptions and average review score

Reviews, including unique id for each reviewer and detailed comments

Calendar, including listing id and the price and availability for that day

The Original Dataset can be found here: [Kaggle Seattle Open Dataset](https://www.kaggle.com/airbnb/seattle)


### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

This project utilizes default packages within the Anaconda distribution of Python for the majority of the analysis. 

However, you will need to install plotly if you haven't already done so before. See [Getting Started with Plotly for Python](https://plot.ly/python/getting-started/).

In addition, if you would like to display the plotly visualizations within the jupyter notebook, then you will need to install the orca commandline utility and the psutil and requests Python libraries. See [Static Image Export in Python](https://plot.ly/python/static-image-export/).

The code should run with no issues using Python versions 3.*.


## Project Motivation<a name="motivation"></a>

For this project, I was interestested in using Seattle Airbnb data to better understand:

1. What are the distribution of listing prices by neighborhoods?
2. How varied are the neighborhoods in terms of property type?
3. How well can we predict listing price?


## File Descriptions <a name="files"></a>

There is one notebook available here to address the questions above.

Please note that the notebook utilizes Plotly for a majority of the visualizations. Dependencies for doing so on your own local machine are mentioned above in the Installations section. 

The Plotly visualizations' output will not appear when viewing in Github. You can view in the main.html or use nbviewer. 


## Results<a name="results"></a>

The main findings of the code can be found at the post available [A Sneak Peek into Airbnb Atcitivity In Seattle](https://medium.com/@chaithanyakumar_91513/a-sneak-peek-into-airbnb-activity-in-seattle-5b59328163af).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>
Credit to Airbnb for providing the data. Licensing information can be found at the [Kaggle page](https://www.kaggle.com/airbnb/seattle) and the original source from [Airbnb Inside](http://insideairbnb.com/get-the-data.html).
