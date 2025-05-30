# 🐳 Docker Compose: Flask + Redis Starter

A lightweight development stack combining **Flask** and **Redis** using **Docker Compose**. This project demonstrates how to spin up a simple Python web service with Redis integration for backend caching or key-value storage.

---

## 📌 Project Overview

* **Name**: docker-compose-basic-redis-web
* **Stack**: Docker, Flask, Redis
* **Goal**: Provide a basic development environment for building Python web apps backed by Redis
* **Use Case**: Local testing, prototyping, container-based microservice setup

---

## 📁 Project Structure

```
├── .gitattributes        # Git settings (optional, not functionally required)
├── app.py                # Main Flask application
├── compose.yaml          # Docker Compose configuration for web + Redis
├── Dockerfile            # Docker build file for the Flask app
├── requirements.txt      # Python dependencies
```

---

## 🚀 Getting Started

### Prerequisites

* [Docker](https://www.docker.com/products/docker-desktop)
* [Docker Compose](https://docs.docker.com/compose/)

### Installation Steps

```bash
# 1. Clone the repository
git clone https://github.com/davidhernandez-adm/docker-compose-basic-redis-web.git
cd docker-compose-basic-redis-web

# 2. Start the services
docker-compose -f compose.yaml up --build

# 3. Access the web service
open http://localhost:8000  # Or navigate via your browser
```

---

## 📦 Technologies Used

* **Python** – Core programming language
* **Flask** – Lightweight web framework
* **Redis** – In-memory key-value store
* **Docker** – Containerization engine
* **Docker Compose** – Multi-container orchestration

---

## 🧪 Testing and Coverage

> No unit tests included yet. Test functionality manually by accessing endpoints and inspecting Redis keys.

---

## 🧠 Key Challenges & Learnings

* Learned how to set up interdependent services using Docker Compose
* Explored environment variable configuration and volume mounting for live reload
* Gained insight into lightweight caching via Redis from Flask

---

## 📷 Screenshots or Live Demo

> Visit `http://localhost:8000` to interact with the Flask service.

---

## 📜 License

[MIT](https://opensource.org/licenses/MIT)

---

> Developed by [David Hernández](https://github.com/davidhernandez-adm) for Docker Compose practice and backend development experimentation.
