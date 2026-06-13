# 📘 Assignment: Persistent REST APIs with FastAPI and SQLite

## 🎯 Objective

Teach students how to build a RESTful API with FastAPI that stores and retrieves data using SQLite, so their application can preserve information across runs.

## 📝 Tasks

### 🛠️ Create a FastAPI app with CRUD endpoints

#### Description

Build a FastAPI application that exposes endpoints for creating, reading, updating, and deleting items.

#### Requirements
Completed program should:

- Create a FastAPI app in a Python file.
- Implement at least four endpoints: create item, read items, update item, and delete item.
- Return JSON responses from each endpoint.

### 🛠️ Use SQLite for persistence

#### Description

Store API data in SQLite so items are saved between server restarts.

#### Requirements
Completed program should:

- Use SQLite as the application database.
- Create a table for items with relevant fields.
- Save new items to the database and load existing items on startup.

### 🛠️ Validate data with Pydantic and document the API

#### Description

Validate request bodies with Pydantic models and make the API easy to test using FastAPI's documentation.

#### Requirements
Completed program should:

- Define Pydantic models for request and response data.
- Validate required fields and types for incoming requests.
- Expose interactive API docs at `/docs` or `/redoc`.
- Include example request/response data in the endpoint definitions.
