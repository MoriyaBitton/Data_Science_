# Data Science

__________________________________________________________________________________________________________

## Teaching assistant

###### Ariel University, Israel || Semester A, 2022-2023 

### [Syllabus]()

### Code - Python
* [Agglomerative Clustering]()
* [Decison Tree - Classification]()
* [Hello Numpy]()
* [KNN - Classification]()
* [Linear Regression - Regression]()
* [SVM - Cross Validation]()

### Email To Contact: 
moria1109@gmail.com

__________________________________________________________________________________________________________

## Final Project - Part A

###### Ariel University, Israel || Semester A, 2020-2021 

### Classification Datasets - [PAMAP2](https://www.kaggle.com/avrahamcalev/time-series-models-pamap2-dataset):

The PAMAP2 Physical Activity Monitoring dataset contains data of 24 different physical activities (such as walking, cycling, playing soccer, etc.), performed by some subjects wearing 3 inertial measurement units and a heart rate monitor. The dataset can be used for activity recognition and intensity estimation while developing and applying algorithms of data processing, segmentation, feature extraction, and classification. 
![unnamed](https://user-images.githubusercontent.com/73881872/110826136-72a7ad80-829d-11eb-8364-ddaeb7487934.jpg)

### Regression Datasets - [Home Depot Product Search Relevance](https://www.kaggle.com/c/home-depot-product-search-relevance/data?select=product_descriptions.csv.zip):

This data set contains several products and real customer search terms from Home Depot's website. In this Assignment, we need to predict a relevance score for the provided combinations of search terms and products (first, character level, and then word/character-combination level). To create the ground truth labels, Home Depot has crowdsourced the search/product pairs to multiple human raters. 
![Investor-Conference-2017_Header](https://user-images.githubusercontent.com/73881872/110826173-7b987f00-829d-11eb-84f5-8c40bc9ab822.jpg)
 
_____________________________________________________

## Final Project - Part B

###### Ariel University, Israel || Semester, B 2021 
  
The project, which consists of 4 parts, was made for my final Data Science course at Ariel University. This project covered machine learning from the basics to more advanced models. I followed the book's instructions (Hands-on Machine Learning) and slowly refined the models as I worked on the project.

### Part 1 - Improving the classification project from last semester:

  _Old results:_
 | Model  | Accuracy |
 | ------------- | ------------- |
 | KNN  | 97.68%  |
 | RandomForestClassifier  | 97.45%  |
 
 _New results:_
 | Model  | Accuracy |
 | ------------- | ------------- |
 | Voting Hard  | 97.51%  |
 | Voting Soft  | 97.51%  |
 | DecisionTree  | 98.10%  |
 | AdaBoost  | 98.10%  |

### Part 2 - Prediction of [Fashion-MNIST](https://github.com/zalandoresearch/fashion-mnist) Dataset:

 By analyzing pixels, we were able to identify clothes images. 
 Therefore, to reduce the problem, we used PCA to process only 100 pixels instead of 784. 
 We used different algorithms to predict the clothes in the testing set: KNNs, logistic regressions, and SVCs. 
 Several ensemble learning models, such as a voting classifier, random forest, and AdaBoost, are also available.

 | Model  | Accuracy | Accuracy with PCA |
 | ------------- | ------------- | ------------- |
 | KNN  | 85.54%  | 86.28% |
 | Logistic Regression  | 84.12%  | 83.96% |
 | Gaussian Naive Bayes  | 58.56%  | 75.87% |
 | Decision Tree  | 78.53%  | 76.09% |
 | SVC  | 88.28%  | 88.44%  |
 | Voting Hard  |   | 87.97% |
 | Voting Soft  |   | 88.27% |
 | Random Forest  | 75.34% | 74.35% |
 | AdaBoost  | 79.15% | 76.26% |

  <img src="https://res.cloudinary.com/practicaldev/image/fetch/s--s6xGmaZX--/c_imagga_scale,f_auto,fl_progressive,h_900,q_auto,w_1600/https://raw.githubusercontent.com/zalandoresearch/fashion-mnist/master/doc/img/fashion-mnist-sprite.png" width="800" height="200">
 
### Part 3 - Prediction of [Dogs vs. Cats](https://www.kaggle.com/c/dogs-vs-cats) Dataset:
 
 * The train folder contains 25,000 images of dogs and cats, and the test folder contains 12,500 images.
 * Each image has a different size. I resized the images to 50 pixels in height and 50 pixels in width.
 * Each pixel has three colors (RGB) and ranges from 0 to 255 associated with it.
 * Each row is a separate image
 * Each value is an integer (0 to 255)
 
 | Model  | Accuracy | Accuracy with PCA |
 | ------------- | ------------- | ------------- |
 | LogisticRegression  |  54.00%  | |
 | KNN  | 56.22%  | |
 | DecisionTree  | 55.84%  | |
 | RandomForest  | 64.56%  | 64.00% |
 | XGboost  | 63.12%  | 63.12% |
 
 <img src="https://www.madpaws.com.au/wp-content/uploads/2015/05/dogvscat_orig.jpg" width="800" height="200">
 
### Part 4:
 
 * In this work, we will classify three different situations of how people interact. The first scenario is a spontaneous (autonomous) hand movement between two people. Second, there is a synchronous movement that involves two people moving their hands together, and third, there is a single movement.
 * Using the patterns of the hands, we can determine whether the situation is spontaneous, alone or synchronous. 
 * Our first step is to unite the datasets (each one is a record of one state using a 3D camera), so we get multiple datasets in this section. For each dataset, we merged all five lines of recording data into one line, and ignored the first seven seconds.
 
 | Model  | Accuracy |
 | ------------- | ------------- | 
 | KNN | 89.94%  |
 | DecisionTree  | 91.38%  | 
 | Voting Hard  | 91.96%  |
 | Voting Soft  | 92.57%  |
 | Random Forest  | 83.42%  |
 | AdaBoost  | 91.39%  |
 
 <img src="https://t3.ftcdn.net/jpg/00/11/09/80/360_F_11098019_i1idssoEViopv3znhszi6vVe0yggGq4o.jpg" width="800" height="200">
