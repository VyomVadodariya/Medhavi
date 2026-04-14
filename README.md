# Medhavi

**Cognitive Infrastructure & Accelerated Learning System**

Medhavi is a proprietary multi-agent system designed to ingest qualitative reading data, construct a psychological knowledge graph of the user, and dynamically rewrite complex external data into hyper-personalized, high-velocity learning curriculums.

## Architecture
- **Frontend:** React (Minimalist UI, Latency-Optimized Handoffs)
- **Backend:** Django Framework (Session Routing, Agent Orchestration)
- **Memory:** Vector Database & GraphRAG Pipeline

## Development Environment Setup

### 1. Backend Initialization
\`\`\`bash
cd backend
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
pip install -r requirements.txt
python manage.py runserver
\`\`\`

### 2. Frontend Initialization
\`\`\`bash
cd frontend
npm install
npm start
\`\`\`

---
*Note: All API keys and environment variables must be configured locally in a `.env` file. Never commit `.env` to version control.*
