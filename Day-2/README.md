# 🚀 Day 2 – Build Your 10%

## Drive Ready – AI Agents | One Person Company (OPC) Initiative

### 🧵 Project: VV Tailors – AI Customer Support Chatbot

**Student:** A. Phaneendra Kumar  
**Department:** CSE – Artificial Intelligence and Machine Learning  
**Institution:** Aditya College of Engineering and Technology  
**Training Program:** Drive Ready – AI Agents  
**Day:** 02

---

## 📌 1. Project Overview

This project focuses on understanding the fundamentals of AI agents and implementing practical AI-based solutions using Python.

As part of Day 2 training, I completed five practical activities covering prompt engineering, few-shot learning, JSON extraction, chatbot memory management, and custom business chatbot development.

The final implementation is a customized AI customer support chatbot for **VV Tailors**, designed to answer customer enquiries about tailoring services and their prices.

## 🎯 2. Objectives

- Understand how system prompts control AI behaviour.
- Implement few-shot learning using sample conversations.
- Extract structured information using JSON.
- Understand chatbot memory and conversation history.
- Build a customized AI chatbot for a business.

## 🛠️ 3. Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming language |
| Google Colab | Development environment |
| Groq API | AI model access |
| OpenAI Python Library | API communication |
| JSON | Structured data processing |

## 💻 4. Practical Activities

### Task 1 – Understanding Prompt Parts

Created a system prompt with four important components:

- **ROLE:** Defines the chatbot's identity.
- **FACTS:** Provides business information.
- **RULES:** Controls chatbot behaviour.
- **FORMAT:** Defines the response style.

Tested the same customer question with and without rules to observe how system instructions affect AI responses.

### Task 2 – Few-Shot Classification

Developed a customer message classifier using three sample examples.

The classifier identifies customer messages into three categories:

1. Order
2. Question
3. Complaint

Tested the classifier using five new customer messages to evaluate its behaviour.

### Task 3 – JSON Extraction and Processing

Implemented AI-based extraction of customer order details into JSON format.

Extracted fields:

- Customer name
- Item
- Quantity
- Date
- Eggless preference

Used Python's `json.loads()` to convert the generated JSON string into a Python dictionary.

Implemented exception handling using `try/except` to handle invalid JSON and missing fields.

### Task 4 – Chatbot Memory Management

Implemented conversation history using Python lists.

- Set `MAX_TURNS = 2`.
- Stored user and assistant messages.
- Limited the conversation context sent to the AI model.
- Tested whether the chatbot could remember information from earlier messages.

Learned how conversation history and context trimming influence chatbot memory.

### Task 5 – Building a Custom Business Chatbot

Developed a customized AI customer support chatbot for **VV Tailors**.

Created a Python dictionary containing the available services and their prices.

#### Service Catalogue

| Service | Price |
|---|---:|
| Blouse Stitching | ₹500 |
| Shirt Stitching | ₹350 |
| Pant Alteration | ₹150 |
| Chudidar Stitching | ₹600 |
| Saree Fall and Pico | ₹250 |
| Dress Stitching | ₹700 |

Implemented Python functions with docstrings to retrieve service information.

Created a custom system prompt to guide the chatbot in answering customer enquiries politely and accurately.

## ✨ 5. Key Features

- Displays available tailoring services.
- Provides service price information.
- Answers customer enquiries.
- Uses a customized system prompt.
- Retrieves service details using Python functions.
- Generates AI-powered customer support responses.

## ▶️ 6. How to Execute

1. Open the project notebook in Google Colab.
2. Install the required Python library.
3. Configure the Groq API key through Google Colab Secrets.
4. Initialize the Groq API client.
5. Execute the code cells in the correct order.
6. Test the chatbot using different customer messages.

**Security Note:** API keys should be stored securely using environment variables or Google Colab Secrets. Never expose secret keys in public repositories.

## 📚 7. Learning Outcomes

After completing Day 2, I gained practical knowledge of:

- Prompt engineering and system instructions.
- Few-shot learning and text classification.
- JSON extraction and Python data processing.
- Conversation history and memory management.
- Integrating AI APIs with Python.
- Developing a business-specific AI chatbot.

## 🏁 8. Conclusion

Successfully completed all five practical activities assigned for Day 2 of the Drive Ready – AI Agents training program.

Through this implementation, I explored important AI agent concepts and developed a customized customer support chatbot for VV Tailors.

This practical experience improved my understanding of prompt engineering, API integration, structured data processing, and AI-powered business automation.

---

### ✅ Day 2 – Completed

**Drive Ready – AI Agents | One Person Company (OPC) Initiative**

*Learn. Build. Implement. Grow.*
