# Session State Example (ADK)

This project demonstrates how to use the Agent Development Kit (ADK) to build a stateful agent that remembers user information across interactions.

## Key Features
- **Stateful Sessions**: Maintains user data (name, preferences) between messages.
- **Personalized Responses**: Agent answers questions using stored session state.

## Project Structure
```
4-session-state/
├── basic_stateful_session.py      # Main script demonstrating session state
└── question_answering_agent/
    ├── __init__.py
    └── agent.py                  # Agent definition
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

Run the example to see session state in action:
```bash
python basic_stateful_session.py
```
This will:
- Create a session with your name and preferences
- Ask a question about your preferences
- Print the agent's personalized response and final session state

## References
- [Google ADK Sessions Documentation](https://google.github.io/adk-docs/sessions/session/)
- [State Management in ADK](https://google.github.io/adk-docs/sessions/state/)