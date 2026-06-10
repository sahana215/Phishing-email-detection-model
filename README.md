# Phishing Email Detection Model

## Overview
This project is a Machine Learning-based phishing email detection system developed using Python and Scikit-learn. The model analyzes email text and classifies it as either **Safe** or **Phishing**.

## Features
- Detects phishing emails using Machine Learning
- Uses TF-IDF Vectorization for text processing
- Multinomial Naive Bayes Classification
- Accuracy Evaluation
- Confusion Matrix Visualization
- Predicts new email messages

## Technologies Used
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- VS Code

## Project Workflow
1. Load the email dataset
2. Split data into training and testing sets
3. Convert email text into TF-IDF vectors
4. Train the Multinomial Naive Bayes model
5. Predict phishing or safe emails
6. Evaluate model performance
7. Display confusion matrix

## Dataset
The dataset contains:
- Email Text
- Label
  - 0 = Safe
  - 1 = Phishing

## Sample Output

Accuracy: 1.0

Prediction: phishing


## Confusion Matrix

The confusion matrix is used to evaluate the model's performance by comparing actual and predicted values.

## Future Improvements
- Use larger real-world datasets
- Add URL analysis
- Analyze sender domains
- Implement advanced models like Random Forest, SVM, and BERT
- Develop a web-based interface

## Learning Outcomes
- Machine Learning fundamentals
- Natural Language Processing (NLP)
- Text Vectorization using TF-IDF
- Model Evaluation Techniques
- Cybersecurity Awareness

## Author

**Sahana S**

Machine Learning Intern – Thiranex

## License

This project is created for educational and internship learning purposes.
