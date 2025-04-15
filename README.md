# AlphaBrief: Financial Briefing Agent

A final project for **IMT 589: Implementing and Managing GenAI Systems** at the University of Washington, created with Felix Zhao.

**AlphaBrief** is an AI-powered tool that delivers personalized daily market briefings using real-time news and stock data based on user preferences.

## Features

- Summarizes top financial headlines  
- Analyzes market sentiment and trends  
- Tracks selected stocks (e.g., gold, silver)  
- Provides personalized, risk-based suggestions  

## Files

- `user_profile.json` – Example user profile  
- `AlphaBrief.json` – Langflow export  

## Tools

- Langflow  
- Gemini (Google Generative AI)  
- Yahoo Finance API  
- Astra DB  
- Pandas  

## How It Works

1. Loads user preferences  
2. Fetches real-time and historical data  
3. Analyzes and summarizes with prompts  
4. Generates a tailored market briefing  

## Limitations

- Slow response time  
- Limited multi-turn conversation  
