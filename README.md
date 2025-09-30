# DevOps Demo Project

This is a simple DevOps project demonstrating:

- Python Flask app
- Docker containerization
- Jenkins CI/CD pipeline

## How to Run

1. Build Docker image:
```bash
docker build -t devops-demo-app ./app
```
2. Run Docker container:
```bash
docker run -p 5000:5000 devops-demo-app
```
3. Access the app at `http://localhost:5000`
