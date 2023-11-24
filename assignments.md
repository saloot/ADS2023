---
hide_hero: true
layout: page
hide_hero: true
show_sidebar: false
---

# How It Works!
Homeworks will be announced regularly here and in the lectures. For the homeworks, the goal is to perform what we have learned during the lactures and lab sessions on the dataset of your choice. 

* A list of available datasets are listed [here](/ADS2023/resources), but if you are interested to work on a dataset of your own, it can be arranged too. Simply send us an email and we will discuss the details. 
* After a homework is announced, you have one week to submit your results.
* The results should be in the form of a pre-compiled Jupyter notebook. For submitting, you have two options:
    * Create a Github repository and submit each week's assignment there (this is the **strongly recommended** option).
    * Otherwise, you can submit it via a Google Colab and share it with us.

* Homeworks can be done in a group of 2 (and we strongly recommend it!). 

* You will be graded according to the following criteria:
    * Notebook runs without a problem: 10%
    * It solves/addresses the problem: 55%
    * It is clear and well-commented: 40% 
        * This last part is crucial and detailed explanations are required for the submitted notebooks


* Grades will be available within 10 days.

* Late policy: For each late day, 10% penalty 

* Make sure to spend sufficient time on the assignments, since you will be asked to reproduce one of the assignments you had submitted in an in-person session during the class as well. This will account for 5% of final grade.

**Generative AI policy**: Use of ChatGPT, Bard or other similar tools are allowed and *encouraged*. However, please try to solve the assignments by yourself first, and then use prompts for ChatGPT/Bard/etc. and compare your results. If interested, you can submit both results :)

# Homeworks and Due Dates

### Assignment 1: Pandas, Colab and Kaggle
* 70 Points: Get familiar with Pandas and Jupyter/Colab/Kaggle Notebooks by completing the exercises on [this mini tutorial](https://www.kaggle.com/learn/pandas) on Kaggle (you can use [Lab Session 1's notebook](https://colab.research.google.com/drive/1Y8SpqDbunGuCnOP8inzmlfoGcfAsHC_e?usp=sharing)) as an additional reference.
    * Once completed, email us the certificate so that we can celeberate together :)
* 15 Points: Pick a dataset to work on for your homeworks (see some suggestions [here](/ADS2023/resources)).
* 15 Points: Form your groups and send us an email.

**Due date:** Monday, Mehr 17, 23:59



### Assignment 2: Exploratory Analysis and Data Cleaning
* On the database of your choice, perform Exploratory Data Analysis, Cleaning and Preprocessing.
    * 25 Points on the notebook running correctly.
    * 10 Points on the variety of topics explored on the dataset (EDA)
    * 20 Points on data cleaning (handling all missing, invalid or duplicate values)
    * 20 Points on data preprocessing and converting everything to numerical values
    * 10 Points on data normalization/standardization
    * 15 Points on having sufficient explanations and overall readability of the notebook

* **Bonus 40 Points**: Complete the exercises on [this mini tutorial](https://www.kaggle.com/learn/data-cleaning) on Kaggle.
    * Once completed, send us the certificate via **Microsoft Teams assignment page** so that we can celeberate together :)

* You can use the [lab sessions's notebook](https://colab.research.google.com/drive/1Y0EniYyhBGX5ac8b_mTV80ms56vFIMJf?usp=sharing) as a guideline.


Please hand in the *compiled* notebook (or the link to your *compiled* notebook on Google Colab/Github/Kaggle) **on the assignment page of Microsoft Teams**.

**Due date:** Monday, Wednesday 26 Merh, 23:59



### Assignment 3: Data Visualization + Web-scraping
* On the database of your choice, practice different data visualization techniques
    * 5 Points on the notebook running correctly.
    * 10 points: pie charts (5 points) and box plots (5 points)
    * 10 Points: line charts (5 points) and stacked (multiple) line charts (5 points)
    * 15 Points: bar charts (5 points), multiple bar charts (5 points) and stacked bar charts (5 points)
    * 10 points: scatter plots (5 points) and bubble charts (5 points)
    * 5 Points on showing the uncertainty (error bars) on a chart of your choice
    * 10 Points on interactive charts using Plotly and/or Bokeh
    * 15 Points on having sufficient explanations and overall readability of the notebook

    * Please Make sure that all your charts have proper **title, axis range, axis labels and legends**.
    * You can use the [lab sessions's notebook](https://colab.research.google.com/drive/1WldZ8citCfJrGJZzcMKbmgneLQ0bI3-H?usp=sharing) as a guideline.

* Web-scraping (20 points): Please write a simpel scraper to extract the following data for 50 "Samand" cars, manufactured after 1385 from the site: https://bama.ir
  
    * Price 
    * Milage
    * Color
    * Production year
    * Transmission type (manual or automatic)
    * Description

    * Plase submit your code as well as results in the form of an excel file.
    * You can use the [web-scraping notebook](https://colab.research.google.com/drive/1hmaWqEw2WIbrLBynaTo7L1Yn4oWgyHqG?usp=sharing#scrollTo=3H2H6IbNVdfR) as a guideline.

* **Bonus 40 Points**: Complete the exercises on [this mini tutorial](https://www.kaggle.com/learn/data-visualization) on Kaggle.
    * Once completed, send us the certificate via **Microsoft Teams assignment page** so that we can celeberate together :)


Please hand in the *compiled* notebook (or the link to your *compiled* notebook on Google Colab/Github/Kaggle) **on the assignment page of Microsoft Teams**.

**Due date:** Tuesday, Aban 2, 23:59


### Assignment 4: Feature Engineering
* On the database of your choice, practice different data visualization techniques
    * 10 Points on the notebook running correctly.
    * Create new features based on:
        * 15 points: ratio, binning, function of a column and combining columns
        * 10 points: date/time
        * 10 points: counts and aggregation
    * 15: feature selection based on Mutual Information
    * 10: dimensonality reduction using PCA
    * 20 Points on having sufficient explanations and overall readability of the notebook
    * 10 Points for answering this question (in Farsi or English in your notebooks): when is feature engineering a "nice to have option" and in what situations it is a "must to have"?

* **Bonus 30 Points**: Complete the exercises on [this mini tutorial](https://www.kaggle.com/learn/feature-engineering) on Kaggle.
    * Once completed, send us the certificate via **Microsoft Teams assignment page** so that we can celeberate together :)

* You can use the [lab sessions's notebook](https://colab.research.google.com/drive/1Eg_Ra6ytNL_HoL7T5VJN5QL-FQY2RAUM?usp=sharing) as a guideline.


Please hand in the *compiled* notebook (or the link to your *compiled* notebook on Google Colab/Github/Kaggle) **on the assignment page of Microsoft Teams**.

**Due date:** Tuesday, Aban 9, 23:59



### Assignment 5: Accuracy Measures
* On the database of your choice, practice measuring the following accuracy measures:
    * 15 Points on the notebook running correctly.
    * 20 Points: Regression Accuracy Metrics:
        * 5 Points: measuring Mean Squared Error (MSE)
        * 5 Points: measuring Mean Absolute Error (MAE)
        * 5 Points: measuring Mean Absolute Percentage Error (MAPE)
        * 5 Points: measuring R2 Score (MAPE)
    * 15 Points: Binary Classification Accuracy Metrics:
        * 5 Points: Precision
        * 5 Points: Recall
        * 5 Points: F1-Score
    * 25 Points: Multi-class Classification Accuracy Metrics:
        * 5 Points: Precision for each class
        * 5 Points: Recall for each class
        * 15 Points: Macro, Weigthed, Micro-averaged F1-Score
    * 15 Points on having sufficient explanations and overall readability of the notebook
    * 10 Points: Suppose we have a multi-label classification problem in the field of football, where each sample (player) can belong to some of 4 classes that we have:
        * Class 1: The player has played for the national team before
        * Class 2: The player had previous history of heart problems
        * Class 3: The player had knee injuries before
        * Class 4: The player has been the captain of the team in the past 

    What accuracy metric do you use to best capture the accuracy of classification algorithm which predicts the above classes based on some data from each player and why?
 
* To measure the above metric, you can either perform simple regression/classification using scikit-learn modules, or simply generate a random vector as the prediction and measure the difference (accuracy) between this "prediction" vector and the actual values (one of the columns of your choice).

* You can use the [lab sessions's notebook](https://colab.research.google.com/drive/1w2HkCGwNj3DWyOif8WF-7pM7pkT8XriC?usp=sharing) as a guideline.

**IMPORTANT NOTE**: In your notebook, **per cell**, please explain why you are doing that part (in natural language, Farsi or English). Also, you need to explain what you have gained/understood from that part. If you only provide code without the comments, *you will not get the full mark*.


Please hand in the *compiled* notebook (or the link to your *compiled* notebook on Google Colab/Github/Kaggle) **on the assignment page of Microsoft Teams**.

**Due date:** Monday, Tuesday 16, 23:59


### Assignment 6: Regression Methods
* On the database of your choice, practice measuring the following accuracy measures:
    * 15 Points on the notebook running correctly.
    * 10 Points: Linear Regression (**try** to reach R2-score above 0.8)
    * 10 Points: Linear Regression (**try** to reach R2-score above 0.85)
    * 10 Points: Kernel Regression (R2-score not important!)
    * 10 Points: Logistic Regression (**try** to reach with R2-score above 0.8)
    * 10 Points: Ridge Regression (**try** to reach with R2-score above 0.75)
    * 10 Points: LASSO Regression (**try** to reach with R2-score above 0.75)
    * 15 Points on having sufficient explanations and overall readability of the notebook
    * 10 Points: explain kernel trick in a few sentences and how it can be helpful in achieving better regression results.
 

* You can use the [lab sessions's notebook](https://colab.research.google.com/drive/1y8lSmzpeFl5pjEqr7Ug0AreA1ap_1I2b?usp=sharing) as a guideline.

**IMPORTANT NOTE**: In your notebook, **per cell**, please explain why you are doing that part (in natural language, Farsi or English). Also, you need to explain what you have gained/understood from that part. If you only provide code without the comments, *you will not get the full mark*.


Please hand in the *compiled* notebook (or the link to your *compiled* notebook on Google Colab/Github/Kaggle) **on the assignment page of Microsoft Teams**.

**Due date:** Friday, Aban 26, 23:59


### Assignment 7: Binary Classification Methods
* On the database of your choice, practice measuring the following accuracy measures:
    * 15 Points on the notebook running correctly.
    * 5 Points: Logistic Regression for Classification (with F1-score above 0.75)
    * 10 Points: SVM (with F1-score above 0.8)
    * 5 Points: Kernel SVM (with F1-score above 0.8)
    * 15 Points: KNN (with F1-score above 0.8)
        * 10 Points on the algorithm implementation
        * 5 Points: Tune for best number of neighbors (K)
    * 15 Points: Decision Trees (with F1-score above 0.8)
        * 10 Points on the algorithm implementation
        * 5 Points: Tune for the best maximum depth to avoid overfitting
    * 10 Points: Random Forests (with F1-score above 0.85)
    * 15 Points on having sufficient explanations and overall readability of the notebook
    * 10 Points: explain 3 techniques regualarize the training process for decision trees.

* 40 Bonus points: On the dataset we used in the lab session (for detecting diabetes), achieve an F1 score above 0.9 (on the test set) using whatever classification method you like (test set should be 20% of the whole data).

* All scores are measured on test set, which should be 20% of the whole dataset
* You can use the [lab sessions's notebook](https://colab.research.google.com/drive/1t3GcesSOkF0ZF2EQl12tpCF2LHZmsKqP?usp=sharing) as a guideline.

**IMPORTANT NOTE**: In your notebook, **per cell**, please explain why you are doing that part (in natural language, Farsi or English). Also, you need to explain what you have gained/understood from that part. If you only provide code without the comments, *you will not get the full mark*.


Please hand in the *compiled* notebook (or the link to your *compiled* notebook on Google Colab/Github/Kaggle) **on the assignment page of Microsoft Teams**.

**Due date:** Monday, Azar 3, 23:59


### Assignment 8: Multiclass Classification Methods
* On the database of your choice, perform **multiclass** classification (with at least 4 classes):
    * 15 Points on the notebook running correctly.
    * 10 Points: Multiclass SVM (with F1-score above 2.5/number_of_classes)
    * 15 Points: Multiclass Logistic Regression (with F1-score above 2.5/number_of_classes)
        * 5 Points: using OVR technique
        * 5 Points: using multinomial approach
        * 5 Points: calculate log loss for the output
    * 10 Points: Multiclass KNN (with F1-score above 2.5/number_of_classes)
        * 5 Points on the algorithm implementation
        * 5 Points: Tune for best number of neighbors (K)
    * 5 Points: Multiclass Decision Trees (with F1-score above 2.5/number_of_classes)
    * 15 Points: Boosting Techniques (with F1-score above 2.5/number_of_classes)
        * 5 Points: XGBoost
        * 5 Points: LightGBM
        * 5 Points: Adaboost or Catboost
    * 5 Points: Grid search to tune one of the boosting methods above
    * 15 Points on having sufficient explanations and overall readability of the notebook
    * 10 Points: Please explain how KNN and decision trees can be extended to multi-label classification problems.
 
* 30 Bonus points: On the dataset we used in the lab session (for predicting the position of the players being one of possible *12*), achieve an F1 score above 0.6 (on the test set) using whatever classification method you like (test set should be 20% of the whole data).

* All scores are measured on test set, which should be 20% of the whole dataset
* You can use the [lab sessions's notebook](https://colab.research.google.com/drive/1Z986y6rbZ1pAvNe8qNGRMC6YEUlThFBs?usp=sharing) as a guideline.

**IMPORTANT NOTE**: In your notebook, **per cell**, please explain why you are doing that part (in natural language, Farsi or English). Also, you need to explain what you have gained/understood from that part. If you only provide code without the comments, *you will not get the full mark*.


Please hand in the *compiled* notebook (or the link to your *compiled* notebook on Google Colab/Github/Kaggle) **on the assignment page of Microsoft Teams**.

**Due date:** Friday, Azar 10, 23:59