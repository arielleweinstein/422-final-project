# Programming For Data Science Final Project

## Overview
The purpose of this project was to take a large database of movies and do initial EDA exploring the available data, and then to create a model to predict critic ratings of movies. The data was split into a training set (movies that came out before 2010) and a test set (movies that came out after 2010) and the training set was used to train the model to predict critic ratings.

## Repo Structure
This repository contians the Python notebook that has all of the EDA and modeling code. The final outcomes of the tested models are at the bottom of the notebook. 

There is a CSV file with all of the data that was used in this project labeled 422final_data.csv.

There is a .gitignore file for ignoring files such as .DS_Store and .ipynb_checkpoints.

There is a .yml file titled 422final.yml that contains all of the packages and variables necessary to run the code. This is mainly for the necessary packages that the code uses and the variables for signing into the MLDS SQL server. 

# To Run
Set your environment variables to be your Northwestern NETID login information. You can run the following commands in your terminal and then reactivate the environment to set the variables:
```bash
conda env config vars set USER=<your username here>
conda env config vars set PASSWORD=<your password here>
```
Don't forget to reactivate your environment after setting each variable so that they are saved to the environment. Then you should be able to run the Python notebook without any issues using the environment.