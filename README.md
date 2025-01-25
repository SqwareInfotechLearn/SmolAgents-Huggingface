# SmolAgents-Huggingface

SmolAgents is a Python-based framework that enables the creation of AI agents capable of handling various tasks, such as basic Q&A, web searches, image generation, and downloading the most popular models from the Hugging Face Hub. This repository demonstrates how to integrate Hugging Face models and multiple tools with the SmolAgents framework.

## Features

- **Basic Q&A Agent**: An agent that answers questions using a pre-trained Hugging Face model.
- **Web Search Agent**: An agent capable of performing web searches using the DuckDuckGo search tool.
- **Image Generation Agent**: An agent that generates images from text prompts using the "m-ric/text-to-image" tool.
- **Custom Tool**: A custom tool that retrieves the most downloaded model for a given task category from the Hugging Face Hub.
- **Managed Agent**: A managed agent that integrates web search functionality with other tools for more complex queries.

## Requirements

- Python 3.x
- Hugging Face API Token
- SmolAgents library
- Gradio (for the Image Generation tool)

### Install Dependencies

To get started with the project, clone this repository and install the required dependencies:

```bash
git clone https://github.com/SqwareInfotechLearn/SmolAgents-Huggingface.git
cd SmolAgents-Huggingface
```

> **Note**: You must have a Hugging Face API token to run the models. Set the token as an environment variable (`HUGGINGFACEHUB_API_TOKEN`), or replace `token` in the code with your token string.

## Usage

### 1. Basic Q&A Agent

This agent uses the Hugging Face model `Qwen/Qwen2.5-Coder-32B-Instruct` to respond to user queries.

### 2. Web Search Agent

This agent can perform web searches using the DuckDuckGo search tool. You can query it for general information like news, events, and more.

### 3. Image Generation Tool

This agent uses the Gradio UI to generate images based on a given text prompt. It utilizes the "m-ric/text-to-image" tool for generating high-quality images from user input.

### 4. Custom Tool for Model Downloads

This custom tool retrieves the most downloaded model from Hugging Face for a specific task (e.g., sentence similarity). You can query the tool for popular models in different categories like text classification, depth estimation, and more.

### 5. Managed Web Search Agent

This agent is a manager for multiple agents, handling web searches and other tasks. It integrates various functionalities into a single agent, providing enhanced capabilities for complex queries.

## Acknowledgments

- **SmolAgents**: A framework to create powerful agents using a variety of tools.
- **Hugging Face**: For providing the models and tools for AI development.
- **Gradio**: For creating an easy-to-use interface for image generation.
