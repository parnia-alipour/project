# What Do We Do in Machine Learning?🧠

In machine learning, we work with a set of data whose purpose is to train the model and help it learn patterns.
This data is initially divided into two parts:
Our test data and our train data test and train.
Our train data includes our main data, which has an output, and that output is the test output of our train data.
For example, imagine we want to see if, based on a person’s history, we can give them a loan or not.💸
All of our data becomes train.
For this, we have a set of columns and features  for example, the last time the person took a loan, their phone number, the loan amount, whether they were trustworthy or not, etc.

All of these are my x columns.
I have another column, the y column  this is my final answer: s this person eligible for a loan based on the provided information?
And that column includes either numbers, or 0 and 1, or yes and no.
Another part of my data becomes x_test what does this do?
This data is used to test the training data. Based on what the model has learned, y_test is supposed to be returned to us.
: This is the answer that the model guesses based on what it has learned, without having seen this data before.
Let’s give an example like this:
A teacher gives a set of lessons to students and during teaching(x_train), asks questions and answers them(Y_train)

: x_test is like the Midterm Exam.

The student, based on what they’ve learned and the teacher’s explanations, must answer the questions without cheating. The answer the student writes on the paper is y_test.
  y_pred is like the final exam.
In the first term, the teacher might have given hints during class and helped the student with the questions. But here, the student has no idea what the questions might be and must answer based only on what they’ve learned  to show whether they truly understood the lesson or not.
Or the entrance exam (konkur) is the same:
  x_train The student studies  
Mentally reviews the concepts and asks themselves questions y_train 
Takes practice tests without cheating  x_test 
The answer the student writes y_test 
And on the actual exam day, the answers they write become  y_pred

Meaning the y that they predict on their own based on the x’s they’ve learned.

### x_train,y_train → Training data and training outputs
### x_test,y_test→ Test data and actual outputs for testing
### y_pred→ Predicted output from the model