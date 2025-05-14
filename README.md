# LangGraph ReAct Agent with Calculator and Greetings

This project demonstrates a simple conversational AI agent built using LangGraph and OpenAI. The agent is capable of performing basic arithmetic calculations using a `calculator` tool and greeting users by name using a `say_hello` tool. It utilizes the ReAct (Reasoning and Acting) framework for decision-making.

## Features

- **Basic Arithmetic Calculations:** Can add two numbers provided by the user.
- **Personalized Greetings:** Can greet users by name.
- **Interactive Conversation:** Allows for multi-turn conversations until the user decides to quit.
- **Streaming Output:** Provides a more interactive experience by streaming the agent's responses.

## Prerequisites

- **Python 3.7+**
- **pip** (Python package installer)
- **OpenAI API Key:** You'll need an API key from OpenAI to use their language models. You can obtain one from [https://platform.openai.com/api-keys](https://platform.openai.com/api-keys).
- **dotenv:** For managing environment variables.

## Setup

1. **Clone the repository (if applicable) or create a new project directory.**

2. **Install the required Python packages:**
   ```bash
   pip install langchain langchain-openai langchain-core langgraph python-dotenv
3. **Create a .env file in your project directory.
  -**OPENAI_API_KEY=YOUR_OPENAI_API_KEY_HERE**
4.**Save the provided Python code as a .py file (e.g., main.py).**

## Usage

1. **Run the Python script:**
     python main.py
2. **Interact with the agent:**
     The script will start an interactive session in your terminal. You can type your queries and press Enter.
     **To ask for a calculation: Provide two numbers. For example:**
     You: What is 5 plus 10?
     **To ask for a greeting: Provide a name. For example:**
     You: Say hello to Alice
     **To exit the conversation: Type quit.**

**Dependencies:**
langchain
langchain-openai
langchain-core
langgraph
python-dotenv

**Contributing**
Contributions are welcome! Please feel free to submit pull requests or open issues for any bugs or enhancements.
