## Sentiment-Analysis-Website

This is an academic project to predict the sentiment of a movie review as being a negative review or positive review.

## Hardware Requirement
This project is designed to run in the Amazon Web Services (AWS) cloud environment. 
It is strongly suggested that you incorporate the use of a GPU through AWS to run the Pytorch neural network model.

## Software Requirement
This project requires the use of Amazon's SageMaker provided through (AWS). You will need an AWS account to use this service.

An AWS hosted Jupyter Notebook using XGBoost and running Python 3.6 and Pytorch was used to execute this code.

The following libraries which are included in the requirements.txt for testing and deployment were used:

pandas==0.22

numpy

nltk

beautifulsoup4

html5lib


## Code
The main code for this project is provided in the `SageMaker Project.ipynb` notebook file. Additional supporting files are also provided in the additional folders.

## Data
The dataset consists of 25,000 movie reviews provide by the Internet Movie Data Base [IMDB](http://ai.stanford.edu/~amaas/data/sentiment/). 

## Run
Simply launch a Jupyter Notebook instance using AWS' SageMaker and clone this Git repository `https://github.com/Onestroke1/Sentiment-Analysis-Website.git`.
Opening the Jupyter Notebook file `SageMaker Project.ipynb` will walk you through each step that was done to achieve the final results. 




