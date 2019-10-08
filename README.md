# Instacart- Customer cart prediction and recommendation

**Team Members:** Siddartha Rao, Siddharth Kothari and Vishal Singh

**Data set:** The dataset consists of 6 files:
1)	’aisles.csv’: Contains aisle id and respective aisle name
2)	’departments.csv’: Contains department id and respec-tive aisle name
3)	’orderproductsprior.csv’: Contains transcational his-tory  of  which  product  were  purchased  in  each  order,were they reordered, and thier add to cart order id andrespective aisle name
4)	’orderproductstrain.csv’:  Contains  details  of  whichproduct were purchased in the last order of few users,were they reordered, and their add to cart order id andrespective aisle name
5)	’orders.csv’:  Contains  more  details  about  each  orderlike  day  of  week,  order  number  etc,  also tell  which set (prior, train, test) does the order belong to
6)	’products.csv’:  Contains  product  details  of  productname, their aisle and department

**Files and flow of project:** 
1)	Exploratory Data Analysis: EDA has been done in file ‘EDA.ipynb’
2)	Prediction: Two models has been build for prediction

    a.	Light GBM: The model has been build in file ‘Light GBM - feature, parameter tuning.ipynb’. The file has an output sub_lgbm which is the prediction on test data and need to be submitted in kaggle to get accuracy
    
    b.	XGBoost: The model has been build in file ‘XGBoost.ipynb’. The file has an output sub_xgb which is the prediction on test data and need to be submitted in kaggle to get accuracy
    
3)	Clustering: Clustering has three files

    a.	‘Customer Segmentation  - Product Pairs.ipynb’ – Clustering done based on product pairs
    
    b.	‘Customer Segmentation  - Aisle.ipynb’ – Clustering done based on aisle ids. Use this file’s output for recommendation
    
    c.	‘pca-product_pairs.py’ – PCA done on product pairs 
    
4)	Recommendation: The files are – 

    a.	‘Apriori.ipynb’ – Apriori algorithm was done in this file and output was used in recommendation
    
    b.	‘Recommendation.ipynb’ – output files from ‘Customer Segmentation  - Aisle.ipynb’ and ‘Apriori.ipynb’ with data set givens to create recommendation list
    

