# RAG_CHATBOT 💬

An intelligent Retrieval-Augmented Generation (RAG) chatbot built with Python, designed to provide accurate and context-aware responses by leveraging external knowledge sources.


## ✨ Features

*   🧠 **Context-Aware Responses:** Utilizes Retrieval-Augmented Generation (RAG) to fetch relevant information before generating answers, ensuring high accuracy.
*   💬 **Conversational AI:** Engages in natural, flowing conversations, remembering past interactions for a seamless user experience.
*   🚀 **Scalable Architecture:** Designed with a modular `api` and `app` structure for easy scaling and integration.
*   ⚙️ **Customizable Knowledge Base:** Easily integrate and update your own documents and data sources to tailor the chatbot's knowledge.
*   🐍 **Python-Powered:** Built entirely in Python, leveraging its robust ecosystem for AI and web development.


## 🛠️ Installation Guide

Follow these steps to set up the RAG_CHATBOT locally.

### Prerequisites

Ensure you have Python 3.8+ installed on your system.

### 1. Clone the Repository

First, clone the project repository from GitHub:

```bash
git clone https://github.com/SRKChaithanya/RAG_CHATBOT.git
cd RAG_CHATBOT
```

### 2. Set Up a Virtual Environment

It's highly recommended to use a virtual environment to manage dependencies:

```bash
python -m venv .venv
source .venv/bin/activate  # On Windows, use `.venv\Scripts\activate`
```

### 3. Install Dependencies

Install the required Python packages using pip:

```bash
pip install -r requirements.txt
```

*(Note: A `requirements.txt` file is assumed to be present in the project root containing all necessary dependencies.)*

### 4. Environment Configuration

Create a `.env` file in the project root directory based on a `.env.example` (if provided) or manually. This file will store your API keys and other sensitive configurations.

```
# Example .env content
OPENAI_API_KEY="your_openai_api_key_here"
# Add any other necessary environment variables here
```

Replace `"your_openai_api_key_here"` with your actual API key.




This project is currently released without a specific license. This means that, by default, all rights are reserved by the copyright holder (SRKChaithanya).

*   **Copyright:** © 2023 SRKChaithanya. All rights reserved.

Users are advised to contact the copyright holder for explicit permission regarding usage, distribution, or modification of the software.
