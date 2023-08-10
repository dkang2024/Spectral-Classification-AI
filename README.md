# Spectral-Classification-AI

This repository contains a machine learning model trained to classify stars using an image of them and the stars' fluxes. The machine learning model has an accuracy of 95%, compared to the accuracy given by a regular calculation of about 40%. The machine learning model is a combination of a Random Forest Classifier, Convolutional Neural Network, and Multi-Layer Perceptron. 

## IMPORTANT

**When running the files, try not to run the cells that have prompts to them in Dataset.ipynb. If you happen to run the first two cells with user prompts ("Are you sure you want to run this cell"), which download data from Simbad and shuffles GeneratedData.txt, DO NOT RUN THE THIRD CELL WITH A USER VERIFICATION PROMPT WHICH UPDATES DATASET.CSV!!! This will mess up the Dataset's orientation with the Image Dataset, and will result in very low accuracy from the model. If you run the first two cells, which I don't recommend because downloading from Simbad takes a while and times you out from their DDOS protection sometimes, just make sure not to run the third cell with user authentication in Dataset.ipynb. Regarding Image Dataset.ipynb, just type "exit" when prompted.**

## Python Build 

This build is only tested on Python 3.11.4 with the latest versions of every package imported. Please update your python to this version and update your packages if these files do not work. We tested on Python 3.9 with older packages and some of the importations failed. 

Please enjoy!
