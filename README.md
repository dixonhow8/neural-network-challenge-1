# neural-network-challenge-1
This is the repository for the Module 18 challenge involving Neural networks.
# Student Loan Repayment Prediction

## Background
This project focuses on predicting the likelihood that a borrower will repay their student loans. By analyzing historical data, we aim to create a machine learning model that will allow our company to provide more accurate interest rates for prospective borrowers. The dataset contains information about previous student loan recipients, including their credit rankings.

## Files
- [Student Loans with Deep Learning Notebook](student_loans_with_deep_learning.ipynb)

## Beginning Steps
To get started with this challenge, follow these steps:

1. **Create a New Repository**: Name it `neural-network-challenge-1`. Do not add this challenge assignment to an existing repository.
2. **Clone the Repository**: Clone the new repository to your local machine.
3. **Add Starter File**: Download and add the starter file `student_loans_with_deep_learning.ipynb` to your local Git repository.
4. **Push Changes to GitHub**: Commit your changes and push them to GitHub.
5. **Upload to Google Colab**: Open `student_loans_with_deep_learning.ipynb` in Google Colab to work on your solution.
6. **Track Changes**: Periodically download your updated notebook and push it back to your repository to track version history.

## Instructions
The notebook is divided into four parts:

### Part 1: Prepare the Data
- Load the dataset from the provided URL into a Pandas DataFrame.
- Review the DataFrame to identify features and the target variable (`credit_ranking`).
- Create the feature set (X) and the target variable (y).
- Split the datasets into training and testing sets.
- Scale the features using `StandardScaler()` from scikit-learn.

### Part 2: Compile and Evaluate the Model
- Use TensorFlow to design a deep neural network model:
  - Determine the number of input features, layers, and neurons.
  - Start with a two-layer model using the ReLU activation function.
- Compile the model with the following configurations:
  - Loss function: `binary_crossentropy`
  - Optimizer: `adam`
  - Metrics: `accuracy`
- Fit the model on the training data (start with 50-100 epochs).
- Evaluate the model's performance using the test data to calculate loss and accuracy.
- Save the model to a Keras file named `student_loans.keras`.

### Part 3: Predict Loan Repayment Success
- Reload the saved model.
- Make predictions on the testing data, rounding the results to binary values.
- Generate a classification report based on the predictions and test data.

### Part 4: Recommendation System Discussion
Provided answers to the following questions:
1. **Data Collection**: Describe the necessary data to build a recommendation system for student loan options and its relevance.
2. **Filtering Method**: Explain whether your model would use collaborative, content-based, or context-based filtering, and justify your choice.
3. **Challenges**: Identify two real-world challenges in building a student loan recommendation system and explain their significance.

## Conclusion
This project aims to leverage machine learning techniques to improve student loan refinancing processes. By accurately predicting loan repayment, the company can better serve borrowers with tailored interest rates. The insights gained from the model and subsequent discussions about a recommendation system will contribute to more effective loan management strategies.
