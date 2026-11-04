
# Enterprise Cloud Infrastructure Architecture

## Project Overview

This project demonstrates an enterprise cloud infrastructure
application built using Python and Flask.

It focuses on core cloud infrastructure concepts such as
application server management, database connectivity,
file storage, access control, and application monitoring.

## Technologies Used

- Python
- Flask
- SQLite
- REST API
- AWS Architecture Concepts
- Git and GitHub

## Project Architecture

The proposed cloud architecture includes:

- Application Load Balancer
- Amazon EC2 for application hosting
- Amazon RDS for database management
- Amazon S3 for cloud storage
- Amazon VPC for network isolation
- IAM for identity and access management
- Security Groups for network security

Note: The current implementation runs locally.
AWS services are part of the proposed deployment architecture.

## Features

1. Application health monitoring
2. Employee data management
3. REST API development
4. API key-based access control
5. File upload functionality
6. Application metrics

## Project Structure

enterprise-cloud-infrastructure/
|
|-- app.py
|-- requirements.txt
|-- README.md
|-- .gitignore
|-- cloud_storage/

## Installation and Setup

### 1. Clone the repository

git clone https://github.com/YOUR_USERNAME/enterprise-cloud-infrastructure.git

### 2. Navigate to the project

cd enterprise-cloud-infrastructure

### 3. Create a virtual environment

python -m venv venv

### 4. Activate the environment

Windows:
venv\Scripts\activate

### 5. Install dependencies

pip install -r requirements.txt

### 6. Run the application

python app.py

Application URL:
http://127.0.0.1:5000

## API Endpoints

| Endpoint | Method | Description |
|----------|--------|-------------|
| /health | GET | Application health |
| /employees | POST | Add employee |
| /employees | GET | Retrieve employees |
| /upload | POST | Upload files |
| /metrics | GET | Application metrics |

Protected APIs require the X-API-Key header.

## Future Enhancements

- AWS EC2 deployment
- Amazon S3 integration
- Amazon RDS integration
- Docker containerization
- Application Load Balancer
- Auto Scaling
- CloudWatch monitoring

## Author

Kiranmai Sampangi
