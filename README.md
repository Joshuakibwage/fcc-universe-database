# 🌌 Universe Database

[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?logo=postgresql&logoColor=white)](https://www.postgresql.org/)  
[![freeCodeCamp](https://img.shields.io/badge/freeCodeCamp-4BC51D?logo=freecodecamp&logoColor=white)](https://www.freecodecamp.org/)

A PostgreSQL relational database modeling **galaxies, stars, planets, moons, and comets**. Built as part of the **freeCodeCamp Relational Database Certification**.

---

## ⚡ Features

- 5 tables: `galaxy`, `star`, `planet`, `moon`, `comet`  
- Auto-incrementing primary keys & foreign key relationships  
- Sample data:
  - 6+ galaxies  
  - 6+ stars  
  - 12+ planets  
  - 20+ moons  
- Data types: `INT`, `NUMERIC`, `BOOLEAN`, `TEXT`, `VARCHAR`  
- Constraints: `NOT NULL`, `UNIQUE`  

---

## 🚀 Usage

```bash
git clone https://github.com/Joshuakibwage/fcc-universe-database.git
cd fcc-universe-database
psql -U freecodecamp -f universe.sql
