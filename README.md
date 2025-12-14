# MVTPS – Maritime Vessel Tracking & Port Analytics System

This project is a full-stack web application built using:

- Backend: Django REST Framework
- Authentication: JWT (SimpleJWT with blacklist support)
- Database: SQLite
- Frontend: React

## Features
- User authentication (Login / Register)
- JWT-based protected APIs
- Token blacklist on logout
- Role-based access
- Frontend integration using React
- Token visibility via browser DevTools (Network & Application tabs)

## Tech Stack
- Django, DRF
- SimpleJWT
- SQLite
- React, Axios

## How to Run
### Backend
```bash
cd backend
python manage.py runserver

## Frontend
cd frontend
npm install
npm start

