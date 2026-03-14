\# Kitchen Order API – Docker \& Kubernetes Deployment



\## Overview

This project demonstrates a containerized Node.js API deployed using Docker and Kubernetes.



The application allows users to create and view kitchen orders.



\## Architecture



Browser / Client  

↓  

Kubernetes Service  

↓  

API Pod (Node.js)  

↓  

MongoDB Pod  



\## Technologies Used

\- Node.js

\- Docker

\- Docker Compose

\- Kubernetes (Kind)

\- MongoDB

\- GitHub



\## Endpoints



\### Health Check

GET /health



\### Create Order

POST /orders

{

&#x20; "dish": "Dosai"

}



\### List Orders

GET /orders



\## Run Locally



\### Build Docker Image

