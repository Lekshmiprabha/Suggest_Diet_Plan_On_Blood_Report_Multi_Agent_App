# Suggest_Diet_Plan_On_BlooD_Report_Multi_Agent_App
# Diet Plan Suggester on Blood Report (Multi-Agent App)

An AI-powered multi-agent system that analyzes blood test results and recommends personalized diet plans. Built with LangGraph and deployed on Streamlit Cloud.

## Features

- **Blood report analysis**: Extracts key metrics (glucose, cholesterol, hemoglobin, etc.)
- **Multi-agent reasoning**: Separate agents for analysis, diet planning, and risk assessment
- **Personalized recommendations**: Diet, hydration, lifestyle adjustments based on results
- **User-friendly UI**: Streamlit interface for uploading reports and viewing suggestions
- **Deployed**: Live on Streamlit Cloud — no local setup required

## Agents

- **Analyzer Agent** — interprets blood report values and identifies abnormalities
- **Nutritionist Agent** — recommends diet adjustments based on findings
- **Risk Assessor** — flags health concerns and suggests medical follow-ups

## Tech stack

- **LangGraph** — multi-agent orchestration
- **Streamlit** — interactive web UI
- **Python** — data processing and logic
- **Deployed on Streamlit Cloud**

## How it works

1. User uploads a blood report (image or PDF)
2. Analyzer Agent extracts key values
3. Nutritionist Agent builds custom diet plan
4. Risk Assessor flags any concerns
5. Full report with recommendations displayed in UI

## Screenshot

[Add screenshot of the app interface here]

## Live demo

[Link to Streamlit Cloud deployment]

## How to run locally

```bash
pip install -r requirements.txt
streamlit run app.py
```

## Learning

This project taught me how to structure multi-agent systems for real-world healthcare use cases — balancing accuracy, user safety, and practical recommendations.
