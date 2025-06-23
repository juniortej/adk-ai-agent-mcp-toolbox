# adk-ai-agent-mcp-toolbox

AI agent using Google ADK and MCP toolbox to analyze your data with BigQuery.

## Features
- Run custom SQL queries on BigQuery
- Calculate and compare sales data
- Easy to extend with new tools

## Quick Start

1. Clone the repo:
   ```zsh
   git clone https://github.com/your-username/adk-ai-agent-mcp-toolbox.git
   cd adk-ai-agent-mcp-toolbox
   ```
2. Copy and edit environment variables:
   ```zsh
   cp dh-Agent/.env.example dh-Agent/.env
   # Edit dh-Agent/.env with your keys
   ```
3. Install dependencies:
   ```zsh
   pip install -r requirements.txt
   ```
4. Configure your BigQuery project in `MCP/tools.yaml`.
5. Start the agent:
   ```zsh
   cd dh-Agent
   python agent.py
   ```

## Security
- Never share your `.env` file or API keys.

## License
MIT
