# Day 3 – Your First AI Agent using LangChain

## Project Overview
This project is part of my AI Agents Workshop (Day 3). I built a basic AI assistant for **Sweet Crumbs Home Bakery** using Python, LangChain and Groq LLM.

The chatbot answers customer questions about bakery products, prices, eggless cakes and order requirements.

## Technologies Used
- Python
- Google Colab
- LangChain
- LangChain-Groq
- Groq API
- CSV

## Features
- Created a LangChain prompt template.
- Connected Groq LLM using ChatGroq.
- Implemented conversation memory.
- Built a basic agent using `create_agent`.
- Created automated customer-question tests.
- Tested different prompt instructions.
- Compared temperature settings.
- Created Python functions for price lookup and product availability.

## Bakery Menu

| Product | Price |
|---|---:|
| Plum Cake | ₹500 |
| Chocolate Cake | ₹650 |
| Cupcake | ₹80 |

## Testing Results

Created `test.csv` containing 5 customer questions.

**Final Test Result:**
- Total test cases: 5
- Passed: 5
- Failed: 0
- Pass percentage: 100%

## Python Functions

- `get_price()` – Calculates the total product price.
- `is_available()` – Checks whether a product is available.

## Project Files

- `day3_langchain.ipynb` – Main Google Colab notebook.
- `test.csv` – Customer test questions and expected answers.
- `tests.csv` – Additional test dataset, if retained.

## Learning Outcomes

- Understood the difference between chatbots and AI agents.
- Learned the basics of LangChain.
- Understood prompts, memory and chains.
- Learned how to test LLM responses.
- Understood the basics of agent creation.

## Conclusion

Successfully completed the Day 3 practical project and achieved a 100% pass rate in the final five-question test.

**Project:** Sweet Crumbs Home Bakery AI Assistant  
**Day:** 3 – AI Agents Workshop
