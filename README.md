# Multiple-Cancer-Type-Prediction-with-TCGA-PanCancer-Atlas-data

## (Due to github file size limitation, only files that smaller than 25MB were uploaded)

In this project, I tried to predict different cancers based on the gene expression data.

I first downloaded gene expression data of ten different kinds of cancers from the TCGA database (The Cancer Genome Atlas Program). A total of 20,532 gene expression profile were sequenced for each patient.

Then, I prepared the data by selecting the first 100 patients as a training dataset and 20 patients (101-120 patients) as a testing dataset.

Thirdly, I fit the training data with different machine learning models.

Finally, I compared the accuracy of different models and achieved 95% accuracy with the Random Forest model, which is a pretty good result in the in vitro diagnostics field.
