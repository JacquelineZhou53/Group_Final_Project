# Group_Final_Project
Group member: Gretchen Zhang, Baihe Yuan, Jacqueline Zhou, Disheng Wen, Siyuan Chen

### 1) Import data

Importing the user_history data. Mainly came from the template.

### 2) Principal Component Analysis on User History data

Run PCA on user_history data, observe the pattern of the first two PCA features to decide number of clusters there are in the data.

### 3) K-means clustering

Divide the data into 3 clusters as the conclusion of the 2nd part.

### 4) PCA on clusters

Since the singular value analysis for all three clusters showed that the first three principal component revealed the most information, this part of code processes out the first three principal features for each clusters

### 5) Put the processed clusters back in place

Putting the three clusters into one matrix as the original order

### 6) Fill in NAs in the Ratings matrix

Replace NA entries with in the ratings matrix as 0

### 7) Find duplicate users and fitting a regression model on full features

Fit a regression model on the full features for the 3000 users with rating data available

### 8) Matrix Completion via Gradient Descent

Estimating the unfilled entries (0) by gradient descent iterations

### 9) Prediction

Predict the ratings for the rest 1500 users and output as a csv files
