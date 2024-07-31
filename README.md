# CodeAlpha_Handwritten_Character_Recognition
Creating a handwritten character recognition system that can recognize various handwritten characters or alphabets.
🚀 Exploring Machine Learning with MNIST Dataset 🧠

In a recent project, I worked with the MNIST dataset—a classic dataset used for image classification.

Overview of project: 👇

1-Loading and Preparing Data:

Fetching the Data: The MNIST dataset was retrieved and converted to NumPy arrays.

Target Labels: Labels were converted to integers for multi-class classification.




  
2-Visualizing a Sample Digit:

Function Definition: Created a plot_digit function to reshape the 784-element array into a 28x28 image for visualization.

Sample Visualization: Displayed the 36,001st digit to verify data integrity.





3-Splitting the Data:

Data Partitioning: Divided the dataset into training and test sets, reserving 10,000 samples for testing.





4-Training the Model:

Model Initialization: Trained a logistic regression model on the entire training set to classify digits (0-9).





5-Predicting a Sample Digit:

Model Prediction: Predicted the label for the 36,001st digit and printed the result.





6-Cross-Validation:

Performance Evaluation: Assessed the model's accuracy using cross-validation on the training set, and shared the average accuracy.





7-Predicting Multiple Sample Digits:

Random Sample Testing: Predicted labels for several random samples from the test set. Printed actual vs. predicted labels and visualized the digits.





8-Evaluating on the Test Set:

Test Set Accuracy: Evaluated the model's overall performance on the test set and reported the accuracy.
