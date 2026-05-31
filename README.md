# Task 1 - CI/CD Pipeline Using GitHub Actions

## Objective
Automate the build, test, and deployment process of a Node.js application using GitHub Actions and Docker.

---

## Tools Used
- GitHub
- GitHub Actions
- Node.js
- Docker
- Docker Hub

---

## Workflow

1. Developer pushes code to `main` branch
2. GitHub Actions pipeline is triggered automatically
3. Install dependencies using npm
4. Run automated tests
5. Build Docker image
6. Login to Docker Hub
7. Push Docker image to Docker Hub

---

## Project Structure

- server.js
- package.json
- package-lock.json
- Dockerfile
- .github/workflows/main.yml

---

## CI/CD Pipeline Flow

GitHub Push  
→ GitHub Actions  
→ Install Dependencies  
→ Run Tests  
→ Build Docker Image  
→ Push Image to Docker Hub  

---

## Outcome

Successfully implemented a full CI/CD pipeline using GitHub Actions that:
- Automatically tests the application
- Builds a Docker image
- Pushes the image to Docker Hub on every push to main branchgit git