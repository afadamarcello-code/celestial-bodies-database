# 🌌 Celestial Bodies Relational Database

A comprehensive PostgreSQL database architecture mapping the hierarchical relationship between astronomical bodies. This project demonstrates advanced SQL schema design, data normalization, and constraint management.

## 🛠️ Technical Highlights
- **Schema Architecture:** Designed a 5-table relational structure (Galaxy > Star > Planet > Moon).
- **Data Integrity:** Implemented `SERIAL PRIMARY KEY` and `REFERENCES` (Foreign Keys) to ensure strictly enforced hierarchical relationships.
- **Advanced Constraints:** Utilized `UNIQUE`, `NOT NULL`, and specific data types (`NUMERIC`, `BOOLEAN`, `TEXT`, `VARCHAR`) to meet complex business logic requirements.
- **Scale:** Populated with 40+ rows of unique data, including 6 galaxies, 6 stars, 12 planets, and 20 moons.

## 🚀 Database Schema
- **Galaxy Table:** The root container for all stellar systems.
- **Star Table:** Linked to Galaxies; contains physical properties.
- **Planet Table:** Linked to Stars; includes habitability and structural booleans.
- **Moon Table:** Linked to Planets; mapped via foreign key relationships.
- **Planet_Types:** A specialized lookup table for categorizing planetary structures.

## 📂 Project Structure
- `universe.sql`: The full database dump containing the schema and all data inserts.

---
*Part of the 120-Day Elite Data Architect Roadmap.*
