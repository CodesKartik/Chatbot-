# 🤖 Simple Python Chatbot

## 📌 Overview
This is a basic rule-based chatbot built in Python. It responds to user inputs using predefined keywords and returns random responses from a set of possible replies.

It’s designed for beginners to understand:
- Conditional logic
- Loops
- Dictionaries
- Basic NLP-style keyword matching

---

## ⚙️ Features
- Responds to common greetings like "hello", "hi"
- Handles simple queries like "how are you"
- Randomized responses for variety
- Default fallback message for unknown inputs
- Continuous chat loop until user exits

---

## 🛠️ Requirements
- Python 3.x

No external libraries required (only built-in `random` module is used)

---

## 🚀 How to Run

1. Save the file as:
   Chatbot.py

2. Open terminal / command prompt

3. Run the script:
   python Chatbot.py

---

## 💬 How It Works (Process Explanation)

### 1. Response Dictionary
Stores keywords as keys and lists of responses as values.

### 2. Default Response
Used when no keyword matches user input.

### 3. Chat Loop
Runs continuously until the user types "exit".

### 4. Input Handling
User input is converted to lowercase for matching.

### 5. Keyword Matching
Checks if any keyword exists inside user input.

### 6. Random Response
Selects a random reply using the random module.

### 7. Fallback
If no keyword is found, returns a default message.

---

## 🧠 Example Interaction

Hello! I'm a simple chatbot. How can I assist you today?

You: hi  
Chatbot: Hi there! How can I help you?

You: what is your name  
Chatbot: I'm a simple chatbot created for demonstration purposes.

You: something random  
Chatbot: I'm sorry, I didn't understand that. Can you please rephrase?

You: exit  
Chatbot: Goodbye! Have a great day!

---

## ⚡ Limitations
- Not AI-based (no machine learning)
- Only keyword matching (no context understanding)
- Limited responses

---

## 🔮 Future Improvements
- Add NLP using libraries like nltk or spaCy
- Use AI APIs for smarter replies
- Add GUI (Tkinter / Web UI)
- Store conversation history
- Expand response database

---

## 📄 License
Free to use for learning and personal projects.
