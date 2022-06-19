# Question pair similarity analysis using the Quora Dataset.

This project is mainly foucsed on performing text anlytics on identifying the search related results. The dataset used for the problem is taken from Kaggle. It consists of 404,290 rows and 6 columns. The description of each column is as follows <br>

-Id: unique Id for each instance <br>
-qid1: unique Id for question1 of the question pair <br>
-qid2: unique Id for question2 of the question pair <br>
-question1: the context of question1 <br>
-question2: the context of question2 <br>
-is_duplicate: the target variable, set to 1 if question1 and question2 have essentially the same meaning, and 0 otherwise. <br>
<br>
The dataset has been split into 95% and 5% for training and testing respectively. Below are the list of activities performed over the dataset and prepared model<br>

<b><h2>Data Cleaning</h2></b>
-Lowercase<br>
-Tokenize<br>
-Removing Stop Words<br>
-Lemmatization<br>
-Stemming<br>

<b><h2> Feature Extraction</h2></b>
-Cosine Similarity<br>
-Difference in Character Length<br>

<b><h2>Modelling</h2></b>
-Linear Regression<br>
-Random Forest<br>
-XGBoost<br>

<b><h2>Contributers:</b></h2>
Sai Kiran Batchu<br>
Subash Chandra Biswal<br>
Sukumar Vinnakota<br>
Kushal Reddy Chavva<br>
