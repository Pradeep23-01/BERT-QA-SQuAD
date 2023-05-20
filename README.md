# BERT-QA-SQuAD
This work concentrates on comparing &amp; improving BERT based QA models using less Computation and GPU

To Improve the performance of the BERT-based question-answering model on the SQuAD dataset by proposing several enhancements with BERT architecture

Techniques Used:
- Hyperparameter tuning 
- Ensembling Multiple Models

## SQuAD 2.0 DATASET:
- The Stanford Question Answering Dataset (SQuAD) 2.0 is a dataset designed for evaluating the performance of question-answering systems on more challenging tasks.
- Contains questions that do not have a definite answer in the given context
- The dataset contains over 100,000 questions that are derived from Wikipedia articles and covers a wide range of topics.

Dataset Download: https://rajpurkar.github.io/SQuAD-explorer/

## METRICS:
- F1 score measures the model's ability to correctly predict the answer and is calculated based on the overlap between the predicted answer and the ground truth answer.
- Exact Match (EM), on the other hand, measures the model's ability to provide the exact same answer as the ground truth answer.

## Results:
![Capture](https://user-images.githubusercontent.com/66003584/236112875-6713790a-9c80-4857-9b7a-e505c03df780.PNG)

![em](https://user-images.githubusercontent.com/66003584/236112914-37b0822b-02df-457f-9fb6-be553a02dadc.png)

![f1](https://user-images.githubusercontent.com/66003584/236112928-d595e384-19c4-4767-90a0-a3bba79da434.png)

## Conclusions:
- Ensembling Techniques Improve the QA model performance overall across both metrics (F1 and EM)
- Hyperparameter tuning was performed but did not give increased change in performance
- Ensembling Pretrained Large scale Language models is time efficient solution 
- The Best model is Ensemble with Majority Voting with a F1-score of  0.942 and Exact match of 0.960
