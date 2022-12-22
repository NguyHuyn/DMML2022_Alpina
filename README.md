<img src="documents/En-tête.png" width="1000" >



# DMML2022_Alpina
Sarah MOUGIN & Huynh phuong trang NGUYEN

## Detecting the difficulty of a french text

Our mission is to find the difficulty of the texts in the file unlabeled_data.csv, with the file traning_data.csv as source to train our different models.
The start csv files and those produced by our models are stored in the "data" folder.
The first models, such as Logistic Regression, KNN, Decision Tree Classifier, Random forest Classifier, were developed before the data cleaning process. All are stored in the file "code" > "models_without_cleaning.ipynb" .
Then, we elaborated the cleaning process, and then we reapply the models tested before. These are stored in the file "code > "model_with_cleaning.ipynb".

Explanations about the processes and our sources are detailed in the file "documentation" > doc.pdf

## Results

We obtained the best accuracy with the process linear regression without cleaning, with a precision of 0.516 on Colab and 0.49 on Kaggle concerning the unlabeled_data.
The csv file of the best result of unlabeled_data is in "documents" > "Language difficulty project.pdf" 

## Video Presentation
[![Watch the video]](https://youtu.be/Uf5U5dViqrU)
