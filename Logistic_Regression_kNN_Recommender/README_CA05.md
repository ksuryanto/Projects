# CA05 - Logistic Regression & kNN Recommender
## A) Logistic Regression
### 1) The Application
Cardiovascular Disease (CVD) kills more people than cancer globally. A dataset of real heart patients
collected from a 15 year heart study cohort is made available for this assignment. The dataset has 16
patient features. Note that none of the features include any Blood Test information.
### 2) Deliverables
#### Part 1: build a binary classifier model to predict the CVD Risk (Yes/No, or 1/0) using a Logistic
Regression Model with the best performance possible (deliverable: Notebook)
#### Part 2: Display the Feature Importance of all the features sorted in the order of decreasing influence on
the CVD Risk (deliverable: Notebook)
#### Part 3: Evaluate the performance of your model (including ROC Curve), explain the performance and
draw a meaningful conclusion. (deliverable: Performance outputs in Notebook, explanation and
conclusion in Word/PDF document)
## B) knn Recommender
### 1) The Application
At scale, this would look like recommending products on Amazon, articles on Medium, movies on
Netflix, or videos on YouTube. Although, we can be certain they all use more efficient means of making
recommendations due to the enormous volume of data they process. However, we could replicate one of
these recommender systems on a smaller scale using what we have learned here in this article. Let us
build the core of a movies recommender system.
### 2) Data Source and Contents
The data contains thirty movies, including data for each movie across seven genres and their IMDB
ratings. The labels column values are all zeroes because we aren’t using this data set for classification or
regression. You can ignore this column. The implementation assumes that all columns contain numerical
data.
Additionally, there are relationships among the movies that will not be accounted for (e.g. actors,
directors, and themes) when using the KNN algorithm simply because the data that captures those
relationships are missing from the data set. Consequently, when we run the KNN algorithm on our data,
similarity will be based solely on the included genres and the IMDB ratings of the movies.
### 3) Building your own Recommender system
You are building your own movie recommendation website which uses your Recommendation Engine at
the back-end. You are going to build this back-end Recommendation Engine. Imagine a user is
navigating your recommendation website, and he/she encounters a movie named “The Post”. The user
is not sure if he/she wants to watch it, but its genres intrigue the user; he/she is curious about other
similar movies. The user scrolls down to the “More Like This” section to see what recommendations your
recommendation website will make, and the back-end algorithmic gears begin to turn.
Your website sends a request to its back-end for the 5 movies that are most similar to The Post. The backend
has a recommendation data set exactly like ours. It begins by creating the row representation (better
known as a feature vector) for The Post, then it runs a program similar to the one below to search for
the 5 movies that are most similar to The Post, and finally sends the results back to the user at your
website.
