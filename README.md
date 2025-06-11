# AI-CHATBOT-WITH-NLP

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*:URMIL RAMESHRAO BHOYAR 

*INTERN ID*:CT06DL1258

*DOMAIN*: PYTHON PROGRAMMING

*DURATION*:6 WEEKS

*MENTOR*: NEELA SANTOSH

# DESCRIPTION OF TASK 

 **Project Overview**
This project, AI Chatbot with NLP, demonstrates how to build a simple yet intelligent conversational chatbot using fundamental Natural Language Processing techniques. The bot can greet users, understand their 
questions, and respond contextually by referencing a provided dataset (data.txt). The entire chatbot logic is implemented in Python and executed using Google Colab, a powerful cloud-based code editor that's 
ideal for NLP experimentation and interactive learning.
The core functionality revolves around tokenizing the input data, preprocessing it (like lemmatization and punctuation removal), and then applying TF-IDF vectorization and cosine similarity to identify the best 
possible response from the dataset. This chatbot is rule-based but smart enough to simulate a basic conversation, making it an excellent starter project for those learning NLP, Python, or chatbot development.

**Tools & Technologies Used**
1. Programming Language
Python 3: The primary language used for text processing, chatbot logic, and execution.

2. Libraries & Frameworks
NLTK (Natural Language Toolkit): For text tokenization, lemmatization, and linguistic preprocessing.
Scikit-learn: For TfidfVectorizer and cosine_similarity used in semantic matching.
Random and String: For basic utilities like punctuation handling and random greeting generation.

3. Code Editor
Google Colab: A browser-based notebook environment that provides zero-setup Python execution, GPU access, and integration with Google Drive—perfect for running this NLP chatbot without installing anything
locally.

**Workflow**
Step 1: Data Ingestion
The chatbot starts by reading a plain text file (data.txt) that serves as its knowledge base.
The text is converted to lowercase to ensure uniformity.

Step 2: Tokenization
The data is tokenized into sentences and words using nltk.sent_tokenize() and nltk.word_tokenize().
This helps in managing the context and extracting meaningful responses.

Step 3: Text Normalization
Punctuation is removed using Python's string.punctuation.
Lemmatization is applied using WordNetLemmatizer to convert words to their base forms, which improves response matching accuracy.

Step 4: Greeting Recognition
The bot identifies simple greetings like "hi", "hello", or "whassup" using a predefined input-response dictionary.
if a greeting is detected, the bot responds with a random friendly reply.

Step 5: Intelligent Response Generation
The chatbot uses TF-IDF (Term Frequency–Inverse Document Frequency) to vectorize all sentence tokens.
Cosine Similarity is used to compare the user's query with the vectorized sentences.
The most relevant sentence is chosen and displayed as the bot's response.
If no meaningful match is found, a default “I don’t understand” response is returned.

Step 6: Interactive Chat Loop
The chatbot runs continuously until the user types “bye”.
It handles polite farewells like "thank you" and exits gracefully.

**Learning Objectives**
Through this project, users will learn:
How to tokenize and preprocess natural language data using NLTK.
The role of lemmatization and punctuation removal in NLP.
How TF-IDF vectorization helps in converting text to numerical format.
How to measure semantic similarity between user input and known data using cosine similarity.
How to build a simple interactive chatbot that runs in a Python loop.

**Use Cases and Applications**
Educational Tools: For teaching basic NLP principles.

FAQ Chatbots: For static informational systems on websites or helpdesks.

Customer Support: With additional training, can be adapted for real customer service queries.

Personal Assistants: A great foundation for building more advanced voice/text-based bots.

College Projects: Ideal for academic demonstration of NLP workflows.

**Future Enhancements**
Add support for contextual conversation using RNNs or transformers.

Build a web interface using Flask or Streamlit.

Support multiple languages using translation APIs.

Store chat history and responses using a database like SQLite or Firebase.

Add voice input/output with speech_recognition and pyttsx3.

**Code Execution**
Since this chatbot project is built using Google Colab, it requires no installations or system configuration. To run the code:

Open Google Colab.

Upload your data.txt file to the Colab environment.

Copy and paste the full chatbot code into a notebook cell.

Run all cells sequentially.

Interact with the chatbot in the input prompt that appears.
