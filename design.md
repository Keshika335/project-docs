# Design Document

## System Architecture
- Client: Web browser (React frontend)
- Server: Node.js backend
- Database: PostgreSQL

## Data Flow
1. User submits form
2. Backend validates input
3. Data stored in database
4. Report generated and displayed

## Database Schema
- Users table
- Reports table
- Logs table

## API Design
- POST /login
- POST /upload
- GET /report/:id
