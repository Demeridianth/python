# 🎬 FastAPI DVD Rental API  

⚠️ **Note**: This app will automatically create a new table named **`films`** in your PostgreSQL database if it doesn’t already exist.  

A simple backend API built with **FastAPI**, **SQLAlchemy**, and **PostgreSQL**.  
It manages a collection of films with CRUD operations and can also inject films from a CSV file.  

This project is designed for portfolio purposes and can be used as a backend for a frontend application.  

---
## To run the app:
- fastapi dev main.py
- OR
- uvicorn main:app --reload


## 🚀 Features  
- **CRUD for Films**  
  - Create new films  
  - Read all films or a single film by ID  
  - Update film details (title, description, release year)  
  - Delete films  
- **CSV Injection** – bulk import films from `films_pipe.csv`  
- **Interactive API docs** available at:  
  - Swagger UI → [http://127.0.0.1:8000/docs](http://127.0.0.1:8000/docs)  
  - ReDoc → [http://127.0.0.1:8000/redoc](http://127.0.0.1:8000/redoc)  

---

## 🛠 Tech Stack  
- [FastAPI](https://fastapi.tiangolo.com/) – web framework  
- [SQLAlchemy](https://www.sqlalchemy.org/) – ORM  
- [PostgreSQL](https://www.postgresql.org/) – database  
- [Pandas](https://pandas.pydata.org/) – CSV parsing  

---


