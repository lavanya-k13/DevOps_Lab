# DevOps_Lab
# Experiment No. 1 - Simple User Registration Form

## Aim
Write code for a simple user registration form for an event.

## Software / Tools Required

| S.No | Software / Tool | Purpose |
|------|----------------|---------|
| 1 | Python 3.8 | Programming language used for Flask development |
| 2 | Flask 1.1.2 | Web Framework for developing the registration form |
| 3 | Docker | Containerization and deployment of the application |
| 4 | Web Browser (Chrome/Firefox) | To access and test the registration form |
| 5 | Text Editor / IDE (VS Code) | To write and manage source code |

## Installation Steps

1. Install Python 3.8 from https://www.python.org/downloads/
2. Install Flask using: pip install Flask==1.1.2
3. Install Docker from https://www.docker.com/products/docker-desktop
4. Install VS Code from https://code.visualstudio.com/

## Description
This experiment demonstrates how to build a simple user 
registration form using Flask and deploy it in a Docker container.

## Project Structure
Lab-Exp-1/
├── app.py
├── requirements.txt
├── Dockerfile
└── templates/
    ├── register.html
    └── success.html

## Steps to Run

### Build Docker Image
docker build -t simple-flask1-app .

### Run Docker Container
docker run -p 5000:5000 simple-flask1-app

### Access the Application
Open browser and go to: http://localhost:5000/register
