# Fashion-Product-Prediction

Problem Statement :- 
Extract textual features and image features(using VGG16 model) of different products. Predict a products category by using textual and image features

Dataset Link :- 
https://www.kaggle.com/paramaggarwal/fashion-product-images-dataset

To solve this task following steps were followed.

	Reading json files and extracting product data from json files
	Preprocessing the extracted data, such as removal of html tags, removal of stopwords, etc from description and display name of products
	Analysis on different features describing how much different values they can take for each class
	Featuring data using one hot encoding and bag of words encoding
	Modelling data using Logistic Regression, Random Forest and XGBoost
	Comparison of different models using Log loss
