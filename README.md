# AutogenStudio 0.4 Custom Agents

This repository contains custom agents for AutogenStudio 0.4, including a **Gallery Agent** and a **Team Builder Agent** with a **Calculator Assistant**.

## Agents

### 1. Gallery Agent
- **Name**: `gallery_agent`
- **Description**: A custom agent designed for efficient interaction and management of gallery-based operations.

### 2. Team Builder Agent (Calculator Team)
- **Name**: `calculator_team`
- **Description**: A team-based agent that performs arithmetic calculations using a calculator tool.
- **Components**:
  - **Agent Name**: `assistant_agent`
  - **Model**: `OllamaChatCompletionClient` (using `codellama:13b`)
  - **Tools**: 
    - **Calculator**: A simple arithmetic tool supporting `+`, `-`, `*`, `/`.
  - **Termination Condition**: Max 3 messages before termination.

## Installation & Usage
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/autogenstudio-agents.git
   cd autogenstudio-agents
