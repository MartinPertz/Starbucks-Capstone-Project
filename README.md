# Starbucks-Capstone-Project

Udacity capstone project

This is a Udacity Nanodegree Data Scientist Project.

### Table of Contents
- Installation
- Project Motivation
- File Description
- Results
- Acknowledgements

### Installation
The program code runs under Python 3.*. 

It requires the following Python libraries:
- pandas
- numpy
- sklearn.model_selection
- sklearn.ensemble
- sklearn.tree
- sklearn.preprocessing
- sklearn.metrics
- math
- json
- copy
- scipy.stats
- matplotlib.pyplot
- seaborn as sns

### Project Motivation
The data for this project was provided by Udacity. This is not real data, but simulated data. They consist of information that describes what factors influence customers to make a purchase decision. My interest was in using the simulated data to answer the question:

How accurate is it to predict whether or not an offer in the Starbucks rewards app will be accepted by a customer group?

For this purpose, the database of consumers with their specific characteristics was divided into individual customer-specific databases. The databases were divided according to:

- offer: BOGO (Buy One Get One Free) / discout / informational
- customer gender: male/female (there was not enough data for gender 'other' for static evaluations)
- customer age: old / young (split by mean age over all consumers)
- customer income: rich / poor (split by mean income over all consumers)

In this way, 16 databases were determined and the accuracy determined for each database.


### File Description
Starbucks_Capstone_notebook.ipynb

The app folder includs the following files, provided by Udacity:
- portfolio.json
- profile.json
- transcript.json

README.md

LICENSE

Hint: Please ignore the object '.ipynb_checkpoints'

You can find the code in my github repository [https://github.com/MartinPertz/Starbucks-Capstone-Project](https://github.com/MartinPertz/Starbucks-Capstone-Project)


### Results
The key findings of the Code can be found in the article available in [medium.com/@martinpertz](https://medium.com/@martinpertz/evaluation-of-forecast-accuracy-for-starbuck-offers-1d77d258fb1b).


### Acknowledgements
Thanks to Udacity for providing the data for training purposes as part of this project. Also thanks to Udacity for the courseware and training.
