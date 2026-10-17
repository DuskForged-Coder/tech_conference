# Plan My Weakend

A weekend activity planning app built with Google's Agent Development Kit (ADK).

## Project Structure

- `agent.py` — Root agent definition (Gemini 3.5 Flash)
- `data/weakend_data.json` — Jaipur weekend activity/place/food data
- `__init__.py` — Package init
- `.gitignore` — Ignore rules for `.env`, `.adk/`, `__pycache__/`, `venv/`, etc.

## Getting Started

1. The `.env` file contains your Google API key and is git-ignored for security.
2. Install dependencies: `pip install google-adk`
3. Run the agent: `python -m plan_my_weakend.agent`

## Data

The `data/weakend_data.json` file contains Jaipur spots across categories:
- Activities (e.g., Nahargarh Fort Sunset)
- Places (e.g., Hawa Mahal, Jal Mahal)
- Food (e.g., Tapri Central, Masala Chowk)
