# 🪲 BuggyBuddy

BuggyBuddy is an end-to-end data science project aimed at performing similarity search through a bug report database to assist users in identifying duplicate bug reports. This facilitates faster problem resolution in software development.

## 1. Data Analysis and Model Exploration

### a. BuggyBuddy-Notebook
This section contains in-depth data analysis and model  involving NLP techniques such as Embedding, Deep Learning, and Semantic Search.

## 2. Production Microservices

### a. BuggyBuddy-ETL-Microservice
An ETL microservice built for seamless ETL pipeline, responsible for extracting, transforming, and loading bug report data.

### b. BuggyBuddy-Model-Builder-Microservice
A Model Builder microservice designed to automatically create, train, evaluate, and save new models when new data is available.

### c. BuggyBuddy-RESTful-API-Microservice
A RESTful API application for the BuggyBuddy project developed using FastAPI. This microservice serves as the interface for users to interact with the system and perform similarity search on bug reports.

These microservices communicate with each other using the RabbitMQ message broker, facilitating seamless integration and data flow within the BuggyBuddy project.