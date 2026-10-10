# ShelfMind

ShelfMind is an Agentic Perishable Intelligence Platform designed for zero-waste grocery operations. It is built for the GDGoC HITAM Hackathon PS2 challenge, with a focus on reducing food waste by combining inventory awareness, product freshness analysis, forecasting, and actionable recommendations.

## Overview

ShelfMind helps retailers and grocery operators make better decisions about stock, freshness, and waste reduction. The platform is designed to support a workflow where products are monitored, risks are identified early, and operational recommendations are generated through an intelligent decision layer.

The project combines:

- inventory and product intelligence
- perishable-risk identification
- agent-driven recommendations
- data-backed decision support
- sustainable retail operations

## Problem It Addresses

Food waste is a significant challenge in grocery retail. Common issues include:

- overstocking perishable goods
- poor demand forecasting
- product spoilage before sale
- lack of actionable data for inventory decisions
- inefficient stock rotation

ShelfMind aims to mitigate these challenges by turning operational data into useful, timely recommendations.

## Key Features

- perishable inventory intelligence
- AI/agent-based recommendation workflows
- real-time or near-real-time stock assessment
- synthetic or seed data generation for testing and demos
- backend API services with structured models and schemas
- modular design suitable for extension and experimentation

## Architecture Summary

The project follows a modular architecture with distinct layers:

- Frontend layer: user-facing interface and interaction flow
- Backend layer: API business logic and service orchestration
- Agent layer: recommendation and intelligence workflows
- Data layer: database models, schemas, and seed/synthetic datasets
- Evaluation layer: validation and analysis of system behavior

## Repository Structure

```text
shelfmind/
├── README.md
├── docs/
│   ├── PROJECT_DOCUMENTATION.md
│   ├── SETUP.md
│   └── ...
├── backend/
│   ├── app/
│   ├── tests/
│   ├── requirements.txt
│   └── ...
├── .env.example
├── .gitignore
└── FreshOrbit-main.zip
```

## Technology Stack

The project structure indicates use of:

- Python for backend logic and application services
- FastAPI or similar API framework patterns
- SQL/database-backed storage for data persistence
- Pydantic-style schemas and models
- agent-driven business logic
- frontend assets and API contracts in the bundled design documents

## Getting Started

### Prerequisites

- Python 3.10+
- pip
- virtual environment support
- Git

### 1. Clone or extract the project

```bash
git clone https://github.com/Ganesh1-IFS/shelfmind.git
cd shelfmind
```

If you are using the packaged project archive, extract it first:

```bash
unzip FreshOrbit-main.zip
cd FreshOrbit-main
```

### 2. Create a virtual environment

```bash
python -m venv .venv
source .venv/bin/activate
```

On Windows:

```powershell
.venv\Scripts\activate
```

### 3. Install dependencies

```bash
cd backend
pip install -r requirements.txt
```

### 4. Configure environment variables

Copy the example environment file:

```bash
cp .env.example .env
```

Then update `.env` with the required local values.

### 5. Run the backend

```bash
python app/main.py
```

If the project uses a different entry point in your extracted source, follow the application-specific instructions in the docs.

## Project Workflow

The intended user journey is:

1. ingest product or inventory data
2. evaluate freshness and risk levels
3. detect high-waste or overstock items
4. generate recommendations
5. improve grocery operational decisions

## Testing

The repository includes a backend test folder. To run tests:

```bash
cd backend
pytest
```

This helps validate API behavior, schemas, agent logic, and data-driven decisions.

## Documentation

The repo includes documentation for:

- project overview
- setup procedures
- architecture and system design
- technology stack
- backend/frontend contracts
- demo flow
- database schema

Key documents include:

- `docs/PROJECT_DOCUMENTATION.md`
- `docs/SETUP.md`
- bundled design files inside the extracted project archive

## Notes on the Current Repository State

This repository currently contains a packaged project bundle (`FreshOrbit-main.zip`) in addition to documentation files. For full local development, extract the archive and work from the extracted project folder.

## Contributing

To contribute:

1. create a feature branch
2. make focused changes
3. keep documentation updated
4. run tests before submission
5. validate API or workflow changes thoroughly

## License

No explicit license is currently declared in the repository metadata. If this project is intended for public reuse or open-source distribution, it is recommended to add a standard license such as MIT or Apache-2.0.

## Future Improvements

Recommended next steps:

- finalize and document all environment variables
- expand API documentation
- add production deployment instructions
- unify frontend/backend onboarding guides
- standardize code comments and architecture notes
- add CI checks for linting and tests

## Summary

ShelfMind is a practical sustainability-focused platform centered on waste reduction in grocery operations. It combines AI/agent-style intelligence with structured backend services and data models to support more effective perishable inventory management.

This project is well-suited for hackathon and prototype use, and with stronger docs and deployment steps it can be further developed into a production-ready solution.
