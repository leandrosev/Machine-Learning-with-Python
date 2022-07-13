# Machine-Learning-with-Python
Machine Learning and Deep Learning Projects

Evangelidakis Leandros


# 1. User Identification based on walking pattern (Classification)
    (WalkingActivityID.pdf (Greek), AccelerometerDataset.ipynb (best run using Google Colab) )

    Dataset from UCI Machine Learning Repository. Refers to 22 participants walking. Data gathered from smartphone's accelerometer.
    Algorithms used:
      - Support Vector Machines (SVM)
      - SVM with Stohastic Gradient Descent (SVM-SGD)
      - K-Nearest Neighbours (K-NN)
      - Random Forests (RF)
      - Deep Neural Networks (DNN)
      
    For all algorithms except DNN, Grid Search is used for hyperparameter tuning. Model evaluation is based on 10-fold Cross Validation.
    Best Results: Accuracy close to 96% (DNN)
    
   ![results](https://i.ibb.co/CnL72C5/results.png)  
  
  # 2. Sentiment Analysis using state-of-the-art algorithms (Text Classification)
    (imdb_reviews.ipynb )
    
    Dataset from Stanford Database. Contains 50.000 movie reviews. Half of them are used for training and the other half for evaluation.
    Because of heavy duty algorithms, Goolge Colab with GPU support was used and is recommended.
    Algorithms used:
      - Naive Bayes Support Vector Machines (NBSVM)
      - FastText 
      - Bidirectional Encoder Representations from Transformers (BERT)
      - DistilBERT 
      
      For hyperparameter tuning, SGD with Warm Restarts and Cyclical Learning Rates were used.
      Best Results: Accuracy more than 94% (BERT)
   
  ![sentiment](https://tinypic.host/images/2022/07/14/table.png)
      
   # 3. Auction sales analysis. Predicting Closing Price, probability of selling an item and Starting Bid price optimization
    (auction_sales.ipynb (Greek) )
    
    Dataset from Ebay. Contains auction data of 12 popular items, from 150 users.
    Algorithms used:
        -  Linear, Ridge and Lasso Regression
        -  Logistic Regression
        -  Random Forests and Stohastic Gradient Descent Regresors
        -  Random Forests, SVM and kNN Classifiers
        
    For hyperparameter tuning, Grid-Search was used.     
        
   Random Forest predictions:
   ![rf](https://i.ibb.co/6gLbY0b/rf.png)
   
   Model Comparison:
   
   ![models](https://uc9be965d01f91f994fb9b2a2378.previews.dropboxusercontent.com/p/thumb/ABnoTHerAKz1tXBuRBvzhThbTFSDqF4TgkN6NKwXNFwpZvtKZ0_7Jq-C22_c0_XxDcfo-y_4AO1n3YaKkuti76hGh25-0kVyV4ab5qnFRuC20S5jS5JzoFOJWujrx1bWtjbkvwrhjc26LU8nxr2sCvlgJM8_whaLgFQTrVweUMCywUXQ3xtdjRnKB-hmyPQvPOWcXTIVzh_ZxFUh9iA2pSc0j--zXGFjIpDhUIdbpe_qeIifrv3AKqGrkDlDQ255CF1HHqRYVnZ_dIuCRgeUoRENEWXMU4R7Mi4SXAAKL9eP-WxjlDGWzIsLJehbJ3qkZQ1jZMHnuhr-SS_OFqn4K01x8SAGbHiCP69OLxXhIRO6Wry3FXJTcbLTJMdLW8r5VLrx1aqorqdsjz4_ErKvaRprs9gKCjuO6jsalOaQWAuGaQ/p.png)
   
