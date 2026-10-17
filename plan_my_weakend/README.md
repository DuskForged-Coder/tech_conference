# Plan My Weakend

A weekend activity planning app built with Google's Agent Development Kit (ADK).

## Project Structure

- `agent.py` — Root agent definition (Gemini 3.5 Flash)
- `data/weakend_data.json` — Jaipur weekend activity/place/food data
- `tests/` — Test suite

## Getting Started

1. Copy `.env.example` to `.env` and add your Google API key.
2. Install dependencies: `pip install -r requirements.txt`
3. Run the agent: `python -m plan_my_weakend.agent`

## Data

The `data/weakend_data.json` file contains Jaipur spots across categories:
- Activities (e.g., Nahargarh Fort Sunset)
- Places (e.g., Hawa Mahal, Jal Mahal)
- Food (e.g., Tapri Central, Masala Chowk)
