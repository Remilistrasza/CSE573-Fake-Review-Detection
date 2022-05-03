# CSE 573: Fake Reviews Detection



# Dataset

[YelpZip](https://github.com/Remilistrasza/CSE573-Fake-Review-Detection/tree/main/YelpZip)



# Statistical machine learning approach

Utilized 3 different machine learning models

## Logistic Regression

### TF-IDF

| Accuracy | Precision | Recall | F1-Score |
| -------- | --------- | ------ | -------- |
| 86.74%   |   87.13%   | 99.40% |  92.86%  |



### fastText embedding


| Accuracy | Precision | Recall | F1-Score |
| -------- | --------- | ------ | -------- |
| 86.34%   |   86.52%   | 99.69% |  92.64%  |



## SVM

### TF-IDF

| Accuracy | Precision | Recall | F1-Score |
| -------- | --------- | ------ | -------- |
| 85.65%   |   85.66%  | 98.12% |  92.25%  |



### fastText embedding


| Accuracy | Precision | Recall | F1-Score |
| -------- | --------- | ------ | -------- |
| 86.14%   |   86.32%  | 99.63% |  92.73%  |



## Random Forest

### TF-IDF

| Accuracy | Precision | Recall | F1-Score |
| -------- | --------- | ------ | -------- |
| 86.30%   |   86.40%  | 99.91% |  92.63%  |



### fastText embedding


| Accuracy | Precision | Recall | F1-Score |
| -------- | --------- | ------ | -------- |
| 86.35%   |   86.86%  | 99.21% |  92.62%  |



# Deep learning



* ## BERT

  BERT base model



Code: [BERT](https://github.com/Remilistrasza/CSE573-Fake-Review-Detection/blob/main/src/Language_Model_BERT.ipynb)





| Accuracy | Precision | Recall | F1-Score |
| -------- | --------- | ------ | -------- |
| 86.87%   | 87.76%    | 98.62% | 92.87%   |



<br />

​                   


* ## RoBERTa

 RoBERTa base model



Code: [RoBERTa](https://github.com/Remilistrasza/CSE573-Fake-Review-Detection/blob/main/src/Language_Model_RoBERTa.ipynb)



| Accuracy | Precision | Recall | F1-Score |
| -------- | --------- | ------ | -------- |
| 86.99%   |  87.78%   | 98.74% |  92.94%  |