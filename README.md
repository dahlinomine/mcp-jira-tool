# MCP Jira Tool

![mcp](https://img.shields.io/badge/mcp-blue?style=flat-square) ![jira](https://img.shields.io/badge/jira-blue?style=flat-square) ![project-management](https://img.shields.io/badge/project--management-blue?style=flat-square)

Connect agents to Jira to automate ticket creation, updating, and sprint management.

## Overview
The MCP Jira Tool is a Python-based Model Context Protocol (MCP) server designed to bridge the gap between AI agents and Jira Cloud/Server. It enables autonomous agents to interact directly with your project management workflows, reducing manual overhead and ensuring data consistency across development cycles.

## Features
*   **Ticket Automation:** Seamlessly create, update, and transition Jira issues using natural language prompts.
*   **Sprint Management:** Tools to view active sprints, add issues to backlogs, and track progress.
*   **Search & Query:** Advanced JQL support to fetch specific issue sets for context-aware agent responses.
*   **Comment & Collaboration:** Automatically post updates or internal notes to tickets based on agent task completion.

## Installation
Clone the repository and install the necessary dependencies using `pip`:

```bash
git clone https://github.com/yourusername/mcp-jira-tool.git
cd mcp-jira-tool
pip install -r requirements.txt
```

## Usage
Ensure your environment variables (`JIRA_URL`, `JIRA_EMAIL`, and `JIRA_API_TOKEN`) are configured before starting the server.

Run the tool with:
```bash
python main.py
```

**Example:**
Once connected to an MCP-compatible host (like Claude Desktop), you can issue commands such as:
*"Create a high-priority bug ticket in the PROJ board regarding the login timeout issue and assign it to the current sprint."*

## Contributing
Contributions are welcome! Please submit a Pull Request or open an issue to discuss proposed changes. Ensure that your code adheres to PEP 8 standards and includes relevant tests for new functionality.

## License
This project is licensed under the [MIT License](LICENSE).