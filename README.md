![Linting](https://github.com/sudoDeVinci/devinci.cloud-backend/actions/workflows/linting.yml/badge.svg?branch=main)
![Type Check](https://github.com/sudoDeVinci/devinci.cloud-backend/actions/workflows/typecheck.yml/badge.svg?branch=main)

# Devinci.cloud Backend

A web application built with Flask and SQLite providing database and routing functionality for the website `devinci.cloud`.

## Project Structure

```
.
├── main.py
├── README.md
├── requirements.txt
├── logs/
│   └── db.log
|
└── utils/ 
    │ 
    ├── __init__.py
    ├── routes.py
    └── db/
        │ 
        ├── entities.py 
        ├── manager.py
        ├── services.py
        └── schema.py

```
