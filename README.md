# Authenticate Users with FastAPI and Token Authentication

## Introduction

This is a simple project to demonstrate how to use FastAPI with OAuth2 and JWT.

## Requirements

### Create a virtual environment
```
python -m venv venv
```

### Activate the virtual environment
```
source venv/bin/activate
```

### Install the requirements
```
pip install fastapi
pip install uvicorn[standard]
pip install python-multipart
pip install python-jose[cryptography]
pip install passlib[bcrypt]
```

## Generate a secret key
```
openssl rand -hex 32
```

## Run the application
```
uvicorn main:app --reload
```

## Test the application
```
http://localhost:8000/docs
```

## References

- [Youtube](https://youtu.be/5GxQ1rLTwaU)

```

```