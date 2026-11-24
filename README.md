# Multi-Agent-System-using-LangGraph-MCP-Supervisor-Guardrails-HITL

# Multi-Agent Travel Planning System

## Project Overview

The Multi-Agent Travel Planning System is an AI-powered application developed using Python, LangGraph, MCP, and Large Language Models (LLMs).

The application uses multiple specialized AI agents to help users plan their travel, gather travel information, and generate personalized itineraries.

## Technologies Used

- Python
- LangGraph
- LangChain
- Groq LLM
- MCP (Model Context Protocol)
- FastAPI
- Streamlit / Frontend (if applicable)
- Human-in-the-Loop (HITL)
- Guardrails

## Multi-Agent Architecture

1. **Supervisor Agent** – Coordinates and manages multiple agents.
2. **Flight Agent** – Retrieves flight-related information.
3. **Weather Agent** – Provides weather information.
4. **Hotel Agent** – Handles hotel-related information.
5. **Itinerary Agent** – Generates personalized travel plans.
6. **Guardrails** – Helps validate and control agent inputs and outputs.
7. **Human-in-the-Loop** – Allows users to review and approve travel plans.

## Project Workflow

User Request → Supervisor Agent → Specialized Agents → Information Gathering → Itinerary Generation → Human Approval → Final Travel Plan.

## Key Features

- Multi-agent orchestration using LangGraph.
- MCP integration for external tools.
- LLM-powered travel recommendations.
- Human-in-the-Loop approval.
- Guardrails for controlled AI responses.
- Personalized travel itinerary generation.

## Installation

Clone the repository:

```bash
git clone https://github.com/MaheshkumarGovind/Multi-Agent-System-using-LangGraph-MCP-Supervisor-Guardrails-HITL.git
```

Navigate to the project:

```bash
cd Multi-Agent-System-using-LangGraph-MCP-Supervisor-Guardrails-HITL
```

Create virtual environment:

```bash
py -3.12 -m venv agent
```

Activate environment:

```powershell
.\agent\Scripts\Activate.ps1
```

Install dependencies:

```bash
python -m pip install -r requirements.txt
```

Configure environment variables in `.env`:

```env
GROQ_API_KEY=your_groq_api_key
```

Add other API credentials required by your MCP tools.

## Run Application

```bash
python app.py
```

Open in your browser:

http://127.0.0.1:8000

## Author

**Mahesh Kumar**

GitHub: https://github.com/MaheshkumarGovind

## Future Enhancements

- Real-time flight booking integration.
- Hotel booking integration.
- Advanced travel budget optimization.
- More external MCP tool integrations.