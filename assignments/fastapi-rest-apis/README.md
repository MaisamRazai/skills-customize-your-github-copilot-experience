# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Learn how to build a RESTful API using FastAPI by creating endpoints, validating request data, and returning structured JSON responses.

## 📝 Tasks

### 🛠️ Create API Endpoints

#### Description

Set up a FastAPI application and implement basic REST endpoints for managing a collection of items.

#### Requirements
Completed program should:

- Create a FastAPI app instance in a Python file.
- Implement at least two endpoints: one for retrieving items and one for adding a new item.
- Return JSON responses from each endpoint.

### 🛠️ Validate Input with Pydantic

#### Description

Use Pydantic models to validate incoming request data for the API.

#### Requirements
Completed program should:

- Define a Pydantic model for the request body of the POST endpoint.
- Validate required fields and types automatically.
- Return an error response if the request body is invalid.

### 🛠️ Document and Test API Behavior

#### Description

Ensure the API is easy to understand and test by using FastAPI's built-in documentation features.

#### Requirements
Completed program should:

- Expose interactive API docs at `/docs` or `/redoc` when the app is running.
- Include example request and response data in the endpoint definitions.
- Demonstrate the API by describing how to test the endpoints using a browser or a tool like `curl`.
