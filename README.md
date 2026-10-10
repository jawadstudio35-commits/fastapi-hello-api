# FastAPI Hello API

A simple beginner-friendly REST API built with Python, FastAPI, and Uvicorn. The project is managed using `uv`.

## About the Project

This is my first FastAPI project, created to understand the fundamentals of API development.

The API provides a simple JSON response through a GET endpoint.

## Technologies Used

- Python
- FastAPI
- Uvicorn
- uv
- Git and GitHub

## Project Structure

```text
fastapi/
├── src/
│   └── hello_api/
│       ├── __init__.py
│       └── main.py
├── pyproject.toml
├── uv.lock
├── README.md
├── LEARNING.md
└── .gitignore
```

## Installation

Make sure Python and uv are installed.

Clone the repository and open the project folder:

```powershell
git clone YOUR_GITHUB_REPOSITORY_URL
cd YOUR_REPOSITORY_FOLDER
```

Install the project dependencies:

```powershell
uv sync
```

## Run the API

```powershell
uv run uvicorn hello_api.main:app --reload --port 8000
```

## Available Endpoints

| Method | Endpoint | Description |
|---|---|---|
| GET | `/` | Returns a welcome message |
| GET | `/docs` | Opens interactive API documentation |

## Example Response

```json
{
  "message": "Hello Jawad's World"
}
```

## What I Learned

- Creating a Python project with uv
- Managing project dependencies
- Understanding virtual environments
- Creating a FastAPI application
- Defining a GET endpoint
- Returning JSON responses
- Running a development server with Uvicorn
- Testing endpoints through Swagger UI

## Future Improvements

- Add more API endpoints
- Learn POST, PUT, and DELETE methods
- Add request validation using Pydantic
- Connect a database
- Build a CRUD API

## Author

Jawad Haider

