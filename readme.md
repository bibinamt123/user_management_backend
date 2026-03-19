# User Management Dashboard - Backend

## Tech Stack
- FeathersJS
- PostgreSQL
- Knex

## Setup Instructions

1. Clone repository
git clone <repo-link>

2. Install dependencies
npm install

3. Setup PostgreSQL database

4. Run migrations
npx knex migrate:latest

5. Start server
npm start

## API Endpoints

GET /users  
POST /users  
PATCH /users/:id  

## Features
- CRUD operations
- Soft delete using `deleted` field
