🍔 Agentic Chatbot with Guardrails — FoodHub

An agentic AI chatbot built with guardrails to safely and intelligently power conversations in the FoodHub domain — e.g., restaurant suggestions, menu queries, food ordering intents, and conversational recommendations.

This project is implemented as an interactive Jupyter Notebook (Agentic_Chatbot_FoodHub.ipynb) using agentic reasoning, safety guardrails, and configurable LLM tools to handle food-related user queries with reliable grounding, action planning, and safe decision logic.

🧠 Overview

Agentic systems combine multiple AI agents (reasoning, tool usage, planning) with safety enforcement to provide:

📋 Conversational food assistant
Guides users through food choices, menus, restaurant suggestions, and recommendations.

🛡️ Guardrails for safety & reliability
Built-in filters to monitor intents, prevent unsafe outputs, and ensure responses are grounded and relevant.

🤖 Hybrid reasoning + tools
Combines Large Language Models (LLMs) with guardrails, context retrieval, and domain-specific actions.

This approach goes beyond basic chatbots by splitting reasoning into stages (topic classification, action planning, output verification, etc.) and enforcing safety checks at each layer.


🚀 Features

✅ Food Domain Intelligent Chatting
· Handles queries like “What are some popular pizza places near me?”
· gives recommendations and menus in natural language.

✅ Multi-Stage Agent Reasoning
· Classifies intents, builds action plans, verifies responses before delivery.

✅ Safety Guardrails
· Topic validation, harmful intent detection, hallucination checks, and contextual verification.

🔧 Prerequisites

Ensure you have:

Python 3.8 or above

Jupyter Notebook / JupyterLab

Required API keys (OpenAI, Serper/DuckDuckGo, etc., depending on tools you use)


🛠️ Typical Workflow

Load and initialize LLM & tools
Configure language models and connect any external APIs.

Agentic reasoning setup
Define topic classification, action planning, and decision agents.

Guardrail integration
Add checks for topic validity, safety constraints, hallucination detection, and compliance.

User interaction loop
Collect user input, run through the agentic pipeline, and return safe, grounded outputs.

⚙️ Tech Stack

Python

Jupyter Notebook

LangChain / LangGraph (agent orchestration)

Large Language Models (OpenAI, Gemini, etc.)

Guardrail frameworks for safety & verification

Optional Vector Store for food knowledge retrieval

📦 Requirements

Below is a suggested set of dependencies (actual may vary based on notebook):

jupyter
openai
langchain
langgraph
python-dotenv
guardrails
tiktoken
serper
requests


🤝 Contributing

Contributions are welcome! You can:

Fork the repository

Create a feature branch (git checkout -b feature/xyz)

Commit your changes (git commit -m 'Add feature')

Push and open a Pull Request

⚖️ License

This project is licensed under the MIT License — see the LICENSE file for details.

⚠️ Disclaimer

This assistant is a research/demo system and is not a substitute for human food or dietary advice. Always verify critical recommendations independently.
