# Recommender-System
Collect snap data and use recommender systems using deep learning algorithms and machine learning and rate prediction.


## Download Dataset
Download DataSet from link below:
https://drive.google.com/file/d/1-BivapOkCSDZclmOGAonw3jxRD4Fm4s5/view?usp=sharing

### Result for Singular Value Decomposition SVD
`loss (RMSE) : 0.8177`

### Result for SVDpp
`loss (RMSE) : 0.8530`

### Result for Deep Learning with Binary Cross Entropy
`loss (binary cross entropy) : 0.6340`

### Result for Deep Learning with Mean Squared Error
`loss (MSE) : 9.3482`

## Algoritm Singular Value Decomposition (SVD)

Run this `recommeder_system_SVD.ipynb` jupyter lab to see the algoritm.
in this jupyter lab file, the loss function is Root Mean Squared Error.


In the context of the recommender system, the SVD is used as a collaborative filtering technique. It uses a matrix structure where each row represents a user, and each column represents an item. The elements of this matrix are the ratings that are given to items by users.

![bandicam 2023-06-14 20-10-43-510](https://github.com/AmirRezaFarokhy/Recommender-system/assets/113052872/d258f614-915e-471f-a248-4f5d5482901d)

## Algoritm SVDpp

Run this `recommeder_system_SVDpp.ipynb` jupyter lab to see the algoritm.
in this jupyter lab file, the loss function is Root Mean Squared Error.


![bandicam 2023-06-14 20-11-43-815](https://github.com/AmirRezaFarokhy/Recommender-system/assets/113052872/044a219c-800d-4016-9bfb-1e0af581fd35)


## Neural Collaborative Filtering Recommendation (NCF)

Run this `recommeder_system_Deep_Learning_1.ipynb` jupyter lab to see the algoritm.
in this jupyter lab file, we normilize the rating column between 0, 1 and the loss is Binary Cross Entropy.


Run this `recommeder_system_Deep_Learning_MSE.ipynb` jupyter lab to see the algoritm.
in this jupyter lab file, the loss function is Mean Squared Error.


![bandicam 2023-06-15 02-20-24-152](https://github.com/AmirRezaFarokhy/Recommender-system/assets/113052872/04042da0-8eff-4799-aa6a-905fc4b33263)


### Embending Layer
An embedding layer is a type of hidden layer in a neural network. In one sentence, this layer maps input information from a high-dimensional to a lower-dimensional space, allowing the network to learn more about the relationship between inputs and to process the data more efficiently.


### Requirements
Running `Recommender-System` requires:
* Python 3.8 (tested under Python 3.10.4)
* Using Google Colab GPU



