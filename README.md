
# FastAPI and Postgres Dev Environment with Codespadces

## Pydantic versus SQLAlchemy

[Pydantic](https://docs.pydantic.dev/latest/) is for data validation and settings managment using Python type annotations. [SQLAlchemy]() is a SQL toolkit and Object Relational Mapper (ORM).

## Running the sample

1. Copy *.env.devcontainer* to *.env*.

2. Start the web app:

  ```
  uvicorn app:app --reload
  ```

## Files in the project

/devcontainer
  devcontainer.json
  docker-compose.yaml
  Dockerfile
.env.devcontainer
main.py
requirements.txt