# Prediction DDoS
This project was developed for the university course Data Analysis for Security. 
The project aims to extract knowledge from data for the classification of DDos attacks by following the development steps of the KDD process.

![ProcessoKDD](https://github.com/francescovolpe/Prediction-DDoS/blob/main/Img/KDD-Process.png)

## Dataset
Source: [A subset of data collected by the Canadian Institute for Cybersecurity in 2019](https://www.unb.ca/cic/datasets/ddos-2019.html).
The dataset contains attacks that can be executed using TCP/UDP-based protocols.

| # Training examples | # Testing examples | # Feature | # Classes |
| :---: | :----: | :----: | :----: |
| 10.000 | 1.000 | 78 | 5 |


## Confusion matrix on the test dataset
![ConfusionMatrix](https://github.com/francescovolpe/Prediction-DDoS/blob/main/Img/ConfusionMatrix.png)

## Libraries used
* Python 3.8.12
* Scikit-learn 1.0
* Pandas 1.3.4
* Matplotlib 3.4.3
* Numpy 1.21.3

#### Notebook display problems
If you have problems displaying notebooks due to rendering, you can use [nbviewer](https://nbviewer.jupyter.org/)
