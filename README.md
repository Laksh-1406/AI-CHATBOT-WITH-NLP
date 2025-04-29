COMPANY: CODTECH IT SOLUTIONS

NAME: LAKSHYA L JAIN

INTERN ID : :CT04WR234

DOMAIN : PYTHON PROGRAMMING

DURATION : 4 WEEKS

MENTOR : NEELA SANTOSH

#DESCRIPTION

This Python script implements an AI chatbot using Natural Language Processing (NLP) and a graphical user interface (GUI) with Tkinter. It integrates NLTK and spaCy for text processing and scikit-learn for machine learning-based response selection. The chatbot uses a predefined set of responses stored in a dictionary, categorized into greetings, farewells, general information, and default replies. Additionally, it maintains a small knowledge base with frequently asked questions and corresponding answers. The preprocessing function converts user input into lowercase and removes punctuation to standardize text. The core response mechanism leverages TF-IDF (Term Frequency-Inverse Document Frequency) vectorization to convert text into numerical form and computes cosine similarity to identify the most relevant response from the corpus. If the similarity score falls below a defined threshold (0.3), the chatbot returns a default fallback response. The GUI is built using Tkinter, featuring a chat display area (ScrolledText), an input field (Entry), and a send button (Button). The chat window visually differentiates user and bot messages using color-coded tags. When the user inputs a message and clicks "Send," the chatbot processes the message, finds the best response, displays it in the chat window, and clears the input field. The chatbot also auto-scrolls to the latest message to enhance readability. The program ensures an interactive and user-friendly experience by continuously listening for user input while maintaining a simple yet effective conversational flow. The combination of NLP techniques, vectorization, and similarity matching allows the chatbot to respond contextually to predefined queries, making it a lightweight yet efficient AI-driven assistant.

#OUTPUT
![Screenshot 2025-04-29 182445](https://github.com/user-attachments/assets/e08f9a5b-0c2d-41f7-b9f2-06589099cab5)
