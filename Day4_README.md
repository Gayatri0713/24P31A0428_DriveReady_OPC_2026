# Day 4 – AI Bakery Order Assistant

## Description
Developed an AI-powered bakery order assistant using LangChain and Groq. The chatbot helps customers check bakery opening hours, calculate cake prices, and place orders through natural language conversations.

## Technologies Used
- Python
- LangChain
- Groq LLM
- Google Colab
- Google Sheets
- Pydantic
- gspread

## Features
- Answers customer queries about bakery opening hours.
- Calculates cake prices based on quantity.
- Supports eggless cake orders.
- Collects customer details such as name, item, quantity, and pickup date.
- Validates order details using Pydantic.
- Automatically saves confirmed orders to Google Sheets.
- Maintains conversation history.

## Menu
- Plum Cake – Rs. 500
- Chocolate Cake – Rs. 650
- Cupcake – Rs. 80

## How to Run
1. Open the notebook in Google Colab.
2. Install the required Python libraries.
3. Add your Groq API key to Colab Secrets as `GROQ_API_KEY`.
4. Authenticate your Google account.
5. Run the notebook cells in order.
6. Chat with the AI bakery assistant and place orders.

## Project File
`Agentic_AI_day4.ipynb`

## Learning Outcomes
- Learned how to create AI agents using LangChain.
- Integrated Groq LLM with Python.
- Created custom tools for price calculation, opening hours, and order logging.
- Used Pydantic for structured data validation.
- Integrated Google Sheets to store customer orders.
