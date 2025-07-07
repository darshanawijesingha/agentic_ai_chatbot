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

# Update the "How It Works" section with separate lines for clarity

readme_content_updated = readme_content.replace(
    """## 🧠 How It Works

- Loads the LLaMA 3 model using Hugging Face's pipeline
- Initializes a LangChain agent with two tools:
  - **Search**: Fetches web results using Serper.dev
  - **Python**: Executes code using PythonREPLTool
- Uses `ConversationBufferMemory` to keep dialogue context
- Agent type: `CONVERSATIONAL_REACT_DESCRIPTION`
- Handles output parsing issues with `handle_parsing_errors=True`""",
    """## 🧠 How It Works

- Loads **LLaMA-3** model using HuggingFace pipeline  
- Sets up **LangChain agent** with two tools:  
  - **Search**: Uses Serper.dev to fetch web results  
  - **Python**: Executes code using PythonREPLTool  
- Uses **ConversationBufferMemory** for contextual replies  
- Agent type: `CONVERSATIONAL_REACT_DESCRIPTION`  
- Handles output parsing errors with `handle_parsing_errors=True`  
- Responds with structured, informative answers"""
)


# Save updated README
updated_path = "/mnt/data/README_updated.md"
with open(updated_path, "w", encoding="utf-8") as f:
    f.write(readme_content_updated)

updated_path




🔍 Sample Queries
"What is the latest version of Python?"
"Who won the last Cricket World Cup?"
"Plot a sine wave using matplotlib"
"Tell me a joke using Python"



🧪 Dependencies
# transformers
# torch
# langchain
# langchain-experimental
# huggingface_hub
# llama-cpp-python
# serper.dev
# accelerate
# requests
# google-search-results
