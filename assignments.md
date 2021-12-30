---
hide_hero: true
layout: page
hide_hero: true
show_sidebar: false
---

# How It Works!
Homeworks will be announced regularly here and in the lectures. For the homeworks, the goal is to perform what we have learned during the lactures and lab sessions on the dataset of your choice. 

* A list of available datasets are listed [here](/ADS2021/resources), but if you are interested to work on a dataset of your own, it can be arranged too. Simply send us an email and we will discuss the details. 
* After a homework is announced, you have one week to submit your results.
* The results should be in the form of a pre-compiled Jupyter notebook (so you can do it in R if you like). For submitting, you have two options:
    * Create a Github repository and submit each week's assignment there (this is the **strongly recommended** option).
    * Otherwise, you can submit it via a Google Colab and share it with us.

* Homeworks can be done in a group of 2 (and we strongly recommend it!). 

* You will be graded according to the following criteria:
    * Notebook runs without a problem: 25%
    * It solves/addresses the problem: 60%
    * It is clear and well-commented: 15%


* Grades will be available within 10 days.

* Late policy: For each late day, 10% penalty 

# Homeworks and Due Dates

### Assignment 1: Pandas, Colab and Kaggle
* 70 Points: Get familiar with Pandas and Jupyter/Colab/Kaggle Notebooks by completing the exercises on [this mini tutorial](https://www.kaggle.com/learn/pandas) on Kaggle (you can use [Lab Session 1's notebook](https://colab.research.google.com/drive/1d2EkG4eZM_fU44yB7yXff7L-I0R4L9g0?usp=sharing)) as an additional reference.
    * Once completed, email us the certificate so that we can celeberate together :)
* 15 Points: Pick a dataset to work on for your homeworks (see some suggestions [here](/ADS2021/resources)).
* 15 Points: Form your groups and send us an email (.

**Due date:** Monday, Mehr 12, 23:59

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

* You can use the [lab sessions's notebook](https://colab.research.google.com/drive/1jOnp5rpJUkE4HGYbO-LZGZwFOVfGae7H?usp=sharing) as a guideline.


Please hand in the *compiled* notebook (or the link to your *compiled* notebook on Google Colab/Github/Kaggle) **on the assignment page of Microsoft Teams**.

**Due date:** Saturday, Mehr 24, 23:59


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

* You can use the [lab sessions's notebook](https://colab.research.google.com/drive/1fzVLZ5Ch1RwRFQgs65ZnhbYxDbrttdG-?usp=sharing) as a guideline.


Please hand in the *compiled* notebook (or the link to your *compiled* notebook on Google Colab/Github/Kaggle) **on the assignment page of Microsoft Teams**.

**Due date:** Monday, Aban 3, 23:59


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

* You can use the [lab sessions's notebook](https://colab.research.google.com/drive/1L7BAupNGg0QwkiOpx9tgNMuraR5J9thY?usp=sharing) as a guideline.


Please hand in the *compiled* notebook (or the link to your *compiled* notebook on Google Colab/Github/Kaggle) **on the assignment page of Microsoft Teams**.

**Due date:** Monday, Aban 10, 23:59


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

* You can use the [lab sessions's notebook](https://colab.research.google.com/drive/1FnsgqFm7UygRhUXnPVRn3cYAN_1as3a6?usp=sharing) as a guideline.

**IMPORTANT NOTE**: In your notebook, **per cell**, please explain why you are doing that part (in natural language, Farsi or English). Also, you need to explain what you have gained/understood from that part. If you only provide code without the comments, *you will not get the full mark*.


Please hand in the *compiled* notebook (or the link to your *compiled* notebook on Google Colab/Github/Kaggle) **on the assignment page of Microsoft Teams**.

**Due date:** Monday, Aban 17, 23:59


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
 

* You can use the [lab sessions's notebook](https://colab.research.google.com/drive/10cFiEIoORgXdyHISPJw-A2jsV-KZRAGx?usp=sharing) as a guideline.

**IMPORTANT NOTE**: In your notebook, **per cell**, please explain why you are doing that part (in natural language, Farsi or English). Also, you need to explain what you have gained/understood from that part. If you only provide code without the comments, *you will not get the full mark*.


Please hand in the *compiled* notebook (or the link to your *compiled* notebook on Google Colab/Github/Kaggle) **on the assignment page of Microsoft Teams**.

**Due date:** Monday, Aban 25, 23:59


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
* You can use the [lab sessions's notebook](https://colab.research.google.com/drive/1NboSeFrXDwdKvETM7bsF628aPwKo2nPS?usp=sharing) as a guideline.

**IMPORTANT NOTE**: In your notebook, **per cell**, please explain why you are doing that part (in natural language, Farsi or English). Also, you need to explain what you have gained/understood from that part. If you only provide code without the comments, *you will not get the full mark*.


Please hand in the *compiled* notebook (or the link to your *compiled* notebook on Google Colab/Github/Kaggle) **on the assignment page of Microsoft Teams**.

**Due date:** Monday, Azar 1, 23:59


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
* You can use the [lab sessions's notebook](https://colab.research.google.com/drive/1BUZC2fZN28KRwOLUWgFIZueUK78BUkZX?usp=sharing) as a guideline.

**IMPORTANT NOTE**: In your notebook, **per cell**, please explain why you are doing that part (in natural language, Farsi or English). Also, you need to explain what you have gained/understood from that part. If you only provide code without the comments, *you will not get the full mark*.


Please hand in the *compiled* notebook (or the link to your *compiled* notebook on Google Colab/Github/Kaggle) **on the assignment page of Microsoft Teams**.

**Due date:** Monday, Azar 8, 23:59


### Assignment 9: Neural Networks
* On the database of your choice, practice using neural networks:
    * 25 Points on the notebook running correctly.
    * 10 Points: Multilayer Perceptron with Scikit-Learn
        * 5 Points: binary classification with F1-score above 0.75
        * 5 Points: regression with R2-score above 0.8
    * 15 Points: 4-layer feedforward network with Keras
        * 10 Points: binary classification with F1-score above 0.75
        * 5 Points: regression with R2-score above 0.8
    * 20 Points: 4-layer feedforward network with PyTorch
        * 10 Points: binary classification with F1-score above 0.75
        * 10 Points: regression with R2-score above 0.8
    * 15 Points: 4-layer **non-sequential** feedforward network with Keras
        * 5 Points: binary classification with F1-score above 0.75
        * 5 Points: regression with R2-score above 0.8
    
    * 15 Points on having sufficient explanations and overall readability of the notebook
    
    * Bonus 15 Points (if dataset has time-series like features) 3-layer Recurrent Neural Network with Keras
        * 10 Points: binary classification with F1-score above 0.75
        * 5 Points: regression with R2-score above 0.8

* All scores are measured on test set, which should be 20% of the whole dataset
* You can use the [lab sessions's notebook](https://colab.research.google.com/drive/1NX4NnTOxEVQkNRBadezTvMI9o5t6NSC3?usp=sharing) as a guideline.

**IMPORTANT NOTE**: In your notebook, **per cell**, please explain why you are doing that part (in natural language, Farsi or English). Also, you need to explain what you have gained/understood from that part. If you only provide code without the comments, *you will not get the full mark*.


Please hand in the *compiled* notebook (or the link to your *compiled* notebook on Google Colab/Github/Kaggle) **on the assignment page of Microsoft Teams**.

**Due date:** Monday, Azar 22, 23:59


### Assignment 10: Deep Neural Networks
* On the database of your choice, practice working with neural networks and tuning them
* You can use the neural networ you developed in the previous assignment (using Keras)
* The problem you work on in this exercise can be either regression or classification, whichever you find more suitable (one of them is sufficient)
* For each of the following tasks, please **try at least 5 different options**
* In all cases, please use 4-fold cross validation and use the average validation accuracy as the measure to tune.
    * 25 Points on the notebook running correctly.
    * 10 Points: Tuning for optimization algorithm (e.g. SGD, ADAM, etc.)
    * 5 Points: Tuning learning rate 
    * 5 Points: Tuning learning rate decay
    * 5 Points: Tuning batch size
    * 5 Points: Tuning activation functions
    * 5 Points: Tuning weight intilaization
    * 10 Points: Trying multiple layers and number of neurons (e.g. playing with network architecture)
    * 5 Points: Tuning l1 and l2 regularization in the weights
    * 5 Points: Tuning l1 and l2 regularization in the activity_kernel
    * 5 Points: Tuning dropout rate
    * 15 Points on having sufficient explanations and overall readability of the notebook

* All scores are measured on test set, which should be 20% of the whole dataset
* You can use the [lab sessions's notebook](https://colab.research.google.com/drive/1qB0kzFE3AcltmweOoieG0EUHM1qBEazB?usp=sharing) as a guideline.

**IMPORTANT NOTE**: In your notebook, **per cell**, please explain why you are doing that part (in natural language, Farsi or English). Also, you need to explain what you have gained/understood from that part. If you only provide code without the comments, *you will not get the full mark*.


Please hand in the *compiled* notebook (or the link to your *compiled* notebook on Google Colab/Github/Kaggle) **on the assignment page of Microsoft Teams**.

**Due date:** Monday, Azar 22, 23:59


### Assignment 11: Convolutional Neural Networks, Transfer Learning and Data Augmentation
* On the database of your choice, practice image classification using convolutional neural networks
* For each of the following tasks, please **try at least 3 different options**.
* In all cases, please use 3-fold cross validation and use the average validation accuracy as the measure to tune.
    * 25 Points on the notebook running correctly.
    * 10 Points: Creating a convolutional network with Keras (with at least two layers of convolution layer)
    * 20 Points: Tuning the above network for:
        * 5 Points: Tuning the kernel size (i.e. the size of the receptive field) for convolutional layers
        * 5 Points: Tuning the stride for convolutional layers
        * 5 Points: Tuning the pooling size (i.e. the size of the receptive field) for pooling layers
        * 5 Points: Tuning the stride for pooling layers
    
    * 10 Points: Perform data augmentation and train your model above using the ImageGenerator class 
    * 20 Points: Perform transfer learning using **two** of the available models in Keras applications (e.g. VGG19, ResNet, EfficientNet, etc.)    
    * 15 Points on having sufficient explanations and overall readability of the notebook

* You can use the [lab sessions's notebook](https://colab.research.google.com/drive/1HJnXBFS2rMro0nMYNEILZjgPq-vusU3f?usp=sharing) as a guideline.

**IMPORTANT NOTE**: In your notebook, **per cell**, please explain why you are doing that part (in natural language, Farsi or English). Also, you need to explain what you have gained/understood from that part. If you only provide code without the comments, *you will not get the full mark*.


Please hand in the *compiled* notebook (or the link to your *compiled* notebook on Google Colab/Github/Kaggle) **on the assignment page of Microsoft Teams**.

**Due date:** Monday, Azar 29, 23:59


### Assignment 12: Natural Language Processing using Deep Neural Networks
* On the database of your choice, practice NLP using deep neural networks
* In all cases, please use 3-fold cross validation and use the average validation accuracy as the measure to tune.
    * 25 Points on the notebook running correctly.
    * 15 Points: Preprocessing
        * 5 Points: Tokenization
        * 5 Points: Truncation and padding
        * 5 Points: Embdedding
    * 15 Points: create and train a network 9(at least 4 layers)
        * With RNNs
        * With LSTMs
        * With GRUs
    * 10 Points: Performance Tuning (for each of the following tasks, please **try at least 3 different options**):
        * Try different number of layers/number of recurrent units
        * Try different learning rates
        * Try different optimization methods
        * Try different batch sizes
    * 20 Points: Perform transfer learning using **two** different approaches
        * Usually, transfer learning comes in the form of different embeddings or language models.
        * You can check [this link](https://towardsdatascience.com/deep-transfer-learning-for-natural-language-processing-text-classification-with-universal-1a2c69e5baa9) or [TnesorFlow Hub](https://tfhub.dev/) to get started.
    * 15 Points on having sufficient explanations and overall readability of the notebook

* You can use the [lab sessions's notebook](https://colab.research.google.com/drive/1b77S7EAFNbaukIURUzuuc2Gl1n3s9hce?usp=sharing) as a guideline.

**IMPORTANT NOTE**: In your notebook, **per cell**, please explain why you are doing that part (in natural language, Farsi or English). Also, you need to explain what you have gained/understood from that part. If you only provide code without the comments, *you will not get the full mark*.


Please hand in the *compiled* notebook (or the link to your *compiled* notebook on Google Colab/Github/Kaggle) **on the assignment page of Microsoft Teams**.

**Due date:** Monday, Dey 13, 23:59


### Assignment 13: Autoencoders, GANs and Explainable AI
* Using the dataset for assignment 11 for image analysis:
    * 5 Points: Create a dense autoencoder
    * 10 Points: Using the convolutional architecture from assignment 11, create and train convolutional autoencoder
    * 5 Points: Create and train a denoising autoencoder

* 20 Points: Using CIFAR-10 dataset, create and train a Generative and adversarial Network (GAN).
* Explainable AI: Using the convolutional architecture from assignment 11, explain *why* the model misclassified an image using:
    * 10 Points: Grad-CAM
    * 5 Points: SHAP
    * 5 Points: LIME
    * 5 Points: Eli5

* 25 Points on the notebook running correctly.
* 15 Points on having sufficient explanations and overall readability of the notebook

* 20 Bonus Points: create and train a Variational AutoEncoder (VAE) to create images similar to Fashion MNIST dataset.

* You can use the [lab sessions's notebook](https://colab.research.google.com/drive/1rP3YU9oFrLKm5ODOxEFDHFr1ZJagVemE?usp=sharing) as a guideline.

**IMPORTANT NOTE**: In your notebook, **per cell**, please explain why you are doing that part (in natural language, Farsi or English). Also, you need to explain what you have gained/understood from that part. If you only provide code without the comments, *you will not get the full mark*.


Please hand in the *compiled* notebook (or the link to your *compiled* notebook on Google Colab/Github/Kaggle) **on the assignment page of Microsoft Teams**.

**Due date:** Monday, Dey 13, 23:59
