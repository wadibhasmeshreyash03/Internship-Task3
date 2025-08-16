Name : Shreyash Rajendra Wadibhasme 
Company : Codtech IT solutions
Id : CT08DG1782
Domain : Python programming
Duration : june to august 2025 
Mentor : Neela Santosh Kumar

## **Project Overview: Smart Chatbot using NLP**
![chatbotpho](https://github.com/user-attachments/assets/66dfaeb6-af52-444b-98bb-a2169498b36b)

### **Objective**

The project implements a simple **rule-based chatbot** in Python using **Natural Language Processing (NLP)** techniques. It can recognize user intents (greetings, farewells, questions, small talk) and provide appropriate responses.

### **Key Components**

1. **Data & Intents (data.py)**
   * Stores predefined patterns and responses:
     * **Greetings** → ("hello", "hi", "good morning")
     * **Farewells** → ("bye", "see you later")
     * **Questions** → ("how are you", "what's your name")
     * **Small talk** → ("tell me a joke", "what's new")
   * Each intent category has a corresponding set of responses.

2. **NLP Preprocessing (chatbot.py)**
   * Uses **NLTK** (`word_tokenize`, `PorterStemmer`) to:
     * Tokenize user input
     * Normalize words (lowercasing, stemming)
   * Helps in **pattern matching** between user input and stored intents.

3. **Intent Recognition & Response**
   * Matches user input against stored patterns.
   * Selects a random response from the mapped category.
   * If no match is found → provides a fallback message:

     * *"I'm not sure how to respond to that. Could you rephrase that?"*

4. **User Interaction**
   * Runs in terminal/console.
   * Conversation loop continues until user types **“exit”**.
   * Example interaction:

     ```
     You: hi
     Chatbot: Hello! How can I help you?
     ```

### **Technologies Used**

* **Python**
* **NLTK (Natural Language Toolkit)** → Tokenization & stemming
* **Random module** → Select random responses


### **Applications**

* Educational demo of **NLP-based chatbots**
* Can be extended into:
  * Customer support bot
  * FAQ answering system
  * Entertainment/chat companion
