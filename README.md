# MLOps_Docker_Master

# Docker Tutorial 🚀

This guide shows the basic workflow of building, tagging, pushing, and pulling Docker images.

## 1. Build Docker Image
```bash
docker build -t myapp:latest .
```

## 2. Run Container
```bash
docker run -d -p 8080:8080 myapp:latest
```

## 3. Tag Your Image
```bash
docker tag myapp:latest your-dockerhub-username/myapp:1.0
```

## 4. Login to DockerHub
```bash
docker login
```

## 5. Push Image to DockerHub
```bash
docker push your-dockerhub-username/myapp:1.0
```

## 6. Pull Image from DockerHub
```bash
docker pull your-dockerhub-username/myapp:1.0
```

## 7. Run Container After Pulling
```bash
docker run -d -p 8080:8080 your-dockerhub-username/myapp:1.0
