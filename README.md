# Starbucks-Capstone-Project

Udacity capstone project

This is a Udacity Nanodegree Data Scientist Project.

### Table of Contents
Installation
Project Motivation
File Description
Results
Acknowledgements

### Installation
The program code runs under Python 3.*. 

It requires the following Python libraries:
pandas
numpy
sklearn.model_selection
sklearn.ensemble
math
json
copy
scipy.stats

### Project Motivation
The data for this project was provided by Udacity. This is not real data, but simulated data. They consist of information that describes what factors influence customers to make a purchase decision. My interest was in using the simulated data to answer the question:

	For which customers groups can a recommendation for an offer be made and with what accuracy?

For this purpose, the database of consumers with their specific characteristics was divided into individual customer-specific databases. The databases were divided according to:

- offer: BOGO (Buy One Get One Free) / discout / informational
- customer gender: male/female (there was not enough data for gender 'other' for static evaluations)
- customer age: old / young (split by mean age over all consumers)
- customer income: rich / poor (split by mean income over all consumers)

In this way, 24 databases were determined and the accuracy determined for each database.


### File Description
Starbucks_Capstone_notebook.ipynb

The app folder includs the following files, provided by Udacity:
- portfolio.json
- profile.json
- transcript.json

README.md

LICENSE

Hint: Please ignore the object '.ipynb_checkpoints'


### Result
The results are contained in the respective conclusions for the individual tasks. A brief summary is included at the end of Starbucks_Capstone_notebook.ipynb in 'Conclusion for computed accuracy for 'BOGO' and 'discount' "gender-age-income-specific" data'.


### Acknowledgements
Thanks to Udacity for providing the data for training purposes as part of this project. Also thanks to Udacity for the courseware and training.
