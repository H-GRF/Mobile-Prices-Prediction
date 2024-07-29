# Mobile Prices Regression
## DatatalksClub ML Zoomcamp Midterm Project

Author: [ Hamza Gouaref]
Email: [ gouarefhamza@gmail.com]

## Objectives of Midterm Project:

* Find a dataset
* Explore and prepare the data
* Train the best model
* Export the notebook into a script
* Put model into a web service
* Deploy model locally with Docker

## Overview

This project focuses on predicting mobile phone prices in Algerian Dinar (DZD) using a regression approach. The dataset used in this project contains the following features related to mobile phones:

* phone_name: Name of the mobile phone model.

* rating_5: Average rating out of 5.

* number_of_ratings: Number of ratings given to the mobile phone.

* ram: RAM (Random Access Memory) size of the mobile phone.

* rom: ROM (Read-Only Memory) size of the mobile phone.

* back_camera: Specification of the back camera of the mobile phone.

* front_camera: Specification of the front camera of the mobile phone.

* battery: Battery capacity of the mobile phone.

* processor: Details about the processor of the mobile phone.

* price_DZD: Mobile phone price in Algerian Dinar (DZD).

By leveraging machine learning techniques, we aim to build an accurate regression model that can predict mobile phone prices based on these features.

## Explore Data:

Check the structure and columns of the dataset.
Review the number of features and observations in the data...

## Prepare Data:

Handle missing values if any.

Address duplicate entries.

## Train Data:
Encode categorical variables using techniques like one-hot 

encoding or label encoding.

Train and evaluate different machine learning models to find the best-performing one.

## Model Deployment to Web Services

For deploying the model as a web service, Flask will be utilized, implemented through the web_service.py script.

Set up Pipenv Virtual Environment by running the following commands in your terminal:

pip install pipenv
pipenv install flask numpy scikit-learn==1.3.0 requests

The model will be integrated into the Flask web service for real-time predictions.

## Deploy Model Locally with Docker

To deploy the model locally using Docker, follow these steps:

Ensure Docker is installed on your machine.
Open your terminal and navigate to the project directory.
Run the following command to create a Docker image:

docker build -t mobile-price-regression .


Once the image is built, run the Docker container with the following command:


docker run -it --rm -p 5000:5000 mobile-price-regression

## Expected Outcomes

By the completion of this project, we anticipate achieving the following goals:

Develop a regression model capable of accurately predicting mobile phone prices in Algerian Dinar (DZD) based on various features.

Gain insights into the factors that significantly influence mobile phone prices in the Algerian market.

Contribute valuable findings and analysis to the domain of mobile device market analysis in Algeria, aiding consumers, retailers, and manufacturers in making informed decisions.

Showcase the power of regression techniques in predicting complex real-world outcomes, demonstrating their applicability in pricing analysis and market research within the Algerian mobile phone industry.
