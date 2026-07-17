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
| GET | `/api/activities` | [describe] |
| POST | `/api/bookings` | [describe] |
| ... | ... | ... |

*(Fill in your real routes — even a partial table is more useful than none.)*

## Getting Started

### Prerequisites
- Node.js (v[X]+)
- [Database] running locally or a connection string

### Installation

```bash
git clone https://github.com/BenjaminZadorian/FullStackCourseWork-Backend.git
cd FullStackCourseWork-Backend
npm install
```

### Environment Variables

Create a `.env` file in the root:

```
PORT=
DATABASE_URL=
[OTHER_VAR]=
```

### Run locally

```bash
npm start
```

The API will be available at `http://localhost:[PORT]`.

## Deployment

Deployed on [Render.com](https://render.com) with the root directory set to this repo.
