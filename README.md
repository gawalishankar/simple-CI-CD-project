🚀 Simple CI/CD Project with GitHub Actions

This repository demonstrates a straightforward Continuous Integration and Continuous Deployment (CI/CD) pipeline for a Node.js application using GitHub Actions and Docker.

🧩 Architecture Overview

Frontend: Node.js application in the app.js file.

Docker: Dockerfile to containerize the application.

CI/CD: GitHub Actions workflows in .github/workflows.

✨ Features

✅ Automated build and test with GitHub Actions.

🐳 Containerization for consistent environments.

🚀 Continuous deployment to a specified environment.

⚙️ Prerequisites

Docker installed 🐳

GitHub repository with secrets configured for Docker registry 🔐

🛠 Setup Instructions
1️⃣ Clone the Repository
git clone https://github.com/gawalishankar/simple-CI-CD-project.git
cd simple-CI-CD-project

2️⃣ Build Docker Image
docker build -t my-node-app .

3️⃣ Run Docker Container
docker run -p 8080:8080 my-node-app

4️⃣ Access Application

Open your browser and navigate to http://localhost:8080 to view the application.

🔄 GitHub Actions Workflow

The .github/workflows directory contains the CI/CD workflow configuration. Ensure that your GitHub repository has the necessary secrets configured for Docker registry authentication.

📄 License

MIT License
