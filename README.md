**Full-stack developer focused on FastAPI, React and TypeScript.**

I build web applications end to end: from asynchronous REST and WebSocket APIs to type-safe user interfaces, persistent data layers, automated testing and containerized deployment.

## About me

* Primary stack: **Python, FastAPI, React and TypeScript**
* Building maintainable full-stack applications, REST APIs and real-time features
* Working with asynchronous processing, background jobs and external services
* Interested in application architecture, security, observability and developer experience
* Using **Rust** for desktop applications, local AI and performance-oriented software

## Technology stack

### Frontend

![React](https://img.shields.io/badge/React-20232A?logo=react\&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript\&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript\&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?logo=vite\&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5\&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3\&logoColor=white)

### Backend and data

![Python](https://img.shields.io/badge/Python-3776AB?logo=python\&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi\&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?logo=pydantic\&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql\&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?logo=celery\&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?logo=redis\&logoColor=white)

### Infrastructure and tools

![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker\&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?logo=nginx\&logoColor=white)
![Caddy](https://img.shields.io/badge/Caddy-1F88C0?logo=caddy\&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?logo=git\&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions\&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux\&logoColor=black)

### Additional technologies

![Rust](https://img.shields.io/badge/Rust-000000?logo=rust\&logoColor=white)

---

## Featured projects

### [Live Stream Monitor](https://github.com/ivangor246/live_stream)

A self-hosted platform for managing, publishing and watching live-stream events on a personal server or private network.

It combines a React dashboard, a FastAPI backend, PostgreSQL and MediaMTX into a containerized deployment with real-time updates, access control and protected recordings.

**Highlights:**

* Frontend built with **React, TypeScript and Vite**
* REST and WebSocket backend built with **FastAPI and Pydantic**
* Persistent storage with **PostgreSQL and Alembic migrations**
* RTMP publishing with WebRTC playback and automatic HLS fallback
* Real-time viewer counts, reactions and stream-status updates
* Administrator, operator and viewer roles with HttpOnly cookie sessions
* Private streams with revocable viewer links and short-lived media credentials
* Stream recording with a protected fMP4 archive
* Health checks, structured JSON logging and Prometheus-compatible metrics
* Docker Compose deployment with optional Caddy-based HTTPS configuration
* Automated linting, backend tests and continuous integration
* PostgreSQL and recording backup and restore tools

[View repository](https://github.com/ivangor246/live_stream)

---

### [Domain Analyzer](https://github.com/ivangor246/domain-analyzer)

A self-hosted full-stack application for analyzing public domain infrastructure.

It collects registration, DNS, network and security-related information and presents the results through a React interface backed by an asynchronous FastAPI service.

**Highlights:**

* Asynchronous API built with **FastAPI and Pydantic**
* Frontend built with **React, TypeScript and Vite**
* RDAP, DNS, GeoIP, HTTP, TLS and TCP analysis
* Background job processing with **Celery and Redis**
* Progress tracking, cancellation and partial results
* Frontend API types generated from the OpenAPI schema
* Rate limiting, structured logging and Prometheus-compatible metrics
* Dockerized backend, worker, Redis and Nginx frontend
* Automated backend and frontend tests
* Security restrictions for private and reserved network targets

[View repository](https://github.com/ivangor246/domain-analyzer)

---

### [Gen Music AI](https://github.com/ivangor246/gen_music_ai)

A cross-platform desktop application for generating multi-instrument music locally with AI.

The application performs inference entirely on the CPU, without cloud services or a dedicated GPU.

**Highlights:**

* Built with **Rust, Candle and Iced**
* Local AI inference
* Configurable instruments and generation parameters
* Built-in playback and timeline visualization
* MIDI and WAV export
* Automated tests and CI checks
* Releases for Linux, Windows and macOS

[View repository](https://github.com/ivangor246/gen_music_ai) · [Latest release](https://github.com/ivangor246/gen_music_ai/releases/latest)

---

## Current focus

* Building production-oriented applications with **FastAPI and React**
* Designing REST and WebSocket APIs for asynchronous and real-time systems
* Creating type-safe frontend integrations with **TypeScript and OpenAPI**
* Working with PostgreSQL data models and database migrations
* Implementing authentication, authorization and secure resource access
* Improving application testing, observability and operational reliability
* Packaging and deploying self-hosted applications with Docker
