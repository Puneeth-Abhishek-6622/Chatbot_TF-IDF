# Haystek FAQ Chatbot

## Overview
This is a simple FAQ chatbot built using Python, scikit-learn, and Gradio. The chatbot answers user queries about a hypothetical company’s services, pricing, support, greetings, and thanks.

## How It Works
- The chatbot uses TF-IDF vectorization to convert user queries and pre-defined patterns into numerical vectors.
- Cosine similarity is computed between the user query vector and all pattern vectors to detect the closest intent.
- A similarity threshold of 0.4 ensures relevant responses while reducing the risk of false positives.
- The chatbot responds with a predefined response that matches the detected intent.

## Technologies Used
- Python
- scikit-learn (TF-IDF, cosine similarity)
- Gradio (for creating an interactive web UI)

## How to Run
1. Install required packages:
   !pip install gradio scikit-learn


