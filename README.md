# Machine-Learning-Python
Machine Learning and Deep Learning Projects

Evangelidakis Leandros


# 1. User Identification based on walking pattern (Classification)
    (WalkingActivityID.pdf)

    Dataset from UCI Machine Learning Repository. Refers to 22 participants walking. Data gathered from smartphone's accelerometer.
    Algorithms used:
      - Support Vector Machines (SVM)
      - SVM with Stohastic Gradient Descent (SVM-SGD)
      - K-Nearest Neighbours (K-NN)
      - Random Forests (RF)
      - Deep Neural Networks (DNN)
      
    For all algorithms except DNN, Grid Search is used for hyperparameter tuning. Model evaluation is based on 10-fold Cross Validation.
    Best Results: Accuracy close to 96% (DNN)
  
  
  # 2. Sentiment Analysis using state-of-the-art algorithms (Text Classification)
    (imdb_reviews.ipynb + sentiment_analysis.pdf)
    
    Dataset from Stanford Database. Contains 50.000 movie reviews. Half of them are used for training and the other half for evaluation.
    Because of heavy duty algorithms, Goolge Colab with GPU support was used and is recommended.
    Algorithms used:
      - Naive Bayes Support Vector Machines (NBSVM)
      - FastText 
      - Bidirectional Encoder Representations from Transformers (BERT)
      - DistilBERT 
      
      For hyperparameter tuning, SGD with Warm Restarts and Cyclical Learning Rates were used.
      Best Results: Accuracy more than 94% (BERT)
      
      
      
