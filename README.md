# MCP-server

mcp_server/
├─ api/ (FastAPI endpoints)
├─ orchestrator/
│  ├─ orchestrator.py
│  └─ policies.py
├─ agents/
│  ├─ retriever_agent.py
│  └─ generator_agent.py
├─ tools/
│  ├─ sandbox_runner.py
│  └─ integrations/ (ticketing, monitoring)
├─ data/
│  └─ docs/ (knowledge base)
├─ infra/
│  └─ docker-compose.yml
├─ tests/
└─ README.md
