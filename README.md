# Terrorism target set generation

_José Roberto Canivete Cuissa_  
_Luigi Bassini_  
_Dorian Quelle_  

Zurich, 14.05.2023

The aim of this project is to predict if a building with specific features is likely to be targeted in a terrorist attack by analyzing a selected list of buildings that have been attacked in the past. To achieve this, the proposed approach involves using the OpenAI GPT-3.5 model to rate the importance of certain features for a given building at a specific year in the past. The past events are exctracted from the Global Terrorism Database (https://www.kaggle.com/datasets/START-UMD/gtd). Then, a machine learning model will be trained using the generated dataset to make predictions.

This project has been proposed by Zurich Insurance as a challenge during the Academia Industry Modeling Week 2023 which took place at the University of Zurich.  

### Requirements

- openai
- numpy
- pandas
- matplotlib
- shap
- scikit-learn

To use the OpenAI API, the library needs a valid account's secret key. Visit https://platform.openai.com/ to create an account and generate a secret key. 