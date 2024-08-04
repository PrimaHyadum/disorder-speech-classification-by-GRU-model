# Disorder speech classification by GRU model
This is my practical work for my summer internship. The algorithm is Zero Crossing Rate (ZRC). You can see the full project in my ipynb file. I use ChatGPT to do some cells in file.

I know that the dataset is really bad, but our teacher send me this one.

The Dataset link: https://www.kaggle.com/datasets/mhantor/russian-voice-dataset/data

### Model parameters:
+ Input size: 100
+ Hidden size: 128
+ Output size: 2
+ Number of layers: 2
+ Learning rate: 0.001
+ Optimizer: Adam
+ Loss Function: Cross-Entropy Loss
+ Epochs Count: 10

### Notes:
+ When the data were normalized, accuracy decreased by 5%
+ When removing silence at the beginning and end of each track accuracy decreased by 5-10%

### Evaluation
+ Accuracy: 99.12%
+ Precision: 0.98
+ F1 Score: 0.99
+ ROC AUC: 1.00
