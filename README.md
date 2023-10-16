# Text Classification Using Naive Bayes Algorithm

This project focuses on building a text classification system to detect spam emails using the Naive Bayes algorithm. It includes steps to load a dataset, split it into training and testing sets, and use Count Vectorization to convert text data into numerical features for machine learning. The project also evaluates the model's performance using accuracy, precision, recall, and F1 score metrics.

## Prerequisites

Before running the code, make sure you have the following Python packages installed:

- [pandas](https://pypi.org/project/pandas/)
- [scikit-learn](https://scikit-learn.org/stable/)

You can install them using pip:

pip install pandas
pip install scikit-learn

## Usage

1. **Load the dataset**: The code loads the dataset from a CSV file named 'emails.csv'. Ensure that you have this file in the same directory as your code or provide the correct file path.

2. **Data Split**: The dataset is split into a training set and a test set using a default ratio of 3:1. You can adjust the split ratio as needed.

3. **Count Vectorization**: The text data is transformed into numerical features using the CountVectorizer method. The vocabulary is learned from the training data and applied to both the training and testing data for consistency.

4. **Training the Model**: A Multinomial Naive Bayes model is trained on the training data.

5. **Model Evaluation**: The model's performance is evaluated using the following metrics:
   - Accuracy
   - Precision
   - Recall
   - F1 score

6. **Testing the Model**: The code provides examples of email texts to classify as spam or not spam using the trained Naive Bayes model.

## Example Emails

Here are some example emails to test the classification model:

1. "Subject: Meeting Agenda for Tomorrow" - Not Spam
2. "Subject: Get a Free iPhone X" - Spam
3. "Subject: Invitation to a Birthday Party" - Not Spam
4. "Subject: Important Updates on Your Account" - Spam
5. "Subject: Dinner Plans for This Friday" - Not Spam
6. "Subject: Claim Your Prize Now!" - Spam

## Run the Code

You can run the code provided in your Python environment. Make sure to adapt the file paths and data as needed. After running the code, it will classify the example emails and print the results.

Feel free to modify the code for your specific use case or dataset.
