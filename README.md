# DevOps_Lab
# Experiment No. 1 - Simple User Registration Form

## Aim
Write code for a simple user registration form for an event.

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
