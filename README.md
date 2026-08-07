# FlyRank CRUD API

> A REST API built with **FastAPI** during the **Backend AI Engineer Internship** at **FlyRank**.

This repository documents the development of a production-oriented CRUD API while applying software engineering principles, backend best practices, and modern Python development.

Rather than being a finished project, this repository represents my learning journey and technical growth throughout the internship.

---

# Project Goals

The main objectives of this project are:

* Build a RESTful API using FastAPI
* Learn modern backend development practices
* Apply clean project organization
* Develop production-oriented coding habits
* Improve software architecture knowledge
* Practice Git and GitHub workflows
* Document every stage of development

---

# Current Status

🚧 **In Development**

This project is actively evolving during the internship. New features, improvements, and refactoring will be introduced through small, well-documented commits.

---

# Tech Stack

* Python 3.12
* FastAPI
* Uvicorn

Future additions may include:

* Pydantic
* SQLAlchemy
* SQLite / PostgreSQL
* Docker
* Pytest
* GitHub Actions

---

# Project Structure

```text
flyrank-crud-api/
│
├── app/
│   ├── __init__.py
│   └── main.py
│
├── .gitignore
├── README.md
└── requirements.txt
```

As the project grows, the structure will evolve into a modular architecture including routers, schemas, models, services, and database integration.

---

# Getting Started

## Clone the repository

```bash
git clone https://github.com/maurosopranadev/flyrank-crud-api.git
cd flyrank-crud-api
```

---

## Create a virtual environment

```bash
python -m venv venv
```

---

## Activate the virtual environment

### Windows

```bash
venv\Scripts\activate
```

### Linux / macOS

```bash
source venv/bin/activate
```

---

## Install dependencies

```bash
pip install -r requirements.txt
```

---

## Run the server

```bash
uvicorn app.main:app --reload
```

---

# Interactive API Documentation

FastAPI automatically generates interactive documentation.

Swagger UI

```
http://127.0.0.1:8000/docs
```

ReDoc

```
http://127.0.0.1:8000/redoc
```

---

# Learning Objectives

This project is being used to strengthen practical knowledge in:

* REST APIs
* HTTP methods
* FastAPI
* Python backend development
* Request validation
* Software architecture
* Clean code principles
* Version control with Git
* GitHub collaboration
* API documentation

---

# Development Roadmap

## Project Setup

* [x] Initialize Git repository
* [x] Configure GitHub repository
* [x] Configure `.gitignore`
* [x] Organize project structure
* [x] Configure FastAPI application

## Backend Development

* [ ] CRUD endpoints
* [ ] Request validation
* [ ] Response models
* [ ] Exception handling
* [ ] Dependency injection

## Database

* [ ] Database integration
* [ ] ORM configuration
* [ ] Data persistence

## Quality

* [ ] Unit tests
* [ ] Integration tests
* [ ] Logging
* [ ] Error handling improvements

## Deployment

* [ ] Docker
* [ ] Cloud deployment
* [ ] CI/CD
* [ ] Production configuration

---

# Commit Philosophy

This repository follows a commit history where each commit represents a single logical change.

Examples:

* Initial project setup
* Add .gitignore and remove Python cache files
* Refactor project structure into app package
* Add CRUD endpoints
* Implement request validation
* Configure database

This approach makes the project's evolution easier to understand and review.

---

# About This Repository

This repository is intentionally developed in incremental steps.

Instead of uploading a finished solution, every architectural decision, refactoring, and new feature is committed separately to reflect a real software development workflow.

The goal is not only to build a working API, but also to demonstrate professional engineering practices throughout the development process.

---

# Author

**Mauro Soprana**

Backend & AI Engineering Student

GitHub

https://github.com/maurosopranadev

LinkedIn

(Coming soon)
