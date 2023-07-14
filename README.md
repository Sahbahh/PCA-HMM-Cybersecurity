# PCA-HMM-Cybersecurity
SFU CMPT318 - group project <br />
Team members:<br /> 
Kiarash Zamani <br />
Sahba Hajihoseini <br />
Quang minh Dinh <br />
Kayin Lam Chen <br />
-----------------------------------
**Summary:**<br />
This Cybersecurity project is a technical study of unsupervised intrusion detection. It utilizes time series analysis and forecasting applied to stream data from a supervisory control system. The project is divided into three primary tasks:<br />

1. **Feature Engineering:** It involves the selection of a subset of response variables for the training of multivariate Hidden Markov Models (HMMs) using Principal Component Analysis (PCA). This process allows the identification of the most suitable variables for training the models.<br />

2. **HMM Training and Testing:** Data is partitioned into training and testing sets, and HMMs are trained on various data sets with different numbers of states. Models are then evaluated and selected based on their log-likelihood and Bayesian Information Criterion (BIC) values.<br />

3. **Anomaly Detection:** Using the trained HMMs, the log-likelihood of observation sequences is computed to detect anomalies within specific datasets.<br />

A key aspect of this project is the utilization of common datasets for training, testing, and anomaly detection. This allows for comparative analysis of experimental results across all participating groups.<br />

The project makes use of R programming language, and outcomes include an extensive analysis and evaluation report, as well as the R code developed to complete these tasks.<br />
