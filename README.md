# Final_Project
Comparison of BERT, RoBERTa, Albert on MIT Movie and MIT Restaurant datasets
For this project, we worked on two datasets MIT Movie and MIT Restaurant. Each dataset has different type of data. 
Pre-processing of this data is done to create new_labels for each sentence. Then this pre-processed data or encoded tokens and the new labels are given to three models  BERT, RoBERTa, Albert. These models were fine-tuned intially for Token Classification task with a linear token classification layer on the top of models.
After training these models on mentioned datasets and the training was monitored for 4 epochs. It is observed that RoBERT and Albert performed better than BERT model on the two datasets. Finally labels of test data are predicted and  they achieved better F1 scores for RoBERTa and Albert when compared to BERT model.
