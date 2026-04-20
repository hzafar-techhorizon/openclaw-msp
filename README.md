# OpenClaw — AI-Powered MSP Lead Generation Agent

Autonomous lead generation system for Managed Service 
Providers built with CrewAI, LangChain, and Python.

## What It Does

OpenClaw runs on a schedule and autonomously:
- Discovers small businesses without IT support
- Scores leads by company size, industry, and tech signals  
- Enriches leads with contact information
- Drafts personalized outreach emails

Zero human intervention after setup.

## Tech Stack

- **Agents:** CrewAI, LangChain
- **Backend:** FastAPI, Python 3.11
- **Database:** PostgreSQL
- **Scheduler:** APScheduler
- **Deployment:** Ubuntu 24.04 LTS
- **AI Models:** OpenAI GPT-4, Claude

## Architecture

Discovery Agent → Scoring Agent → Enrichment Agent → 
Outreach Agent → PostgreSQL → FastAPI Dashboard

## Status

🚧 Active development — v1.0 targeting Q2 2026

## Built By

Haroon Zafar — Tech Horizon MSP  
techhorizonmsp.ca
