# Tool Agent (ADK)

This project demonstrates how to use the Agent Development Kit (ADK) to build a tool agent that can interact with users and perform tool-based tasks.

## Key Features
- **Tool Integration**: Easily connect external tools and APIs to your agent.
- **Structured Outputs**: Consistent and reliable responses for downstream processing.

## Project Structure
```
2-tool-agent/
├── tool_agent/
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
   cd 2-tool-agent
   adk web
   ```
2. Select your tool agent in the web UI and enter your prompt.

## References
- [ADK Documentation](https://google.github.io/adk-docs/)
