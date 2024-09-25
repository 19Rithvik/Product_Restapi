RESTful API for Product Catalog
Welcome, Coder!

This project is a RESTful API for managing a product catalog. It allows users to create, read, update, and delete product information. The project is built using FastAPI, SQLAlchemy, and SQLite, offering a modern and efficient approach to API development.

You can start editing the API by modifying main.py. The server will auto-reload and reflect changes as you update the file.

Tools and Technologies Used
Programming Language: Python
Framework: FastAPI (for building the API)
Database: SQLite (for data storage)
ORM: SQLAlchemy (for database interactions)
Migrations: Alembic (for handling database schema changes)
Data Validation: Pydantic (for defining data models and validation)
Development Environment: Visual Studio Code (VSCode)
Testing: Pytest (for unit testing)
Packages
This project uses the following Python packages:

fastapi
uvicorn
sqlalchemy
pydantic
alembic
pytest
httpx

Getting Started
First, run the development server:

bash
Copy code
uvicorn main:app --reload
Open http://localhost:8000/docs with your browser to view the interactive API documentation.

Learn More
To learn more about FastAPI, Alembic, and the other technologies used in this project, take a look at the following resources:

FastAPI Documentation – Learn about FastAPI's features and API.
SQLAlchemy Documentation – Explore SQLAlchemy's ORM capabilities.
Alembic Documentation – Learn about database migrations.
You can also check out the GitHub repository for this project — feedback and contributions are welcome!

Deploy on Koyeb
The easiest way to deploy your FastAPI app is to use the Koyeb Platform.

Check out the Koyeb deployment documentation for more details.
