# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Learn how to build a RESTful API using the FastAPI framework, including defining endpoints, handling requests, and validating data.

## 📝 Tasks

### 🛠️ Create a Hello World Endpoint

#### Description
Set up a basic FastAPI application and create a root endpoint.

#### Requirements
Completed program should:
- Import FastAPI
- Instantiate the app
- Define a GET route at `/` that returns `{"message": "Hello World"}`
- Run the app using uvicorn

### 🛠️ Create an Item Resource

#### Description
Implement endpoints to manage a collection of items (CRUD operations).

#### Requirements
Completed program should:
- Implement a GET `/items` endpoint to list all items
- Implement a POST `/items` endpoint to add a new item
- Implement a GET `/items/{item_id}` endpoint to retrieve a specific item
- Use Pydantic models for data validation
