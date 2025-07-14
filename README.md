🤖 AI Chatbot Using NLP 

This is a rule-based **AI chatbot** built using **Natural Language Processing (NLP)** techniques via **NLTK**. It can handle greetings, internship-related queries, Python-related questions, and more using pattern recognition, lemmatization, and intent matching.

---

## 📌 Project Objective

**Task-3:**  
> Build a chatbot using Natural Language Processing libraries like NLTK or spaCy, capable of answering user queries.

---

## 🧠 Features

- ✔️ Handles greetings, help requests, and internship questions
- ✔️ Uses NLP techniques like:
  - Tokenization
  - Lemmatization
  - Intent matching
- ✔️ Simple command-line interaction
- ✔️ Easily expandable for more topics/intents

---

## 🛠 Requirements

Install the required libraries with:

```bash
pip install nltk
Then download the required NLTK datasets:

import nltk
nltk.download('punkt')
nltk.download('wordnet')
🚀 How to Run
Clone or download this repository.

Save your chatbot script as chatbot_nlp.py.

Run it in your terminal:

python chatbot_nlp.py
🧪 Sample Conversation
🤖 CODTECH Chatbot with NLP (type 'exit' to quit)
You: hi
Bot: Hello!

You: what is python?
Bot: Python is a powerful, high-level programming language used in AI, data science, and more.

You: when will i get my certificate?
Bot: You will receive your certificate on your internship end date.

You: bye
Bot: Goodbye!
🧾 Intern Info Responses
The chatbot understands internship-related questions such as:

When will I get my certificate?

What is CODTECH?

Who created you?

📦 File Structure

chatbot_project/
├── chatbot_nlp.py         # Main chatbot script
├── requirements.txt       # Python dependencies
└── README.md              # Project documentation
