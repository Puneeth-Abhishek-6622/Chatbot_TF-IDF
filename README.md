# Haystek FAQ Chatbot

## Overview  
This is a simple FAQ chatbot built using Python, scikit-learn, and Gradio. The chatbot answers user queries about a hypothetical company’s services, pricing, support, greetings, and thanks.

## How It Works  
- The chatbot uses TF-IDF vectorization to convert user queries and predefined patterns into numerical vectors.  
- Cosine similarity is computed between the user query vector and all pattern vectors to detect the closest intent.  
- A similarity threshold of 0.4 ensures relevant responses while reducing the risk of false positives.  
- The chatbot responds with a predefined message matching the detected intent.

## Technologies Used  
- Python  
- scikit-learn (for TF-IDF vectorization and cosine similarity)  
- Gradio (for creating an interactive web interface)

## How to Run  
1. Install the required packages by running this command in your terminal or notebook:  
- pip install gradio scikit-learn

2. Run the chatbot script (e.g., `python chatbot.py`) or run it in a notebook cell.  
3. The Gradio app will open a local web interface or provide a shareable link.
