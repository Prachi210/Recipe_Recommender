**Introduction:**
Hello, and welcome to the second part of the Food Recommender Assignment. The end objective of this assignment is to build a recipe recommender system. Recall that we had divided the project into parts. 
Part 1: Exploratory Data Analysis (EDA) and Feature Extraction from Raw Data
Part 2: Building the Recommender System
In the first part of the assignment, you extracted features and made the data ready for machine learning. In this assignment, the objective will be to create a recommender system.  You will use the Google Colab environment to write code in this assignment.   

**Problem Statement**
In this assignment, your objective is to recommend recipes to a user. You have to build a recommender system that will have to generate recommendations for given user_ids.
Recommender systems in real life are expected to come up with results instantaneously. Imagine you are surfing YouTube and the recommendations panel to the right of the screen takes 20 minutes to load. That would not be a good experience, and you might decide to use another video streaming service. In the world of recommenders, prediction latency is more important than accuracy. Moreover, the data and features these recommender systems use to make recommendations are very voluminous. The data we used for EDA in the earlier assignment is not on the same scale as the YouTube recommender's data. 
How can these recommenders serve recommendations in almost real-time while working on such voluminous data? 
Advanced algorithms. 
The advancements in recommender and deep learning algorithms are responsible for improving prediction latency. Use of big data hardware. The real-life recommenders use massive hardware clusters to train the algorithms. 
In our case, we will not be able to use deep learning or hardware on the same scale used in the industry. As a result, we will have to sub-sample the data set. 

NOTE: After completing this exercise, you might be tempted to run your machine learning algorithms on the full-scale data you used in the last assignment. We advise against it. You would have to use a large-scale cluster, impacting your AWS credits. 
The data you will work with is given below. 
You are expected to use the Spark platform to build your ML model. The algorithms you will use are ALS and K Nearest Neighbors (KNN). 
Note: Using KNN and making a hybrid recommender system will be optional. 
You will use the Google Colab environment to solve this assignment. To solve this assignment, you do not need to migrate any data from your AWS account. We have shared the new data files above. You can make a copy of the Google collab template notebooks.
You can download and submit the notebook in .ipynb format. 
If you are new to Google Colab, you can look at this starter notebook; it introduces the Colab environment. It is very similar to your Jupyter notebook. 
