# Web Server Layer TS App

A simple layered Node.js + TypeScript application using **Express**, **Sequelize**, and **SQLite**.  
This project demonstrates a clean architecture with separation of concerns across **Controller**, **Service**, **Repository**, and **Model** layers.

---

## Features

- RESTful API built with Express
- TypeScript with decorators (`sequelize-typescript`)
- SQLite for local persistence
- Layered architecture:
  - `controllers/` — API endpoints
  - `services/` — business logic
  - `repositories/` — database interaction
  - `models/` — ORM entities
  - `dtos/` — data transfer objects
- Auto-sync database schema with Sequelize

---

