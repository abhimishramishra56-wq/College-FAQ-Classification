# Task 2 – Model or API Integration

## Project Title
College FAQ Classification System Using AI/NLP

## Model Used
Multinomial Naive Bayes with TF-IDF text features.

## Objective
To classify college-related questions into five categories: Exams, Fees, Results, Timetable, and Admissions.

## Tools and Libraries
- Python
- Google Colab
- scikit-learn
- TfidfVectorizer
- MultinomialNB

## How It Works
1. Collect sample college-related questions.
2. Convert text into numerical TF-IDF features.
3. Train a Multinomial Naive Bayes classifier.
4. Enter a new question.
5. Predict its category.

## Sample Input
When is my exam?

## Sample Output
Predicted Category: Exams

## Limitations
- The sample dataset is small.
- Predictions may be inaccurate for unfamiliar wording or spelling mistakes.
- This is a basic prototype and needs more data and testing.

## Conclusion
This prototype demonstrates how a simple NLP model can classify college FAQ questions into predefined categories.
