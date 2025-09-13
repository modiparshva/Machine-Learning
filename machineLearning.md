**Q1. Introduction to Machine Learning**



a) Define Machine Learning and explain its importance in modern computing.



* Machine Learning (ML) is a branch of AI where **computers learn patterns from data to perform tasks without explicit programming**.
* It enables **automation, enhances decision making**, and provides **personalized user experiences**.
* ML handles **large and complex data efficiently in applications** such as healthcare, finance, and fraud detection.



b) Differentiate Machine Learning from traditional programming approaches.



* Traditional Programming : Uses **fixed set of rules** written by **programmers**. Input + Program -> Output
* Machine Learning : Learns **rules from data with input and output**. Data + Output -> Model.
* ML Adapts automatically, while traditional programming requires manual changes.
* Traditional is rule-based; ML is data-driven and can handle complex patterns.



c) Role of data in ML Systems and challenges in data preparation.



* Role of Data : core to ML; Models learn from data quality and quantity to make predictions.
* Challenges :

&nbsp;	1) Missing or Inconsistent data

&nbsp;	2) Noisy data and outliers

&nbsp;	3) Data bias leading to unfair models

&nbsp;	4) Large volumes and data integration complexity

&nbsp;	5) Selecting relevant features for learning.



**Q2. Types of Machine Learning** 



a) Explain Supervised Learning with at least two real-life examples and a workflow diagram.



* Definition : In Supervised Learning, models learn from labeled data(inputs with correct outputs) to predict outcomes for new data.
* Examples: 

&nbsp;	1) Email Spam Detection :

&nbsp;		Inputs : Email text, sender info;

&nbsp;		Output : Spam / Not Spam

&nbsp;		Part of Classification

&nbsp;	2) House Price Prediction :

&nbsp;		Inputs : Size, location, age;

&nbsp;		Output : Price

&nbsp;		Part of Regression

* Common Workflow :

&nbsp;	1) Data Collection

&nbsp;	2) Data Preprocessing

&nbsp;	3) Splitting data into Training and Test sets

&nbsp;	4) Model Training (on labeled data)

&nbsp;	5) Model Evaluation (on test data)

&nbsp;	6) Prediction / Deployment



b) Explain Unsupervised Learning, including Clustering and dimensionality reduction examples.



* Definition : Unsupervised learning works with unlabeled data to find patterns, groupings, or reduce dimensions.
* Clustering Examples :

&nbsp;	1) Customer Segmentation :

&nbsp;		Algorithm : K-means groups customers based on shopping habits(no labels).

* Dimensionality Reduction Example :

&nbsp;	1) Data Visualization :

&nbsp;		Algorithm : PCA reduces high-dimensional data (thousands of features) to 2D to 3D for easier visualization.

* Other Application: Image Compression, anomaly detection.



c) Explain Reinforcement Learning with a real-world application (e.g. gaming, robotics).



* Definition : In reinforcement learning, an agent learns by interacting with its environment, receiving rewards or penalties, and optimizing its actions for maximum cumulative reward.
* Example - Robotics :

&nbsp;	1) A robotic arm learns to pick and place objects in a factory by trying different actions and getting feedback (reward for success, penalty for error).

* Example - Gaming :

&nbsp;	1) AlphaGo : Trained to play Go by playing games and learning from wins/losses, improving strategy using RL Algorithms.



d) Comparative Table : Supervised vs Unsupervised vs Reinforcement Learning.



* Data Type : Supervised Learning : Labeled Data , Unsupervised Learning : Unlabeled Data, Reinforcement Learning : Environment Feedback
* Goal : 