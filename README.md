# Intent_classifier
My intent classifier is a machine learning model designed to understand the purpose or intent behind a user’s input in a conversational system. It’s built using the CLINC150 dataset, which contains various user queries labeled by intent such as book_flight, greet, fun_fact, and oos (out-of-scope).
Intent Classifier – Conversational AI with Scikit-learn
This project is part of my ongoing journey into Machine Learning and Natural Language Processing (NLP), where I’m focusing on building intelligent systems — especially chatbots and AI agents that understand and respond to human language.

✨ About the Project
The Intent Classifier is a basic NLP model designed to classify user queries into predefined intent categories. It is the first step in building a simple conversational agent.

I trained the model using TF-IDF Vectorization and tested several algorithms like:

Logistic Regression

Multinomial Naive Bayes

Support Vector Machine (SVM)

So far, Naive Bayes has performed the best for this dataset.

📂 Dataset
The dataset is a modified version of the classic Chatbot Intents Dataset. It includes user inputs (patterns) and their associated intents such as:

greetings

goodbyes

affirmations

fun facts

out-of-scope (oos) queries

The goal is to map a user’s message to the correct intent, which can later be used to trigger a response in a chatbot.

🛠️ Features
Preprocessing using TfidfVectorizer (with and without n-grams)

Comparison of model accuracy scores

Visualization of top features per class

Custom predict_intent() function to test the classifier on new inputs

⚙️ Model Performance

Model	Accuracy
Logistic Regression	~81.8%
Naive Bayes	~83.0%
SVM	~77.7%
Note: These results are based on default hyperparameters and minimal tuning.

📌 Why I Built This
After months of exploring machine learning from different angles — from image data to clustering — I realized I’ve always been passionate about making machines talk.

This project marks my pivot back into NLP, especially in building intent-aware systems that can:

understand human queries,

classify what the user wants,

and form the core of intelligent conversational agents.

🚀 What's Next?
In the coming months, I’ll be:

Sharing more projects focused on conversational AI

Exploring dialogue systems and contextual understanding

Implementing deep learning models (like RNNs, Transformers) for better language understanding
