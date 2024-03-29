# NBME_project
This prokect is our BERT based model solution to the Kaggle competition at https://www.kaggle.com/competitions/nbme-score-clinical-patient-notes. The solution follows a Named Entity Recognition approach. The code can be found in the "nbme-pytorch-ner.ipynb" file. 

The dataset used is the dataset available at the competition page https://www.kaggle.com/competitions/nbme-score-clinical-patient-notes/data. While the best model that was trained on all dataset on the DTU HPC cluster and some saved outputs of the training phase can be found at: https://www.kaggle.com/datasets/rebeccadifrancesco/nbmemodel .
The notebook that was submitted on Kaggle (https://www.kaggle.com/code/rebeccadifrancesco/nbme-pytorch-ner) shows the F1 score on the test set to be 0.78. The results folder simply contains the dataframe with all the hyperparameters experiments for the 18 models tested and it shows the loss, precision, recall and accuracy curves for the best model (lr: 5e-5, batch size: 16) running on 10 epochs rather than 4 to highlight the overfitting issue after 4 epochs. 

![image](https://user-images.githubusercontent.com/102923478/227796019-507be84b-e3a7-4936-920f-46af4641f69d.png)

