# CA02 - Spam eMail Detection using Naive Bayes Classification Algorithm
## Background 
The model consists of emails labelled as either from Spam or Not Spam. There are 702 emails equally divided into spam and non spam category. The model will be tested on 260 emails. The goal is to ask the model to predict the category of this emails and compare the accuracy with correct classification that we already know. 
## Instructions
### Step 1 - Cleaning and Preparing the data
We have two folders test-mails and train-mails. We will use train-mails to train the model. The very first step in text data mining task is to clean and prepare the data for a model. In cleaning, we remove the non required words, expressions and symbols from text. Here the words that don’t really contribute to the analysis (stop words) will not be included in the analysis. Hence in this exercise, we consider only most frequent 3000 words of dictionary from email. 
### Step 2 - Extracting features and corresponding label matrix.
After cleaning what we need from every email document, we should have some matrix representation of the word frequency. make_Dictionary reads the email files from a folder, constructs a dictionary for all words. Next, we delete words of length 1 and that are not purely alphabetical. At last we only extract out 3000 most common words. make_Dictionary reads the email files from a folder, constructs a dictionary for all words. Next, we delete words of length 1 and that are not purely alphabetical. At last we only extract out 3000 most common words. With the help of dictionary, we generated a label and word frequency matrix for each words in the 3000
### Step 3 - Training and predicting with sklearn Naive Bayes
sklearn Naive Bayes provides three alternatives for model training. In this exercise we shall use Gaussian (used in classification and assumes that features follow a normal distribution).
### Step 4 - Accuracy Score
Next, we compare the accuracy score for predicted labels. Accuracy score is just percentage of correct predictions. Again here, sklearn provides neat implementation for accuracy score calculation.
## Conclusion
The Naive Bayes considers the independence in features. For exampleit assumes the occurrence of one word/ feature is independent of other. But in real life it may not be so ( occurrence of morning is high after Good). 
