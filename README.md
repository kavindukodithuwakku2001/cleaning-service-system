# Cleaning Service Management System

A web application for booking and managing cleaning services with an admin panel.

## Setup
1. Clone the repo: `git clone https://github.com/kavindukodithuwakku2001/cleaning-service-system.git`
2. Install Node.js and SQLite.
3. Backend setup:
   - `cd backend`
   - `npm install`
   - Configure `.env` (see `.env.example`)
   - `npm start`
4. Frontend setup:
   - `cd frontend`
   - `npm install`
   - `npm start`
5. Database: Uses SQLite (`database.db` in `/backend`).

## API Endpoints
- `GET /bookings`: List user bookings.
- `POST /bookings`: Create a booking.
- `PUT /bookings/:id`: Update a booking.
- `DELETE /bookings/:id`: Delete a booking.

## Tech Stack
- Frontend: React, Material UI
- Backend: Node.js, Express, SQLite, Sequelize# cleaning-service-system