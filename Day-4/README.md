# Day 4 – Tools, Structured Output and Google Sheets

## Project
**Sweet Crumbs Home Bakery – AI Agent**

## Objective
To build an AI-powered bakery assistant using LangChain tools, structured output, Pydantic validation and Google Sheets integration.

## Technologies Used
- Python
- LangChain
- LangChain Groq
- Groq LLM (`openai/gpt-oss-20b`)
- Pydantic
- Google Colab
- Google Sheets
- gspread

## Main Tasks Completed

1. Connected Groq LLM with LangChain.
2. Connected Google Sheets using gspread.
3. Created a Pydantic `Order` model.
4. Created tools using LangChain's `@tool` decorator.
5. Implemented `get_price()` to calculate cake prices.
6. Implemented `is_open()` to check bakery opening hours.
7. Implemented `log_order()` to save customer orders.
8. Built an AI agent using `create_agent()`.
9. Tested the agent with customer messages.
10. Inspected agent messages and tool execution traces.

## Bakery Menu

| Item | Price |
|---|---:|
| Plum Cake | ₹500 |
| Chocolate Cake | ₹650 |
| Cupcake | ₹80 |

## Business Rules
- Orders require 24 hours' notice.
- Eggless versions are available for all cakes.
- The agent checks prices using tools.
- The agent checks opening hours using tools.
- Confirmed orders are saved in Google Sheets.
- The agent responds in English or Telugu.

## Student Activities Completed

### Activity 1 – Your Tools
Created custom LangChain tools using the `@tool` decorator.

### Activity 2 – Your Record
Created a structured Order model using Pydantic and tested customer messages.

### Activity 3 – Your Sheet
Created a Google Sheet and a custom tool to save customer orders.

### Activity 4 – Break It
Changed a tool name to `tool1` with a basic description and tested agent tool selection.

### Activity 5 – Read the Trace
Inspected the agent execution trace and counted tool calls and AI messages.

## Test Result
Tested the agent with a request for 3 cupcakes.

- Correct price: ₹240
- Tool calls: 2
- AI messages: 3
- Agent successfully corrected an invalid tool argument and returned the correct price.

## Learning Outcomes
- Understanding how AI agents use tools.
- Creating structured data with Pydantic.
- Integrating Google Sheets with LangChain.
- Understanding tool calling and execution traces.
- Building practical AI agents for real-world business applications.

## Day 4 Status
**Completed – All five student activities covered.**
