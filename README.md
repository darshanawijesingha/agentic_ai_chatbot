# agentic_ai_chatbot
chat with ai without logging 


pip install --upgrade pip

# Core libraries
pip install torch transformers accelerate langchain huggingface_hub llama-cpp-python serpapi python-dotenv langchain-experimental

# Optional community tools
pip install langchain-community google-search-results


HF_TOKEN = "# Replace with your HuggingFace token"
SERPER_API_KEY = "# Replace with your Serper.dev API key"



## 🚀 Features
# ✅ LLaMA 3 - 8B Instruct
# ✅ Search the web using Serper.dev
# ✅ Execute Python code using Python REPL tool
# ✅ LangChain Conversational Agent
# ✅ Custom Prompting + Tool Usage
# ✅ Chat History Memory Buffer
# ✅ Handles Output Parsing Failures Gracefully

🧠 How It Works
Loads LLaMA-3 model using HuggingFace pipeline
Sets up LangChain agent with two tools:
Search (Serper.dev)
Python (REPL)
Uses ConversationBufferMemory for contextual replies
Handles parsing errors gracefully
Responds with structured, informative answers



🔍 Sample Queries
"What is the latest version of Python?"
"Who won the last Cricket World Cup?"
"Plot a sine wave using matplotlib"
"Tell me a joke using Python"



🧪 Dependencies
transformers
torch
langchain
langchain-experimental
huggingface_hub
llama-cpp-python
serper.dev
accelerate
requests
google-search-results
