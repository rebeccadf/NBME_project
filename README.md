# NBME_project
Our BERT based model solution to the Kaggle competition at https://www.kaggle.com/competitions/nbme-score-clinical-patient-notes. The solution follows a Named Entity Recognition approach. The code can be found in the "nbme-pytorch-ner.ipynb" file. The dataset used is the dataset available at the competition page https://www.kaggle.com/competitions/nbme-score-clinical-patient-notes/data. While the best model that was trained on all dataset on the DTU HPC cluster and some saved outputs of the training phase can be found at: https://www.kaggle.com/datasets/rebeccadifrancesco/nbmemodel .
The notebook that was submitted on Kaggle (https://www.kaggle.com/code/rebeccadifrancesco/nbme-pytorch-ner) shows the F1 score on the test set to be 0.79.
The results folder simply shows the experiments output for the best model (lr: 5e-5, batch size: 16) running on 10 epochs and there is the dataframe with all the hyperparameters experiments for the 18 models tested. 
