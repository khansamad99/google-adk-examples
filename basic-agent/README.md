# Basic Agent

This folder contains a simple greeting agent built using the [google-adk](https://pypi.org/project/google-adk/) framework.

## Structure

```
basic-agent/
  greeting_agent/
    __init__.py
    .env
    agent.py
```

- **greeting_agent/agent.py**: Defines the [`root_agent`](greeting_agent/agent.py) using the `Agent` class from `google.adk.agents`. This agent asks for the user's name and greets them.
- **greeting_agent/.env**: Stores environment variables, including the `GOOGLE_API_KEY` required for authentication.
- **greeting_agent/__init__.py**: Imports the agent module for package initialization.

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

1. Set your Google API key in `greeting_agent/.env`.
2. Import and use the agent in your application:

```python
from greeting_agent.agent import root_agent

# Use root_agent as needed
```

## Description

The greeting agent is a helpful assistant that interacts with users by asking for their name and greeting them personally.

---
**Note:** Ensure your environment variables are set correctly before running the agent.