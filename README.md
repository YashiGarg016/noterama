# 📒 Noterama

Noterama is a microservices‑based notes system built with **Node.js** and **Angular**.  
It provides a full stack experience with a frontend app, backend APIs, and a worker service — all containerized with Docker for easy deployment.

---

## Features
- User registration and login
- Create, view, update, and delete notes
- View detailed note information
- Share notes with other users
- Group notes together and browse group collections
- Mark notes as favourites
- Set reminders on notes

---

## Tech Stack
- **Frontend:** Angular  
- **Backend:** Node.js (Express APIs)  
- **Worker Services:** Node.js  
- **Database:** MongoDB  
- **Containerization:** Docker & Docker Compose  

---

## Getting Started

### Prerequisites
- [Docker Desktop](https://www.docker.com/products/docker-desktop) installed and running

### Run with Docker Compose
Clone the repository and start all services:
```bash
git clone <your-repo-url> noterama
cd noterama
docker-compose up --build
