# Dream Vacation Destinations

This application allows users to create a list of countries they'd like to visit, providing basic information about each country. The project is structured to mimic a real-life production environment, employing best practices in software development, deployment, and continuous integration/continuous delivery (CI/CD).

## Setup

### Backend
1. Navigate to the `backend` directory.
2. Run `npm install` to install dependencies.
3. Set up your PostgreSQL database and update the `.env` file with your database URL.
4. Run `npm start` to start the server.

### Frontend
1. Navigate to the `frontend` directory.
2. Run `npm install` to install dependencies.
3. Update the `.env` file with your API URL (e.g., `REACT_APP_API_URL=http://localhost:3001`).
4. Run `npm start` to start the React development server.

## Features
- **Add Countries**: Users can add countries to their dream vacation list.
- **View Country Details**: Displays capital, population, and region information for each country.
- **Remove Countries**: Users can remove countries from their list.
- **Production-Ready Setup**: The project is designed to be scalable and maintainable, following industry-standard practices for deployment and CI/CD.

## Roadmap
- **CI/CD Implementation**: Automate the build, test, and deployment process using industry-standard CI/CD tools.
- **Infrastructure as Code (IaC)**: Implement IaC for automated environment setup and management.
- **Scalability**: Enhance the application to support multiple environments (staging, production) with proper domain names and configurations.
- **Security**: Utilize Kubernetes Secrets and environment variables for secure data management.
- **Microservices**: Modularize the application into microservices to improve maintainability and scalability.

## Technologies Used
- **Frontend**: React
- **Backend**: Node.js with Express
- **Database**: PostgreSQL
- **External API**: REST Countries API
- **CI/CD**: To be implemented with [CI/CD tools, e.g., GitHub Actions, Jenkins, or Azure DevOps]
- **Infrastructure as Code**: To be implemented with tools like Terraform or Helm

## Best Practices
- **Version Control**: All changes are tracked in Git for collaboration and history management.
- **Environment Management**: Separate configurations for different environments (development, staging, production) using environment variables.
- **Security**: Sensitive information is managed using environment variables and Kubernetes Secrets.
- **Documentation**: The project is well-documented to facilitate onboarding and maintenance.



# Dream Vacation App - Dockerized Deployment

## Overview

This project containerizes the Dream Vacation App using Docker and Docker Compose.

The application includes:

* React Frontend
* Node.js Backend
* PostgreSQL Database

All services run in isolated containers and communicate internally using Docker networking.

---

# Technologies Used
* Docker
* Docker Compose
* React
* Node.js
* PostgreSQL
* Nginx

---

# Project Structure
dream-vacation-app/
│
├── frontend/
├── backend/
├── docker-compose.yml
├── .env
└── README.md


# Setup 

## 1. Clone Repository

Fork Repository
git clone <my-github-repo-link>
cd dream-vacation-app

## 2. Start the Application
docker-compose up 

# Application URLs

Frontend:
http://localhost:80

Backend:
http://localhost:5000
PostgreSQL:

```bash
localhost:5432
```

---

# Docker Features Implemented

## Frontend

* Multi-stage Docker build
* Optimized production image
* Nginx used for serving static files

## Backend

* Node.js containerized API service
* Environment variables loaded via `.env`

## Database

* PostgreSQL container
* Persistent storage using Docker volumes

## Build Containers

```bash
docker-compose build
```

## Start Containers

```bash
docker-compose up


## Backend
<img width="1076" height="387" alt="image" src="https://github.com/user-attachments/assets/90741dbc-e167-4046-87b6-e8a8996903d9" />

## Frontend
<img width="1086" height="892" alt="image" src="https://github.com/user-attachments/assets/0ae3e5de-812f-4d26-b4ae-d0249b70c69b" />
<img width="1076" height="886" alt="image" src="https://github.com/user-attachments/assets/8c111d09-2629-44d6-884c-c050fba12431" />



```





Backend dockerfile
<img width="1090" height="387" alt="image" src="https://github.com/user-attachments/assets/fedc3d94-0895-4078-af0b-62db36b4b12e" />

<img width="1077" height="567" alt="image" src="https://github.com/user-attachments/assets/0c43364a-3239-453c-9fd9-0a7d9448b6af" />

Frontend dockerfile
<img width="1071" height="646" alt="image" src="https://github.com/user-attachments/assets/a245b47f-9f2d-4ec0-ac5f-11de96099d6f" />

Docker-compose.yml
<img width="1087" height="892" alt="image" src="https://github.com/user-attachments/assets/647c11ca-cd0e-4e68-89c4-3fbcd5b1758f" />
<img width="1067" height="416" alt="image" src="https://github.com/user-attachments/assets/4f526dc0-eb0f-4778-ab40-34a487de45ca" />


##output
<img width="1121" height="946" alt="image" src="https://github.com/user-attachments/assets/c681828d-e0e9-4279-b571-02ea87ee9deb" />
<img width="1566" height="510" alt="image" src="https://github.com/user-attachments/assets/2c2f6329-2709-4fe8-bbf1-a17ad869c5d8" />












