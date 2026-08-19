# ProStackHub DevOps Internship - Task 2

## Project Overview
This project is part of the ProStackHub DevOps Internship. It demonstrates the containerization of a multi-tier application using *Docker* and orchestration via *Docker Compose*[span_0](start_span)[span_0](end_span). The architecture includes a database, a backend service, and a frontend reverse proxy, adhering to production-like packaging standards without requiring paid cloud infrastructure[span_1](start_span)[span_1](end_span).

---

## Architecture & Components
* *Containers & Orchestration:* Docker & Docker Compose[span_2](start_span)[span_2](end_span)
* *Database Layer:* PostgreSQL (Official Alpine image with health checks and persistent volume storage)[span_3](start_span)[span_3](end_span)
* *Backend Layer:* Node.js (Alpine container configured via environment variables)[span_4](start_span)[span_4](end_span)
* *Frontend / Reverse Proxy:* Nginx (Alpine container routing traffic)[span_5](start_span)[span_5](end_span)
* *Configuration:* Managed securely using environment-based configuration (.env)[span_6](start_span)[span_6](end_span)

---

## Project Structure
```text
PROSTACKHUB_TASK2/
├── .env                  # Environment variables for database and backend
└── docker-compose.yml    # Multi-container orchestration setup