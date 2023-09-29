# End-To-End-Chicago-Taxi-Tip-Prediction-with-BigQuery-and-Vertex-AI


This repository contains a complete end-to-end MLOps pipeline for predicting taxi tips in Chicago using Vertex AI and Smart Analytics. The pipeline uses Keras to implement the machine learning model, TFX to implement the training pipeline, and Model Builder SDK to interact with Vertex AI. The Chicago Taxi Trips dataset is a public dataset hosted on BigQuery that includes taxi trips from 2013 to the present.

The pipeline consists of the following steps:

1. **Data preparation:** The pipeline first loads the Chicago Taxi Trips dataset from BigQuery and cleans and preprocesses the data.
2. **Feature engineering:** The pipeline then creates new features from the existing data that may be useful for predicting taxi tips.
3. **Model training:** The pipeline then trains a machine learning model using the preprocessed data and the engineered features.
4. **Model evaluation:** The pipeline then evaluates the trained model on a held-out test set to assess its performance.
5. **Model deployment:** Once the model is trained and evaluated, the pipeline deploys it to Vertex AI as an endpoint.
6. **Model monitoring:** The pipeline then monitors the deployed model to ensure that it is performing as expected.

The repository includes all of the code and configuration files necessary to run the pipeline. To get started, simply clone the repository and follow the instructions in the README file.


## Dataset description
https://pantheon.corp.google.com/marketplace/details/city-of-chicago-public-data/chicago-taxi-trips

The Chicago Taxi Trips dataset is one of public datasets hosted with BigQuery, which includes taxi trips from 2013 to the present, reported to the City of Chicago in its role as a regulatory agency. The task is to predict whether a given trip will result in a tip > 20%.

## Getting started
1. Setup your MLOps environment on Google Cloud.

2. Start your AI Notebook instance.

3. Open the JupyterLab then open a new Terminal

4. Clone the repository to your AI Notebook instance:

```
cd https://github.com/syedsajjadaskari/End-To-End-Chicago-Taxi-Tip-Prediction-with-BigQuery-and-Vertex-AI
cd End-To-End-Chicago-Taxi-Tip-Prediction-with-BigQuery-and-Vertex-AI
```

6. Install the required Python packages:
```
pip install -r requirements.txt
```





