# Celestial Bodies Database 🌌🪐

A PostgreSQL database project mapping out galaxies, stars, planets, and moons to explore relational database structures.

## Technologies Used
* **PostgreSQL:** Relational database management.
* **SQL:** Schema creation, constraints (`PRIMARY KEY`, `FOREIGN KEY`), and data insertion.

## Project Structure
* `universe.sql`: The complete database dump containing the schema setup, table relationships, and populated celestial data.

## Database Structure

The main relationships are:

```text
Galaxy
  │
  └── Star
        │
        └── Planet
              │
              └── Moon
