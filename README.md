# XInsight — Application Summary

[![Tech Stack](https://img.shields.io/badge/Stack-XInsight-blue)](README.md)
[![Python](https://img.shields.io/badge/Python-3.11-blue)](https://www.python.org/)
[![Flask](https://img.shields.io/badge/Flask-2.3-important)](https://palletsprojects.com/p/flask/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-15-blue)](https://www.postgresql.org/)
[![Redis](https://img.shields.io/badge/Redis-7-orange)](https://redis.io/)
[![Docker](https://img.shields.io/badge/Docker-ready-blue)](https://www.docker.com/)

---

## Overview

XInsight is an enterprise-grade Twitter analytics platform that transforms a basic Flask proof-of-concept into a secure, scalable, and production-ready system.  
This README provides a complete summary of architecture, capabilities, deployment workflows, and operational guidance.

---

## Demo Video

> The video below plays directly from the repository (`./demo.mp4`).  
> **Note:** GitHub does not allow autoplay in README files.  
> However, autoplay works normally in browsers, GitHub Pages, or any local/hosted documentation viewer.

### ▶️ Application Demo

<video width="100%" src="./demo.mp4" controls autoplay muted loop playsinline>
  Your browser does not support the video tag.
</video>

---

## Executive Summary

- Modular, maintainable architecture using Flask application factory pattern  
- Production-grade environment using Docker, Gunicorn, Nginx, PostgreSQL, and Redis  
- Security features including authentication, RBAC, CSRF protection, rate limiting, and input validation  
- Observability built-in: structured logging, health checks, and Prometheus/Grafana compatibility  

---

## Key Capabilities

- Scalable backend with efficient database connections and Redis caching  
- Analytics pipeline supporting sentiment analysis, engagement metrics, and trending topics  
- Saved searches, search history, and export options (CSV, JSON, PDF)  
- Responsive UI using Bootstrap 5 and Chart.js visualizations  
- REST API with version-ready structure and standardized error responses  

---

## Deployment Options

### 🔧 Local Development

```powershell
pip install -r requirements.txt
flask --app app run --reload
