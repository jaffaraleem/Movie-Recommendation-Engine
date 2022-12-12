# Movie-Recommendation-Engine

Deep Learning model to provide movie recommendations

Link to dataset : https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset

DataCleaning.ipynb :
Python notebook to clean the dataset and add features like cast, directors to the metadata dataset.
Perform text pre processing and convert words to vectors
Normalize the numeric data columns

DataGenerator.ipynb :
Python notebook to generate combination of 3 movies and a target label. Generated 500000 data points.

RecommendationEngine.ipynb:
Training the model and generation of recommendations

Models:
6 model configurations have been saved. The model with the lowest loss and smallest disatnce is config_3.pt

Other Model Files
config_1.pt --- Largest Learning Rate, High Loss --- 9MB
config_2.pt --- Low Loss --- 9MB
config_3.pt --- Lowest Loss and Distance --- 9MB (selected model)
config_4.pt --- Lowest Learning Rate, High Loss --- 9MB
model_tanh.pt --- Model with tanh activation --- 9MB
model_leakyRelu.pt --- Model with Leaky Relu Activation --- 9MB
model_relu.pt --- Model with Relu Activation --- 9MB