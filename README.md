# -Customer-Segmentation-Report-
 The aim of the project is to apply both supervised and unsupervised machine learning to identify potential customers for a mail-order sales company from a demographics data of Germany. 

# Project Article Link
This is the link of the article related to the project: https://medium.com/@waiganjojohn11/customer-segmentation-report-for-arvato-financial-services-a3452c99feb

# Project Summary
The aim of the project is to apply both supervised and unsupervised machine learning to identify potential customers for a mail-order sales company from a demographics data of Germany. The project will have three parts namely customer segmentation report, supervised machine learning model, and Kaggle competition. 

The goal includes four parts as follows:
1. Data pre-processing: clean and re-encode data.
2. Segmentation: use unsupervised learning techniques to create clusterings of customer and general population, and then identify the difference.
3. Prediction: use the demographic features to predict whether or not a person became a customer after a mailout campaign.
4. Use the same algorithm to predict and submit to Kaggle competition to get evaluation.

To answer these questions, first, I used different approaches to pre-process the data, and then I used unsupervised learning techniques, PCA (Principle Componets Analysis) and k-NN (k-nearest neighbor algorithm), to perform customer segmentation and to identify the core customer traits of the company.
Secondly, with demographics information for targets of a marketing campaign for the company, I used different models to predict which individuals are most likely to convert into customers.

# Installation
The following python tools/module packages is needed for this study.

python 3.6

anaconda

jupyter notebook

pandas

numpy

matplotlib

seaborn

sklearn

# Files Uploaded in Repository

The following are all file/data that needed for this project.

1. Jupyter Notebook (Arvato Project Workbook.ipynb & Arvato Project Workbook.html)-The code for the whole project is contained in these files
2. CSV file for Kaggle Competition (csvFile_KaggleCompetition.csv) - csv file prepared for Kaggle Competition

Unfortunately, I could not upload the data files for the project for confidentiality purposes.

# Summary of the Results

1. There is a proportion difference of +18.56% between customer proportion and general population proportion assigned to cluster 0. Therefore, cluster 0 over-represents customers of the company. For this reason, cluster 0 should be the top among the target customers because customers in that population are more likely to engage with the company. Other clusters that could be considered are cluster 1 and 2.
2. There is a proportion difference of -12.09% between customer proportion and general population proportion assigned to cluster 5. Therefore, cluster 5 under-represents customer data compared to general population. Other clusters that are underrepresented are clusters 3 and 4 which have proportion difference of -9.22% and -9.62% respectively. These clusters are not likely to engage the company compared to the ones that are over-represented.

# Acknowledgement

I couldn’t have finish this project without the help of a lot of people. I’d like to thank the Udacity instructors and the rest of the Udacity staff for their invaluable help. Thanks to my project mentors, for great suggestions, edits, and support.
