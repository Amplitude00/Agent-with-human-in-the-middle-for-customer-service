# Human-in-the-Middle Chatbot System

## Project Overview
This project implements a Human-in-the-Middle (HITM) chatbot system where automated chatbot responses can be reviewed, modified, or overridden by a human before being delivered to the end user. The system ensures higher response accuracy, ethical control, and reliability in sensitive or critical conversations.

## Key Features
- Automated chatbot response generation
- Human intervention before final response delivery
- Manual override and response editing capability
- Conversation logging for audit and improvement
- Scalable and modular chatbot architecture

## Technologies Used
- Python
- Streamlit
- Pytorch
- Ollama
- JSON-based conversation storage

## Workflow
1. User sends a query to the chatbot
2. Chatbot generates an initial response
3. Human reviewer validates or edits the response
4. Final response is sent to the user
5. Conversation is logged for future analysis

## Use Cases
- Customer support systems
- Healthcare and legal chatbots
- Educational assistance platforms
- Moderated AI communication systems

## How to Run
1. Install dependencies: `pip install -r requirements.txt`
2. Run the application: `python app.py`
3. Access chatbot via browser at `localhost`
