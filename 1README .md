# Workflow Decision System

A configurable workflow engine that processes requests,
evaluates rules, executes workflows, and records audit trails.

Features

- Configurable workflow via JSON
- Rules engine
- Idempotent request handling
- External dependency simulation
- Retry handling
- Audit logs
- REST API

Run

pip install -r requirements.txt

uvicorn app.main:app --reload
