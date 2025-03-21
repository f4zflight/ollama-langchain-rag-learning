# Welcome to the Ollama LangChain RAG Learning Project

Hi there! I'm Richard Chung, and thank you for visiting this project. This repository is dedicated to learning and experimenting with **Ollama**, **LangChain**, and **RAG (Retrieval-Augmented Generation)** to build powerful language model applications.

Feel free to explore, experiment, and contribute. If you have any questions or suggestions, don't hesitate to reach out!

Happy coding! 🚀

# Ollama LangChain RAG Learning Project

This repository contains the code and resources for learning and experimenting with **Ollama**, **LangChain**, and **RAG (Retrieval-Augmented Generation)**. The project aims to provide hands-on experience in building and deploying applications with these powerful technologies.

## Project Overview

In this project, we integrate Ollama (a large language model) with LangChain, a framework for building LLM-powered applications, and apply Retrieval-Augmented Generation (RAG) to enhance the capabilities of language models. This approach enables more efficient querying and better performance in handling complex tasks that require external knowledge.

## Development Environment

The project was developed on **Windows 11** using the following tools:

- **Visual Studio Code** (VSCode) for code editing and debugging
- **Python** (specific version: Python 3.x)
- **Poetry** for dependency management and virtual environments (Poetry (version 2.1.1))
- **Ollama** for language model integration (ollama version is 0.6.2)
- **LangChain** for building LLM-powered applications
- **RAG** for improved context retrieval in LLM tasks

### Setup and Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/f4zflight/ollama-langchain-rag-learning.git
   cd ollama-langchain-rag-learning

2. Install dependencies using Poetry:

First, ensure you have Poetry installed. You can install it by following the instructions at Poetry's official website.

Then, install the project dependencies:

bash
poetry install

3. Activate the virtual environment:
bash
poetry shell

4. Run the application:
bash
python main.py

Features
Ollama Integration: Use Ollama's advanced language model to generate text-based outputs and answers.
LangChain Framework: Build complex, chainable language model pipelines with LangChain.
RAG Implementation: Enhance LLMs with external knowledge retrieval to improve response quality and accuracy.

Contributing
We welcome contributions to this project! If you'd like to contribute, please follow these steps:

Fork the repository
Create a new branch (git checkout -b feature-branch)
Commit your changes (git commit -am 'Add feature')
Push to the branch (git push origin feature-branch)
Create a new Pull Request
Please check out the contributing.md file for more detailed instructions on how to contribute.


License
This project is licensed under the MIT License - see the LICENSE file for details.

Project Structure ( this is not yet confirmed)
ollama-langchain-rag-learning/
├── docs/                # Documentation: Project guides, tutorial, and setup instructions
│   ├── tutorial.md      # Tutorial: Step-by-step guide for using the project
│   ├── installation.md  # Installation: Instructions for setting up the project
│   └── contributing.md  # Contributing: How to contribute to the project
├── src/                 # Source code for the application
│   ├── main.py          # Main entry point for the project
│   ├── langchain_integration.py # LangChain integration module
│   └── rag_model.py     # RAG-related functionalities
├── tests/               # Test files for unit tests
│   ├── test_langchain.py # Tests for LangChain integration
│   ├── test_rag.py       # Tests for RAG functionality
│   └── test_utils.py    # Test utilities
├── .gitignore           # Git ignore file to exclude unnecessary files
├── README.md            # Project overview and setup instructions
├── LICENSE              # License for the project
└── requirements.txt     # List of dependencies for the project


