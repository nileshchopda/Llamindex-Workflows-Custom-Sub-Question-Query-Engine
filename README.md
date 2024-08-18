# LlamaIndex Workflow: Agentic RAG Implementation

This repository contains a Jupyter notebook demonstrating the implementation of an Agentic Retrieval Augmented Generation (RAG) system using LlamaIndex workflows. The example showcases how to break down complex queries, process them efficiently, and combine the results using financial data from Infosys.

## Table of Contents

- [Overview](#overview)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [File Structure](#file-structure)
- [Medium Article](#medium-article)
- [Contributing](#contributing)
- [License](#license)

## Overview

This project demonstrates the power of LlamaIndex workflows in creating an Agentic RAG system. The implemented workflow:

1. Breaks down a complex query into sub-questions
2. Processes each sub-question using relevant tools
3. Combines the answers to provide a comprehensive response

The example uses Infosys financial data for the years 2022, 2023, and 2024 to answer questions about the company's net profit.

## Prerequisites

- Python 3.7+
- Jupyter Notebook
- OpenAI API key

## Installation

1. Clone this repository:
   ```
   git clone https://github.com/your-username/llamaindex-workflow-agentic-rag.git
   cd llamaindex-workflow-agentic-rag
   ```

2. Create a virtual environment (optional but recommended):
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

4. Set up your OpenAI API key:
   - Create a `.env` file in the root directory
   - Add your API key: `OPENAI_API_KEY=your-api-key-here`

## Usage

1. Open the Jupyter notebook:
   ```
   jupyter notebook Sub_Question_Query_Engine_as_a_workflow.ipynb
   ```

2. Run the cells in the notebook to see the Agentic RAG system in action.

3. Modify the query or data sources to experiment with different scenarios.

## File Structure

- `Sub_Question_Query_Engine_as_a_workflow.ipynb`: Main Jupyter notebook containing the implementation
- `data/infy_budgets/`: Directory containing Infosys financial reports
- `requirements.txt`: List of Python packages required for this project
- `README.md`: This file, providing an overview and instructions

## Medium Article

For a detailed explanation of the concepts and implementation, check out the accompanying Medium article:

[LlamaIndex Workflows: Orchestrating Complex Agentic RAG to a Structured Workflow](https://medium.com/@nilesh.chopda2112/llamaindex-workflows-orchestrating-complex-agentic-rag-to-a-structured-workflow-f9f0fefa83c7)

This article provides in-depth insights into:
- The concept of Agentic RAG
- LlamaIndex workflows and their components
- Step-by-step implementation guide
- Benefits and potential applications of this approach

## Contributing

Contributions to improve the implementation or extend its capabilities are welcome. Please feel free to submit issues or pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
