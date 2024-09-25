# RESTful API for Product Catalog

Welcome, Coder!

This project is a RESTful API designed for managing a product catalog. It allows users to perform CRUD operations (Create, Read, Update, and Delete) on product information. The project is built using FastAPI, SQLAlchemy, and SQLite, offering a modern and efficient approach to API development.

## Features

- Create new products
- Retrieve product details
- Update existing product information
- Delete products
- Interactive API documentation with Swagger UI

## Requirements

To run this project, ensure you have Python installed along with the following packages:
- `fastapi`
- `uvicorn`
- `sqlalchemy`
- `pydantic`
- `alembic`
- `pytest`
- `httpx`

## Tools and Technologies Used

- Programming Language: Python
- Framework: FastAPI
- Database: SQLite
- ORM: SQLAlchemy
- Migrations: Alembic
- Data Validation: Pydantic
- Development Environment: Visual Studio Code (VSCode)
- Testing: Pytest

## Installation and Setup

1. Clone the repository:
```
git clone https://github.com/yourusername/yourrepository.git
```

2. Navigate to the project directory:
```
cd yourrepository
```

3. Install the dependencies:
```
pip install -r requirements.txt
```

4. Run the development server:
```
uvicorn main:app --reload
```

5. Open your browser and navigate to:
```
http://localhost:8000/docs
```
This will access the interactive API documentation.

## Migrations

1. Initialize Alembic:
```
alembic init alembic
```

2. Create and apply migrations:
```
alembic revision --autogenerate -m "Initial migration"
alembic upgrade head

alembic revision --autogenerate -m "add new column category"
alembic upgrade head
```

3. For future schema changes, follow similar steps to create and apply migrations.

## Testing

To run unit tests, use Pytest:
```
pytest testfilename.py
```

## Learn More

To learn more about FastAPI, Alembic, and other tools used in this project, see the following resources:

- [FastAPI Documentation](https://fastapi.tiangolo.com/) – Learn about FastAPI's features and API
- [SQLAlchemy Documentation](https://docs.sqlalchemy.org/) – Explore SQLAlchemy’s ORM
- [Alembic Documentation](https://alembic.sqlalchemy.org/) – Learn about database migrations

## Deployment

The easiest way to deploy this FastAPI app is using the Koyeb platform.

Check out the [Koyeb deployment documentation](https://www.koyeb.com/docs) for more details.

---
