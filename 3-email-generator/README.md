# Email Generator Agent (ADK)

This project demonstrates how to use the Agent Development Kit (ADK) to build an email generator agent with structured outputs using Pydantic models.

## Key Features
- **Structured Outputs**: Ensures all email responses follow a consistent format (subject and body) using a Pydantic schema.
- **Easy Integration**: Structured outputs make it simple to use the agent in other systems or workflows.

## Project Structure
```
3-email-generator/
├── email_agent/
│   └── agent.py         # Agent definition with output schema
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
   cd 3-email-generator
   adk web
   ```
2. Select `email_generator` in the web UI and enter your prompt.

## Example Prompts
- Write a professional email to my team about the upcoming project deadline that has been extended by two weeks.
- Draft an email to a client explaining that we need additional information before we can proceed with their order.
- Create an email to schedule a meeting with the marketing department to discuss the new product launch strategy.

## References
- [ADK Structured Data Documentation](https://google.github.io/adk-docs/agents/llm-agents/#structuring-data-input_schema-output_schema-output_key)
- [Pydantic Documentation](https://docs.pydantic.dev/latest/)