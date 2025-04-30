# 📦 LibreERP Database

This repository contains the SQL script, ER and relational diagrams, and seed data for the **Libre-ERP** project.

## 🎯 Objective

Provide a centralized version-controlled environment for managing:
- Database scripts
- ER and relational diagrams
- Seed data

---

## 📐 ER Model

The current database model supports core modules such as:
- User management
- Product inventory
- Sales and transactions
- Time zone configuration

> You can find diagrams in `/diagrams/`

---

## 📁 Structure

```bash
libreerp-database/
├── scripts/
│   ├── 001_create_tables.sql
│   ├── 002_create_sp.sql
│   └── 003_insert_initial_data.sql
├── diagrams/
│   ├── rel_model.drawio
│   └── er_model.drawio
├── README.md
└── LICENSE
