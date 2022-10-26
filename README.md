# Anomaly-Network-Traffic-Detection
An intrusion-detection-system model to distinguish benign and potential anomaly network traffic.
The model is built based on the dataset provided by University of New Brunswick.(https://www.unb.ca/cic/datasets/ids-2017.html)

To see precleaned dataset, check total_Matrix.csv

Reduced feature dimensionality through using PCA;
Utilized both unsupervised learning(K-Means) and supervised learning(Random Forest) to predict benign network traffic and attacks; 
Utilized cross-validation to optimize parameters to reduce overfitting;

## To run the model, feed in the file total_Matrix.csv, and run the JupterNotebook file.


