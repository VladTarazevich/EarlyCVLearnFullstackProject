# 🕰️ Interactive Full-Stack CV (Time Capsule Project)

![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2CA5E0?style=flat&logo=docker&logoColor=white)

> 💡 **Developer's Note (2026):** 
> *This is an archival project from my 1st year of university. I built it to pass a JavaScript exam, but to challenge myself, I decided to use **TypeScript** and implement a full **backend ecosystem** (Python, PostgreSQL, Alembic, Docker, Nginx) before I even knew the standard REST API practices. While the code quality and architecture here reflect my absolute beginner stage, I keep this repository public as a reminder of where my backend journey began and how much my engineering skills have evolved since then.*

## 📋 About The Project
This was my very first attempt at building a multi-container full-stack application. It is an interactive CV application that allows users to leave feedback and reviews directly into a connected database.

### 🛠️ Early Tech Stack Explored:
* **Frontend:** TypeScript (chosen over vanilla JS to learn strict typing early on).
* **Backend:** Python with Uvicorn setup.
* **Database & Migrations:** PostgreSQL integrated with Alembic for early schema version control.
* **Infrastructure:** First steps into DevOps using Docker, Docker Compose, and Nginx as a web server.

## 🚀 Running the Time Capsule
*(Warning: This is legacy code left exactly as it was written years ago!)*

To spin up the environment:
```bash
docker-compose up --build
```
This will initialize the frontend, backend, and PostgreSQL containers.

## 🌱 What I Learned Here
This project was my "sandbox" for understanding how different services talk to each other. It taught me the hard way about container networks, database migrations, and the importance of RESTful design (which I didn't use here, but learned immediately after!).
