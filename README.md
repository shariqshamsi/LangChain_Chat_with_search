<<<<<<< HEAD
# LangChain_Chat_with_search
 This repository demonstrates a Streamlit application integrated with LangChain tools and APIs for enabling interactive search and conversational capabilities. The app allows users to interact with a chatbot that leverages multiple search tools, including Arxiv, Wikipedia, and DuckDuckGo, to provide insightful answers based on the user's queries.

## Features

### 1. **Interactive Chatbot Interface**
   - Users can input their queries and receive real-time responses from the chatbot.
   - The chatbot maintains a conversational history for better context and usability.

### 2. **Search Tools Integration**
   - **Arxiv API Wrapper**: Fetches academic research papers, summarizing the top results with concise descriptions.
   - **Wikipedia API Wrapper**: Retrieves and summarizes relevant Wikipedia articles.
   - **DuckDuckGo Search**: Enables web search for general information.

### 3. **Agent Initialization with LangChain**
   - Uses LangChain's `initialize_agent` with `ZERO_SHOT_REACT_DESCRIPTION` for dynamic query handling.
   - Supports multiple tools seamlessly, including Arxiv, Wikipedia, and DuckDuckGo.

### 4. **Real-Time Streaming**
   - Employs `StreamlitCallbackHandler` to stream agent thoughts and responses interactively on the Streamlit interface.

### 5. **Secure API Key Management**
   - Accepts the Groq API key via a password-protected sidebar input field.

## Libraries Used

### Core Libraries
- **[Streamlit](https://streamlit.io/)**: Builds the interactive user interface for the chatbot.
- **[LangChain](https://github.com/hwchase17/langchain)**: Provides the agent framework and integrations with Arxiv, Wikipedia, and DuckDuckGo.
- **[langchain_community](https://github.com/langchain-ai/langchain-community)**: Extends LangChain with community-contributed tools and wrappers.

### Supporting Libraries
- **[python-dotenv](https://github.com/theskumar/python-dotenv)**: Manages environment variables for secure API key handling.
- **[os](https://docs.python.org/3/library/os.html)**: Handles file system interactions and environment variables.

## API Keys
- The application requires a valid Groq API key to function. Enter this key in the sidebar when prompted.
=======
---
title: Search Engine Llm
emoji: 🏃
colorFrom: indigo
colorTo: yellow
sdk: streamlit
sdk_version: 1.44.1
app_file: app.py
pinned: false
license: apache-2.0
---

Check out the configuration reference at https://huggingface.co/docs/hub/spaces-config-reference
>>>>>>> 1d6b24d (initial commit)
