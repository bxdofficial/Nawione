# Nawi Design Agency Website

## Overview
A full-stack design agency website with React frontend and Flask backend. The site offers bilingual support (English/Arabic) and includes user authentication, portfolio management, service listings, and contact forms.

## Recent Changes (September 20, 2025)
- Successfully imported GitHub project to Replit environment
- Configured Python 3.11 and Node.js 20 modules  
- Installed all Python dependencies including Flask, SQLAlchemy, JWT, and PostgreSQL support
- Installed React frontend dependencies with Vite build system
- Built React frontend into Flask static files directory
- Configured Flask to serve on port 5000 with PostgreSQL database
- Set up automated workflows for development and deployment
- Configured deployment for production with autoscale using Gunicorn

## Project Architecture
- **Backend**: Python Flask with SQLAlchemy ORM
- **Database**: PostgreSQL (provided by Replit environment)
- **Frontend**: React with Vite, Tailwind CSS, and various UI libraries
- **Authentication**: JWT-based with refresh tokens
- **Deployment**: Single-server architecture with frontend built into backend static files

## Key Features
- Bilingual content support (English/Arabic)
- User authentication and admin panel
- Portfolio management with image uploads
- Service listings and design request handling
- Contact form with email notifications
- Responsive design with modern UI components

## Configuration
- Development server runs on port 5000 serving both frontend and API
- PostgreSQL database automatically configured via environment variables
- Email configuration available via environment variables
- Admin user seeded on first run (check .env for credentials)

## File Structure
- `frontend/` - React application with Vite
- `backend/` - Flask application with models, utils, and API routes
- `backend/build/` - Built frontend files served by Flask
- `backend/.env` - Environment configuration