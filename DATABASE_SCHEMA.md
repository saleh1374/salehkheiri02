# Database Schema

## Overview

This document describes the PostgreSQL database schema for the Salehkheiri application.

## Tables

### Users
- `id` (UUID, Primary Key)
- `email` (VARCHAR, Unique)
- `username` (VARCHAR, Unique)
- `password` (VARCHAR, Hashed)
- `created_at` (TIMESTAMP)
- `updated_at` (TIMESTAMP)

### Example Structure

```sql
CREATE TABLE users (
    id UUID PRIMARY KEY DEFAULT gen_random_uuid(),
    email VARCHAR(255) UNIQUE NOT NULL,
    username VARCHAR(100) UNIQUE NOT NULL,
    password VARCHAR(255) NOT NULL,
    created_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP,
    updated_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP
);
```

## Migrations

All database migrations are stored in the `database/migrations/` directory.

## Setup

1. Create a PostgreSQL database
2. Run migrations
3. Verify schema with Prisma Studio
