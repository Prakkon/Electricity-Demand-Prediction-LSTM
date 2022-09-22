# Electricity-Demand-Prediction-LSTM


### Introduction

This forecasting method has been adopted due to the necessity of continuous long term data modelling in case of electricity demand prediction. [Another work](github.com/Prakkon/Electricity-Demand-Prediction-Ensemble) largely dissimilar from this addresses the problem with Real Time assessment of data through an ensemble model. 
---

### Dataset Specifications

- Data used consists of meter readings from different buildings (each building representing a type of institution, like education, domestic, et al)
- These meter readings are recorded for every 10 minutes across 20 days of data accumulation
- data also consists of building_meta data (meter readings per building with an id)
- and finally, weather conditions and weather based data collected from weather api.
---

### How to use

- This project uses [Jupyter Notebook](https://docs.jupyter.org/en/latest/install.html) (ver. == 6.4.5). You can alternatively use [Google Colab](https://colab.research.google.com) for editing
- data preprocessing produces the train/test set, and weather data API fetch and data preprocessing yields to weather test/train sets respectively
- Run ```Electricity Demand Prediction.ipynb``` to train the data using LSTM and produce some EDA preprocessing and post processing.
---

### Results

The results are recorded in the [Results](https://github.com/Prakkon/Electricity-Demand-Prediction-LSTM/tree/main/results) directory.
---

### Tech Stack

<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/anaconda/anaconda-original.svg" alt="anaconda_logo" width="50" height="50"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jupyter/jupyter-original.svg" alt="jupyter_logo" width="50" height="50"/>  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" alt="python_logo" width="50" height="50"/>
---          
          

