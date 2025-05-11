# Basic Greeting Agent (ADK)

This project demonstrates how to use the Agent Development Kit (ADK) to build a simple greeting agent.

## Key Features
- **Conversational Agent**: Interacts with users and provides personalized greetings.
- **Simple Example**: Great starting point for building more advanced agents with ADK.

## Project Structure
```
1-basic-agent/
├── greeting_agent/
│   ├── agent.py         # Main agent logic
│   └── __init__.py      # Package initialization
└── README.md            # This documentation
```

## Setup
1. Activate your virtual environment:
   ```bash
   source ../.venv/bin/activate
   ```
2. Add your Google API key to a `.env` file:
   ```
   GOOGLE_API_KEY=your_api_key_here
   ```
3. Install requirements:
   ```bash
   pip install -r ../requirement.txt
   ```

## Usage
1. Start the ADK web UI:
   ```bash
   cd 1-basic-agent
   adk web
   ```
2. Select your greeting agent in the web UI and enter your prompt.

## References
- [ADK Documentation](https://google.github.io/adk-docs/)