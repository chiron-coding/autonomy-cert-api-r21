# Autonomous Certification API

A REST API for autonomous certification management.

## Features

- Certificate issuance and validation
- Certification workflow automation

## Quick Start

```bash
pip install -r requirements.txt
uvicorn app.main:app --reload
```

## API Documentation

Once running, visit `/docs` for interactive Swagger documentation.

## Endpoints

- `GET /health` - Health check
- `POST /certifications` - Create a new certification
- `GET /certifications` - List all certifications
- `GET /certifications/{id}` - Get a certification by ID
## Quick Start

```bash
pip install -r requirements.txt
uvicorn app.main:app --reload
```
