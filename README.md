# Chatbot-
🤖 Simple Python Chatbot
📌 Overview

This is a basic rule-based chatbot built in Python. It responds to user inputs using predefined keywords and returns random responses from a set of possible replies.

It’s designed for beginners to understand:

Conditional logic

Loops

Dictionaries

Basic NLP-style keyword matching

⚙️ Features

Responds to common greetings like "hello", "hi"

Handles simple queries like "how are you"

Randomized responses for variety

Default fallback message for unknown inputs

Continuous chat loop until user exits

🛠️ Requirements

Python 3.x

No external libraries required (only built-in random module is used)

🚀 How to Run

Save the file as:

Chatbot.py

Open terminal / command prompt

Run the script:

python Chatbot.py
💬 How It Works (Process Explanation)
1. Response Dictionary
responses = {
    "hello": ["Hi there! How can I help you?"],
    ...
}

Stores keywords as keys

Each key has a list of possible responses

2. Default Response
default_response = ["I'm sorry, I didn't understand that."]

Used when no keyword matches user input

3. Chatbot Function
def chatbot():

This is the main function controlling the chatbot.

4. Infinite Loop
while True:

Keeps the chatbot running continuously

Stops only when user types "exit"

5. User Input Handling
user_input = input("You: ").lower()

Takes input from user

Converts to lowercase for easier matching

6. Exit Condition
if user_input == "exit":

Ends the chatbot session

7. Keyword Matching Logic
for key in responses:
    if key in user_input:

Checks if any keyword exists inside user input

Example: "hello bot" → matches "hello"

8. Random Response Selection
random.choice(responses[key])

Picks a random reply from the list

Makes chatbot feel less repetitive

9. Fallback Handling
if not found:

If no keyword matches → default response

🧠 Example Interaction
Hello! I'm a simple chatbot. How can I assist you today?

You: hi
Chatbot: Hi there! How can I help you?

You: what is your name
Chatbot: I'm a simple chatbot created for demonstration purposes.

You: something random
Chatbot: I'm sorry, I didn't understand that. Can you please rephrase?

You: exit
Chatbot: Goodbye! Have a great day!
⚡ Limitations

Not AI-based (no machine learning)

Only keyword matching (no context understanding)

Limited responses

🔮 Future Improvements

Add NLP using libraries like nltk or spaCy

Use AI APIs (like OpenAI) for smarter replies

Add GUI (Tkinter / Web UI)

Store conversation history

Expand response database

📄 License

Free to use for learning and personal projects.
