# APR-Survey
A Survey on Automated Program Repair Techniques










# Dataset Overlap
The dataset overlap problem refers to the training data and test benchmark overlap. The problem may cause the model to learn the correct fix for the test sample during the training phase, which may lead to the illusion of getting good repair results.


Here we give a simple example to illustrate the dataset overlap problem. Figure 1 shows an overlapping part in the train dataset and the test benchmark (Defects4J). Therefore, the overlapping projects need to be removed from the training set during the model training process.
