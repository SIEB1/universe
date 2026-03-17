# Celestial Universe Database

This project is part of the **Relational Database Certification** from [freeCodeCamp](https://www.freecodecamp.org/). It consists of a PostgreSQL database named `universe` that models various celestial bodies and their relationships.

## 🚀 Features

The database includes the following tables and relationships:
- **Galaxy**: The largest structures in the universe.
- **Star**: Stars located within galaxies (One-to-Many).
- **Planet**: Planets orbiting stars (One-to-Many).
- **Moon**: Moons orbiting planets (One-to-Many).
- **Galaxy Type**: A categorical table for different galaxy shapes (One-to-Many).

## 🛠️ Tech Stack
- **Database**: PostgreSQL
- **Language**: SQL

## 📊 Database Schema
The project demonstrates core relational database concepts:
- **Primary Keys**: Every table has a unique `_id` column.
- **Foreign Keys**: Relationships established between celestial bodies.
- **Constraints**: Use of `UNIQUE`, `NOT NULL`, and various data types (`INT`, `NUMERIC`, `TEXT`, `BOOLEAN`, `VARCHAR`).

## ⚙️ How to restore the database
To rebuild the database from the provided script, use the following command in your terminal:
```bash
psql -U postgres < universe.sql
