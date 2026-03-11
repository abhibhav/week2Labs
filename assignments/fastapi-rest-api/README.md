# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Learn how to design and implement RESTful APIs using the FastAPI framework in Python. By the end of this assignment, you will have created a simple API for managing resources, practiced handling HTTP requests, and understood the basics of API documentation and validation.

## 📝 Tasks

### 🛠️ Task 1: FastAPI Project Setup

#### Description
Set up a new FastAPI project and create a basic API endpoint.

#### Requirements
Completed program should:

- Install FastAPI and Uvicorn
- Create a main Python file (e.g., main.py)
- Implement a root endpoint (GET /) that returns a welcome message

### 🛠️ Task 2: CRUD Endpoints for a Resource

#### Description
Design and implement CRUD (Create, Read, Update, Delete) endpoints for a simple resource, such as a list of books or users.

#### Requirements
Completed program should:

- Define a Pydantic model for the resource (e.g., Book with id, title, author)
- Implement endpoints to create, read (all and by id), update, and delete resources
- Store resources in an in-memory list (no database required)

### 🛠️ Task 3: API Documentation and Validation

#### Description
Explore FastAPI's automatic documentation and add input validation to your endpoints.

#### Requirements
Completed program should:

- Use Pydantic models to validate input data
- Access the interactive API docs at /docs
- Add example data and field constraints to your models
