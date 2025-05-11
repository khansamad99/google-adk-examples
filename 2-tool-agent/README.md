# Tool Agent

This folder contains a tool agent built using the [google-adk](https://pypi.org/project/google-adk/) framework.

## Structure

```
2-tool-agent/
  tool_agent/
    __init__.py
    agent.py
    __pycache__/
  README.md
```

- **tool_agent/agent.py**: Defines the main agent logic using the `Agent` class from `google.adk.agents`. This agent is designed to interact with users and perform tool-based tasks.
- **tool_agent/__init__.py**: Initializes the tool agent package.
- **tool_agent/__pycache__/**: Contains Python bytecode cache files (auto-generated).

## Requirements

Dependencies are listed in [requirement.txt](../requirement.txt):

- google-adk[database]==0.3.0
- yfinance==0.2.56
- psutil==5.9.5
- litellm==1.66.3
- google-generativeai==0.8.5
- python-dotenv==1.1.0

Install them with:

```sh
pip install -r ../requirement.txt
```

## Usage

1. Set your Google API key in a `.env` file (see example in the basic agent folder).
2. Import and use the agent in your application:

```python
from tool_agent.agent import root_agent

# Use root_agent as needed
```

## About Google ADK Tool Agents

Google ADK (Agent Development Kit) allows you to build modular, extensible agents that can interact with users, call APIs, and perform complex tasks. Tool agents are designed to:
- Integrate with external tools and APIs
- Process user input and provide intelligent responses
- Be easily extended with new capabilities

For more information, see the [google-adk documentation](https://pypi.org/project/google-adk/).

---
**Note:** Ensure your environment variables are set correctly before running the agent.
