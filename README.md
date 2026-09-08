# Flask CRUD REST API

A backend REST API developed using **Python Flask**, **SQLAlchemy**, and **PostgreSQL**, with **Docker** for containerization. The project implements complete CRUD (Create, Read, Update, Delete) operations through RESTful API endpoints.

## 🛠️ Tech Stack

* **Language:** Python
* **Framework:** Flask
* **ORM:** SQLAlchemy
* **Database:** PostgreSQL
* **Containerization:** Docker & Docker Compose
* **API Testing:** Postman

## ✨ Features

* Create new users
* Retrieve all users
* Retrieve a user by ID
* Update existing user details
* Delete users
* PostgreSQL database integration
* SQLAlchemy ORM for database operations
* Dockerized Flask application
* RESTful API architecture

## 📁 Project Structure

```text
flask-crud-api/
│
├── app.py
├── requirements.txt
├── Dockerfile
├── docker-compose.yml
└── README.md
```

## 🔌 API Endpoints

| Method   | Endpoint      | Description                      |
| -------- | ------------- | -------------------------------- |
| `GET`    | `/test`       | Check whether the API is running |
| `POST`   | `/users`      | Create a new user                |
| `GET`    | `/users`      | Retrieve all users               |
| `GET`    | `/users/<id>` | Retrieve a user by ID            |
| `PUT`    | `/users/<id>` | Update a user                    |
| `DELETE` | `/users/<id>` | Delete a user                    |

## 🚀 Getting Started

### Prerequisites

Make sure the following are installed:

* Python
* Docker
* Docker Compose
* Postman (for API testing)

### Clone the Repository

```bash
git clone <YOUR-GITHUB-REPOSITORY-URL>
cd flask-crud-api
```

### Run the Application

Build and start the application using Docker Compose:

```bash
docker-compose up --build
```

The Flask API and PostgreSQL database will run in Docker containers.

## 🧪 API Testing

The API can be tested using **Postman**.

Example request:

```http
POST /users
```

Example request body:

```json
{
    "name": "John",
    "email": "john@example.com"
}
```

## 🗄️ Database

The application uses **PostgreSQL** for data storage and **SQLAlchemy** to interact with the database using an ORM-based approach.

## 🐳 Docker

Docker is used to containerize the application and database.

**Docker Compose** manages the Flask application and PostgreSQL services.

## 📚 Learning Outcomes

Through this project, I gained practical experience in:

* Developing RESTful APIs with Flask
* Implementing CRUD operations
* Working with PostgreSQL
* Using SQLAlchemy ORM
* Containerizing applications with Docker
* Managing multi-container applications using Docker Compose
* Testing APIs using Postman

## 👩‍💻 Author

**Velishoju Sathwika**

[GitHub](https://github.com/velishojusathwika)
