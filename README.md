# _AI-BASED-RECOMMENDATION-SYSTEM


"COMPANY": CODTECH IT SOLUTIONS

"NAME": DEEPALI JICHKAR

"INTERN ID": CT04DM706

"DOMAIN": JAVA

"DURATION": 4 WEEKS

"MENTOR": NEELA SANTOSH
As part of my internship and academic learning in the field of Artificial Intelligence and Machine Learning, I developed a collaborative filtering-based AI Recommendation System using Java and Apache Mahout 0.9, an open-source machine learning library designed to build scalable, data-driven applications.

This system is designed to provide personalized item recommendations—such as movies—to users based on their preferences and the preferences of similar users. The technique used is User-Based Collaborative Filtering, one of the most widely used and effective methods in recommender systems.

The primary objective of this project was to read user-item rating data from a CSV file and then use the Apache Mahout library to process that data and generate meaningful recommendations for users who have not yet interacted with certain items. For this, I used the FileDataModel class provided by Mahout to load the data from movies.csv. The CSV contained user IDs, item IDs (movies), and their respective ratings.

I utilized the GenericUserBasedRecommender class to build the recommendation engine. It works by identifying users with similar tastes using a similarity metric and then suggesting items that those similar users have liked or rated highly. I used Pearson Correlation Similarity to compute the closeness between users and NearestNUserNeighborhood to find the top similar users to a target user.

To ensure the system worked correctly, I used a small dataset with 4 users and 12 user-item interactions. The system was able to process the file, identify the users, calculate similarities, and recommend an item for a specific user that they had not rated yet.

Key Technologies and Libraries Used:
Java – Core programming language

Apache Mahout 0.9 – For building the recommendation algorithm

Guava 31.1-jre – Required by Mahout for internal utilities

SLF4J (Simple Logging Facade for Java) – Logging framework

Apache Commons Math3 – For mathematical operations used internally by Mahout

JARs included:

mahout-core-0.9.jar

mahout-common-0.9.jar

mahout-math-0.9.jar

guava.jar

slf4j-api.jar

slf4j-simple.jar

commons-math3-3.6.1.jar

#output

<img width="1728" height="378" alt="Image" src="https://github.com/user-attachments/assets/410a4aef-f723-466e-b230-dc3323a80cce" />
