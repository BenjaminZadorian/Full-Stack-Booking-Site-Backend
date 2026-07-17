# After-School Activities Booking Site — Backend

Backend API for a full-stack booking platform that lets parents/students browse and book after-school activities. Built as a team project at Middlesex University.

🔗 **Frontend repo:** [FullStackCourseWork-Frontend](https://github.com/BenjaminZadorian/FullStackCourseWork-Frontend)
🔗 **Live demo:** [https://fullstackcoursework-backend.onrender.com]

---

## Overview

This service handles activity listings, user accounts, and booking requests for the platform. It exposes a REST API consumed by the [Vue.js frontend](https://github.com/BenjaminZadorian/FullStackCourseWork-Frontend).

## Tech Stack

- **Runtime:** Node.js
- **Framework:** Pure Javascript
- **Database:** [MongoDB]
- **Hosting:** Render.com, AWS

## Features

- [User registration and login]
- [Browse/search available activities]
- [Create, view, and cancel bookings]
- [Admin endpoints for managing activity listings]

## API Endpoints

| Method | Endpoint | Description |
|---|---|---|
| GET | `/lessons/` | Return all lessons available |
| PUT | `/lessons/:id` | Update available spaces of a lesson, after order is confirmed |
| POST | `/lessons/` | Create a new lesson |
| DELETE | `/lessons/:id` | Delete a selected lesson |
| GET | `/lessons/search` | Search database for a specific lesson |
| POST | `/login/` | Log user in |
| POST | `/orders/` | Create a new order |
| GET | `/orders/user/:userId` | Get all orders from a chosen user |
| POST | `/register` | Register a new user |



## Getting Started

### Prerequisites
- Node.js (v23+)
- [Database] running locally or a connection string

### Installation

```bash
git clone https://github.com/BenjaminZadorian/FullStackCourseWork-Backend.git
cd FullStackCourseWork-Backend
npm install
```

### Run locally

```bash
npm start
```

The API will be available at `http://localhost:[PORT]`.

## Deployment

Deployed on [Render.com](https://render.com) with the root directory set to this repo.
