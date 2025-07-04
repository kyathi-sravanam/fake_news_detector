This project implements a simple fake news detection system using Python, scikit-learn, and TF-IDF vectorization.
It predicts whether a news article is FAKE or REAL based on its content.

📌 Project Workflow
Load and explore dataset (news.csv)

Preprocess and split the data into training & testing sets

Convert text data into numeric form using TF-IDF

Train a PassiveAggressiveClassifier

Evaluate accuracy and build a confusion matrix

⚙️ Technologies Used
Python

pandas, numpy (data manipulation)

scikit-learn (TfidfVectorizer, PassiveAggressiveClassifier, metrics, model_selection)

Google Colab (for coding & experimentation)

✅ Result
Achieved around ~92–93% accuracy on the test set.

