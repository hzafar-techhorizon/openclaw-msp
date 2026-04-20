# OpenClaw Project Structure

openclaw/
├── agents/
│   ├── discovery_agent.py      # Finds businesses without MSP
│   ├── scoring_agent.py        # Scores leads 1-100
│   ├── enrichment_agent.py     # Finds contact info
│   └── outreach_agent.py       # Drafts personalized emails
│
├── api/
│   ├── main.py                 # FastAPI app entry point
│   ├── routes/
│   │   ├── leads.py            # Lead management endpoints
│   │   └── agent.py            # Agent control endpoints
│   └── models.py               # Pydantic schemas
│
├── database/
│   ├── models.py               # SQLAlchemy models
│   ├── crud.py                 # Database operations
│   └── schema.sql              # PostgreSQL schema
│
├── scrapers/
│   ├── google_maps.py          # Google Maps scraper
│   ├── indeed.py               # Job board scraper
│   ├── reddit.py               # Reddit scraper
│   └── website.py              # Company website scraper
│
├── scheduler/
│   └── jobs.py                 # APScheduler configuration
│
├── config/
│   └── settings.py             # App configuration
│
├── requirements.txt
├── .env.example                # Template for env variables
├── README.md
└── docker-compose.yml          # Docker setup
