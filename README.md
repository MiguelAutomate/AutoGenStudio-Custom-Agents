# AutoGen Studio 0.4 Custom Agents

![AutoGen Logo](https://microsoft.github.io/autogen/dev//_static/logo.svg)
![AutoGen Landing](https://media.githubusercontent.com/media/microsoft/autogen/main/autogen-landing.jpg)

A collection of custom agents, tools, and configurations for AutoGen Studio 0.4, extending the default capabilities with specialized components for enhanced human-in-loop conversations and task automation.

## Features

- **Diverse Agent Types**: Includes specialized agents like virtual assistants, chatbots, configuration experts, and more
- **Extended Model Support**: Configurations for various models including GPT-4o mini, Llama3.1, DeepSeek Coder, and others
- **Comprehensive Toolset**: 15+ tools ranging from calculators to API integration and workflow automation
- **Flexible Termination Conditions**: Multiple termination strategies for conversation control
- **Human-in-Loop Teams**: Pre-configured teams for collaborative human-AI interaction

## Components Overview

### Agents
- `human_in_loop_team`: Pre-configured team for human-AI collaboration
- `llama3_agent`: Assistant powered by Ollama's Llama3.1 model
- `virtual_assistant`: For booking appointments and making reservations
- `chatbot`: Natural language conversational agent
- `config_expert`: Validates and modifies configurations
- `model_config`: Manages model configurations
- `tool_config`: Manages tool configurations

### Models
- GPT-4o mini
- Llama3.1
- DeepSeek Coder v2
- Qwen2.5 Coder
- Dolphin-Llama3
- CodeLlama 13b

### Tools
- **Basic Tools**: Calculator, website fetcher
- **Advanced Tools**:  
   - Task parser
   - Domain knowledge base
   - Model trainer
   - Workflow automation
   - API integration
   - Error handling
   - Data visualization

## Installation

1. Clone this repository:
    ```bash
    git clone [https://github.com/MiguelAutomate/AutoGenStudio-Custom-Agents.git](https://github.com/MiguelAutomate/AutoGenStudio-Custom-Agents.git)
    ```
