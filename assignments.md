---
hide_hero: true
layout: page
hide_hero: true
show_sidebar: false
---

# How It Works!
Homeworks will be announced regularly here and in the lectures. For the homeworks, the goal is to perform what we have learned during the lactures and lab sessions on the dataset of your choice. 

* A list of available datasets are listed [here](/ADS2022/resources), but if you are interested to work on a dataset of your own, it can be arranged too. Simply send us an email and we will discuss the details. 
* After a homework is announced, you have one week to submit your results.
* The results should be in the form of a pre-compiled Jupyter notebook. For submitting, you have two options:
    * Create a Github repository and submit each week's assignment there (this is the **strongly recommended** option).
    * Otherwise, you can submit it via a Google Colab and share it with us.

* Homeworks can be done in a group of 2 (and we strongly recommend it!). 

* You will be graded according to the following criteria:
    * Notebook runs without a problem: 25%
    * It solves/addresses the problem: 60%
    * It is clear and well-commented: 15%


* Grades will be available within 10 days.

* Late policy: For each late day, 10% penalty 

* Make sure to spend sufficient time on the assignments, since you will be asked to reproduce one of the assignments you had submitted in an in-person session during the class as well. This will account for 5% of final grade.

# Homeworks and Due Dates

### Assignment 1: Pandas, Colab and Kaggle
* 70 Points: Get familiar with Pandas and Jupyter/Colab/Kaggle Notebooks by completing the exercises on [this mini tutorial](https://www.kaggle.com/learn/pandas) on Kaggle (you can use [Lab Session 1's notebook](https://colab.research.google.com/drive/1L8SU21inMVdB0OpXq2-dX-zNnjCPXRJY?usp=sharing)) as an additional reference.
    * Once completed, email us the certificate so that we can celeberate together :)
* 15 Points: Pick a dataset to work on for your homeworks (see some suggestions [here](/ADS2022/resources)).
* 15 Points: Form your groups and send us an email.

**Due date:** Monday, Mehr 2, 23:59



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

* You can use the [lab sessions's notebook](https://colab.research.google.com/drive/1pkdTMdJvUNr_5lpX7JY7U6-sofm2kKS7?usp=sharing) as a guideline.


Please hand in the *compiled* notebook (or the link to your *compiled* notebook on Google Colab/Github/Kaggle) **on the assignment page of Microsoft Teams**.

**Due date:** Monday, Mehr 25, 23:59


### Assignment 3: Data Visualization
* On the database of your choice, practice different data visualization techniques
    * 25 Points on the notebook running correctly.
    * 10 points: pie charts (5 points) and box plots (5 points)
    * 10 Points: line charts (5 points) and stacked (multiple) line charts (5 points)
    * 15 Points: bar charts (5 points), multiple bar charts (5 points) and stacked bar charts (5 points)
    * 10 points: scatter plots (5 points) and bubble charts (5 points)
    * 5 Points on showing the uncertainty (error bars) on a chart of your choice
    * 10 Points on interactive charts using Plotly and/or Bokeh
    * 15 Points on having sufficient explanations and overall readability of the notebook

* **Bonus 40 Points**: Complete the exercises on [this mini tutorial](https://www.kaggle.com/learn/data-visualization) on Kaggle.
    * Once completed, send us the certificate via **Microsoft Teams assignment page** so that we can celeberate together :)

* Please Make sure that all your charts have proper **title, axis range, axis labels and legends**.

* You can use the [lab sessions's notebook](https://colab.research.google.com/drive/1be5YCofbcpgy3r6pOebiN8aWFAS46TlT?usp=sharing) as a guideline.


Please hand in the *compiled* notebook (or the link to your *compiled* notebook on Google Colab/Github/Kaggle) **on the assignment page of Microsoft Teams**.

**Due date:** Monday, Aban 2, 23:59

### Assignment 4: Feature Engineering
* On the database of your choice, practice different data visualization techniques
    * 25 Points on the notebook running correctly.
    * Create new features based on:
        * 15 points: ratio, binning, function of a column and combining columns
        * 10 points: date/time
        * 10 points: counts and aggregation
    * 15: feature selection based on Mutual Information
    * 10: dimensonality reduction using PCA
    * 15 Points on having sufficient explanations and overall readability of the notebook

* **Bonus 40 Points**: Complete the exercises on [this mini tutorial](https://www.kaggle.com/learn/feature-engineering) on Kaggle.
    * Once completed, send us the certificate via **Microsoft Teams assignment page** so that we can celeberate together :)

* You can use the [lab sessions's notebook](https://colab.research.google.com/drive/1luKBWJoz4SpF6JU8-LLCyKm8Sx5x2DwB?usp=sharing) as a guideline.


Please hand in the *compiled* notebook (or the link to your *compiled* notebook on Google Colab/Github/Kaggle) **on the assignment page of Microsoft Teams**.

**Due date:** Monday, Aban 9, 23:59



### Assignment 5: Accuracy Measures
* On the database of your choice, practice measuring the following accuracy measures:
    * 25 Points on the notebook running correctly.
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
 
* To measure the above metric, you can either perform simple regression/classification using scikit-learn modules, or simply generate a random vector as the prediction and measure the difference (accuracy) between this "prediction" vector and the actual values (one of the columns of your choice).

* You can use the [lab sessions's notebook](https://colab.research.google.com/drive/1QjHyYqEht-1ppMK-3sIy8mFHHfeNpBMd?usp=sharing) as a guideline.

**IMPORTANT NOTE**: In your notebook, **per cell**, please explain why you are doing that part (in natural language, Farsi or English). Also, you need to explain what you have gained/understood from that part. If you only provide code without the comments, *you will not get the full mark*.


Please hand in the *compiled* notebook (or the link to your *compiled* notebook on Google Colab/Github/Kaggle) **on the assignment page of Microsoft Teams**.

**Due date:** Monday, Aban 16, 23:59


### Assignment 6: Regression Methods
* On the database of your choice, practice measuring the following accuracy measures:
    * 25 Points on the notebook running correctly.
    * 10 Points: Linear Regression (with R2-score above 0.8)
    * 10 Points: Linear Regression (with R2-score above 0.85)
    * 10 Points: Kernel Regression (R2-score not important!)
    * 10 Points: Logistic Regression (with R2-score above 0.8)
    * 10 Points: Ridge Regression (with R2-score above 0.8)
    * 10 Points: LASSO Regression (with R2-score above 0.8)
    * 15 Points on having sufficient explanations and overall readability of the notebook
 

* You can use the [lab sessions's notebook](https://colab.research.google.com/drive/1Qos7Lct-3T3cUZNVMt7k5o9tg39ZZyln?usp=sharing) as a guideline.

**IMPORTANT NOTE**: In your notebook, **per cell**, please explain why you are doing that part (in natural language, Farsi or English). Also, you need to explain what you have gained/understood from that part. If you only provide code without the comments, *you will not get the full mark*.


Please hand in the *compiled* notebook (or the link to your *compiled* notebook on Google Colab/Github/Kaggle) **on the assignment page of Microsoft Teams**.

**Due date:** Monday, Aban 23, 23:59


### Assignment 7: Binary Classification Methods
* On the database of your choice, practice measuring the following accuracy measures:
    * 25 Points on the notebook running correctly.
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

* 40 Bonus points: On the dataset we used in the lab session (for detecting diabetes), achieve an F1 score above 0.9 (on the test set) using whatever classification method you like (test set should be 20% of the whole data).

* All scores are measured on test set, which should be 20% of the whole dataset
* You can use the [lab sessions's notebook](https://colab.research.google.com/drive/1we-F7fXFYMKs_8OfgA-N4lSVdYyvbKxG?usp=sharing) as a guideline.

**IMPORTANT NOTE**: In your notebook, **per cell**, please explain why you are doing that part (in natural language, Farsi or English). Also, you need to explain what you have gained/understood from that part. If you only provide code without the comments, *you will not get the full mark*.


Please hand in the *compiled* notebook (or the link to your *compiled* notebook on Google Colab/Github/Kaggle) **on the assignment page of Microsoft Teams**.

**Due date:** Monday, Aban 30, 23:59


### Assignment 8: Multiclass Classification Methods
* On the database of your choice, perform **multiclass** classification (with at least 4 classes):
    * 25 Points on the notebook running correctly.
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
 
* 30 Bonus points: On the dataset we used in the lab session (for predicting the position of the players being one of possible *12*), achieve an F1 score above 0.6 (on the test set) using whatever classification method you like (test set should be 20% of the whole data).

* All scores are measured on test set, which should be 20% of the whole dataset
* You can use the [lab sessions's notebook](https://colab.research.google.com/drive/1oOkdOwlo191R21jirGCTazJGxK9__gdr?usp=sharing) as a guideline.

**IMPORTANT NOTE**: In your notebook, **per cell**, please explain why you are doing that part (in natural language, Farsi or English). Also, you need to explain what you have gained/understood from that part. If you only provide code without the comments, *you will not get the full mark*.


Please hand in the *compiled* notebook (or the link to your *compiled* notebook on Google Colab/Github/Kaggle) **on the assignment page of Microsoft Teams**.

**Due date:** Monday, Azar 7, 23:59
