# Day 2 – Sweet Crumbs Home Bakery Chatbot

## Project Description
This project is a simple AI-powered chatbot developed for Sweet Crumbs Home Bakery.

The chatbot helps customers get information about bakery products, prices, eggless cakes and order requirements.

## Technologies Used
- Python
- Google Colab
- Groq API
- LangChain
- LangChain-Groq

## Features
1. Answers customer questions about bakery products.
2. Provides cake prices.
3. Gives information about eggless cakes.
4. Explains the 24-hour order notice requirement.
5. Remembers customer details during the conversation.
6. Tests chatbot responses using CSV test cases.
7. Uses a LangChain agent to answer customer queries.

## Product Details
- Plum Cake – Rs 500
- Chocolate Cake – Rs 650
- Cupcake – Rs 80 each
- All cakes have eggless versions.
- Orders require 24 hours' notice.

## Implementation
The chatbot uses a Groq language model through LangChain.

A prompt template is used to provide bakery information and instructions. Conversation history is maintained using message memory.

CSV test cases are used to check chatbot responses. A LangChain agent is also created to handle customer questions.

## How to Run
1. Open the project in Google Colab.
2. Install the required Python libraries.
3. Add the GROQ_API_KEY in Google Colab Secrets.
4. Run the Python code cells in order.
5. Test the chatbot with customer questions.

## Conclusion
This project demonstrates how AI agents and LangChain can be used to build a customer support chatbot for a small bakery business.
