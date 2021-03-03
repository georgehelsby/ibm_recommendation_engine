# Building a Recommendation Engine for IBM Watson Studio

For this project I analyze the interactions that IBM Watson Studio users have with articles on the platform, and then make high-quality article recommendations to those users.

My project was divided into the following steps

### 1. Exploratory Data Analysis

- Figure out the distribution of IBM Watson Studio articles that a user interacts with in the dataset.
- Provide visual and descriptive statistics ot these interactions.

### 2. Rank-Based Recommendations

- Provide two functions to get a certain specified number of the most popular articles from the dataset.
- Article names and articles ids were produced.

### 3. User-User Based Collaborative Filtering

- Predict the articles that a user might like on the basis of ratings given to that article by other users who have similar taste with that of the target user.
- Created a user-item matrix to analyse article interactions.
- Created a find similar users function to locate the users with the most similarm 'taste' for articles to any given user.
- Then a final user recs function that recommeneds articles that similar users have viewed, and that the input user hasn't seen. 
- Also adjusting to select the users that have the most total article interactions over those with fewer article interactions.
- As well as choosing articles with the most total interactions before choosing those with fewer total interactions. 

### 4. Matrix Factorization 

- Used matrix factorization & SVD to make article recommendations to the users on the IBM Watson Studio platform
