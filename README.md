# Data_Science_Final_Project


###### Ariel University, Israel || Semester A 2020-2021 

### __Datasets used in the project:__

>  **Classification - PAMAP2**
> 
> The PAMAP2 Physical Activity Monitoring dataset contains data of 24 different physical activities 
> (such as walking, cycling, playing soccer, etc.), performed by some subjects wearing 3 inertial measurement units and a heart rate monitor. 
> The dataset can be used for activity recognition and intensity estimation while developing and applying algorithms 
> of data processing, segmentation, feature extraction, and classification 
>
> [Dataset](https://www.kaggle.com/avrahamcalev/time-series-models-pamap2-dataset)
>
> ![unnamed](https://user-images.githubusercontent.com/73881872/110826136-72a7ad80-829d-11eb-8364-ddaeb7487934.jpg)

>  **Regression - Home Depot Product Search Relevance**
> 
> This data set contains several products and real customer search terms from Home Depot's website. 
> In this Assignment, we need to predict a relevance score for the provided combinations of search terms and products 
> (first, character level, and then word/character-combination level). 
> To create the ground truth labels, Home Depot has crowdsourced the search/product pairs to multiple human raters. 
>
> [Dataset](https://www.kaggle.com/c/home-depot-product-search-relevance/data?select=product_descriptions.csv.zip)
>
> ![Investor-Conference-2017_Header](https://user-images.githubusercontent.com/73881872/110826173-7b987f00-829d-11eb-84f5-8c40bc9ab822.jpg)


###### Ariel University, Israel || Semester B 2021 

### **Overview**
 
This project is the final project of the Data Science course of Ariel University and was made for study purposes.
In this project, we walked through machine learning from basic models to more advanced one.
In the project, I tried to move forward along with the book (Hands-on Machine Learning) and slowly improve the models.

### **This project was built from 4 parts:**
 
> **Part 1 - Improving the classification project from last semester:**
>
>  _Old results:_
> 
> | Model  | Accuracy |
> | ------------- | ------------- |
> | KNN  | 97.68%  |
> | RandomForestClassifier  | 97.45%  |
> 
> _New results:_
> | Model  | Accuracy |
> | ------------- | ------------- |
> | Voting Hard  | 97.51%  |
> | Voting Soft  | 97.51%  |
> | DecisionTree  | 98.10%  |
> | AdaBoost  | 98.10%  |
> 
> [Click here for Dataset](https://www.kaggle.com/avrahamcalev/time-series-models-pamap2-dataset)
> 
> <img src="https://user-images.githubusercontent.com/73881872/110826136-72a7ad80-829d-11eb-8364-ddaeb7487934.jpg" width="800" height="200">

> **Part 2 - Prediction of Fashion-MNIST Dataset:**
>
> In this part of the project, we were required to identify images of clothes by using pixels.
> So to reduce the problem we used PCA so that instead of processing 784 pixels it processed only 100.
> To predict the clothes in the testing set we used different algorithms: 
> simple models like KNN, logistic regression, SVC. 
> and some ensemble learning models like a voting classifier, random forest, and AdaBoost.
>
> | Model  | Accuracy | Accuracy with PCA |
> | ------------- | ------------- | ------------- |
> | KNN  | 85.54%  | 86.28% |
> | Logistic Regression  | 84.12%  | 83.96% |
> | Gaussian Naive Bayes  | 58.56%  | 75.87% |
> | Decision Tree  | 78.53%  | 76.09% |
> | SVC  | 88.28%  | 88.44%  |
> | Voting Hard  |   | 87.97% |
> | Voting Soft  |   | 88.27% |
> | Random Forest  | 75.34% | 74.35% |
> | AdaBoost  | 79.15% | 76.26% |
>
> [Click herefor more Information](https://github.com/zalandoresearch/fashion-mnist)
>
>  <img src="https://res.cloudinary.com/practicaldev/image/fetch/s--s6xGmaZX--/c_imagga_scale,f_auto,fl_progressive,h_900,q_auto,w_1600/https://raw.githubusercontent.com/zalandoresearch/fashion-mnist/master/doc/img/fashion-mnist-sprite.png" width="800" height="200">


> **Part 3 - Prediction of Dogs vs. Cats dataset:** 
>
> The Dogs vs. Cats dataset is a standard computer vision dataset that involves classifying photos as either containing a dog or cat.
> 
> * The train folder contains 25,000 images of dogs and cats, and the test folder contains 12,500 images.
> * Each image has a different size. I resized the images to 50 pixels in height and 50 pixels in width.
> * Each pixel has three colors (RGB) and ranges from 0 to 255 associated with it.
> * Each row is a separate image
> * Each value is an integer (0 to 255)
> 
> | Model  | Accuracy | Accuracy with PCA |
> | ------------- | ------------- | ------------- |
> | LogisticRegression  |  54.00%  | |
> | KNN  | 56.22%  | |
> | DecisionTree  | 55.84%  | |
> | RandomForest  | 64.56%  | 64.00% |
> | XGboost  | 63.12%  | 63.12% |
> 
> [Click here for Dataset.](https://www.kaggle.com/c/dogs-vs-cats)
> 
> <img src="https://www.madpaws.com.au/wp-content/uploads/2015/05/dogvscat_orig.jpg" width="800" height="200">
 
> **Part 4:**
>
> The purpose of the work is to classify three different situations in the way people communicate with each other. 
> 
> The first is a spontaneous (autonomous) situation in which two people move their hands freely in front of each other. 
> The second is a synchronous movement in which the two people move their hands together and the third is a movement in a single position.
> The idea is to look at the patterns of the hands and try to deduce from them whether it is a situation alone, spontaneous or synchronous.
> In this part, we get multip datasets (each one is a record of one state using a 3D camera), so first, we united the datasets into one.
> for each dataset, we took all 5 lines of recording data and combined them into one line, and ignored the first 7 seconds.
> 
> | Model  | Accuracy |
> | ------------- | ------------- | 
> | KNN | 89.94%  |
> | DecisionTree  | 91.38%  | 
> | Voting Hard  | 91.96%  |
> | Voting Soft  | 92.57%  |
> | Random Forest  | 83.42%  |
> | AdaBoost  | 91.39%  |
> 
> <img src="https://t3.ftcdn.net/jpg/00/11/09/80/360_F_11098019_i1idssoEViopv3znhszi6vVe0yggGq4o.jpg" width="800" height="200">

### **Contact:** 

__Email:__ moria1109@gmail.com
