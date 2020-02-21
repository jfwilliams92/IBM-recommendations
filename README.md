# IBM Article Recommendations Project

## Background and Motivation

For the Udacity Data Science NanoDegree, we were charged with making articles recommendations to users of the IBM Watson Studio platform. 
Article recommendations for users will be based on data collected by IBM on the platform, including article data and user behavior data.

Data Scientists are commonly tasked with building recommendation systems for various use cases. This project, and the accompanying lessons, gave me extremely helpful real-world experience in building various types of recommendation systems.

## Tasks
For this project we were tasked with completing: 
1. Exploratory Data Analysis of the article and user data
2. Rank Based Recommendations - popularity based recommendations
3. User-User Collaborative Filtering - we explored measures of similarity between users based on their behavior, and used similar users' articles as recommendations
4. Content-Based Recommendation (OPTIONAL) - This portion was optional but I chose to undertake it.
    * I performed NLP Feature Extraction on the article titles, descriptions, and bodies separately
    * Then, I clustered articles together using sklearn's `KMeans` on the extracted text features
    * Finally, I used a simple Multi-Armed Bandit to recommend popular articles from clusters the users had shown a preference for
5. Matrix Factorization - we used Singular Value Decomposition to decompose our user-article matrix into U, S, and Vt matrices. We explored various levels of latent factors and made predictions on test data by recomposing the matrices.

## Summary of Files and Folders
The main item of interest here is the Recommendations_with_IBM Jupyter notebook. You can view the .ipynb file or the .html file.
This notebook contains all of the data exploration, analysis, and article recommendations as required by the project.