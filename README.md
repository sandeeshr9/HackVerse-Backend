# HackVerse Backend

Database setup for the HackVerse application.

## Technologies
- Supabase
- PostgreSQL
- SQL

## Database
The `hackathons` table stores hackathon names, organizers, dates, modes, tags, and colors.

## Security
Row Level Security (RLS) is enabled, with a policy allowing public read access to hackathons.

## Setup
The `migrations` folder contains the SQL database setup script.