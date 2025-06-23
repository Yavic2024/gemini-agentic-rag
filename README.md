# Gemini Agentic RAG

A tutorial project demonstrating Retrieval-Augmented Generation (RAG) using Google Gemini and agentic workflows. This project shows how to combine LLMs with external knowledge sources for more accurate and context-aware responses.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Examples](#examples)
- [Contributing](#contributing)
- [License](#license)

## Overview

This project implements an agentic RAG pipeline using Google Gemini. It retrieves relevant documents from a knowledge base and augments LLM responses with this information, enabling more reliable and grounded outputs.

## Features

- **Retrieval-Augmented Generation:** Combines LLMs with document retrieval for enhanced answers.
- **Agentic Workflow:** Uses an agent to orchestrate retrieval and generation steps.
- **Extensible:** Easily adapt to different data sources or LLM providers.

## Project Structure

```
gemini_agentic_rag/
├── agentic_rag_gemini.py
├── requirements.txt
├── README.md
└── (other scripts or data files)
```

- `agentic_rag_gemini.py`: Main script implementing the agentic RAG pipeline.
- `requirements.txt`: Python dependencies.
- `README.md`: Project documentation.

## Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/Yavic2024/gemini_agentic_rag.git
   cd gemini_agentic_rag
   ```

2. **Create a virtual environment (optional but recommended):**
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies:**
   ```sh
   pip install -r requirements.txt
   ```

## Usage

1. **Configure your Gemini API key and any other required environment variables.**
   - Example:  
     ```sh
     export GEMINI_API_KEY=your_api_key_here
     ```

2. **Run the main script:**
   ```sh
   python agentic_rag_gemini.py
   ```

3. **Follow the prompts or modify the script to use your own queries and data sources.**

## Configuration

- **API Keys:** Store your Gemini API key as an environment variable or in a `.env` file.
- **Knowledge Base:** Update the script to point to your own document store or data source if needed.

## Examples

```sh
python agentic_rag_gemini.py --query "What is Retrieval-Augmented Generation?"
```

**Sample Output:**
```
Retrieved documents: ...
LLM Response: Retrieval-Augmented Generation (RAG) is ...
```

## Contributing

Contributions are welcome! Please open issues or submit pull requests for improvements.

## License

This project is licensed under the MIT License.
