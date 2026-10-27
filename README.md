# CDD Lab Experiment 9: Dockerfiles and Custom Containerized Applications

## Objective
Write Dockerfiles and build custom containerized applications.

## Duration
2 Hours

## Tasks
1. Write a multi-stage or optimized Dockerfile.
2. Build a custom application (web app, API, or script).
3. Use environment variables and volumes.
4. Optimize image size.
5. Document the build and run process.

## Sample Dockerfile Structure
```dockerfile
FROM python:3.11-slim
WORKDIR /app
COPY requirements.txt .
RUN pip install -r requirements.txt
COPY . .
CMD ["python", "app.py"]
```

## Expected Outcome
A well-documented custom containerized application with optimized Dockerfile.
