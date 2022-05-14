# OLID_NLP
This is the repository for the final assignment of the NLP class followed at the University of Antwerp. The assignment follows the OffensEval 2019 shared task competition with a focus on the sub-task A, aiming to classify offensive text.

The folder [data](./data) contains the training and test sets, as well as the processed datasets required to reproduce the experiments. Information about data and the processes of annotation can be found in the [information](./information) folder.

The final paper of this research explaining the process and results can be found in the [paper](./paper) directory. 

The predictions for each reported model can be found in the [predictions](./predictions) directory. 

In the [notebooks](./notebooks) directory there are different Jupyter Notebooks available (written in Python): 

[TrainingData_Exploration_Preprocessing](./notebooks/TrainingData_Exploration_Preprocessing.ipynb) 

This notebook reads, cleans, pre-processes and prepares input datasets for training SVM and BERT models.
  
[TestData_Preprocessing_Exploration](./notebooks/TestData_Preprocessing_Exploration.ipynb) 

Following the same steps of the first notebook, this notebook reads, cleans, pre-processes and prepares test datasets for prediction purposes.

[SVM_Classification_POS](./notebooks/SVM_Classification_POS.ipynb) 

In this notebook, the pre-processed training data is prepared for modelling. Hyper-parameter tuning is applied with Grid Search to find optimum hyper-parameters for the best performed model. Error analysis is conducted to further evaluate model performance. Finally, the pre-processed test sets are read and prepared for predictions. Results of predictions along with model performance macros are reported and saved.  

[BERT_Experiments](./notebooks/BERT_Experiments.ipynb) 

In this notebook various experiments have been run with the pre-trained BERT-base-uncased model. For each training loss curves have been reported. All experiments are logged and saved. 

[BERT_Predictions](./notebooks/Bert_Predictions.ipynb) 

The best performing BERT experiment have been used to classify texts from different test sets as offensive. Results of predictions along with model performance macros are reported and saved.  


