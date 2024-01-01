# K8s for web application
This repo covers using K8s in creating a kubernetes cluster for an application.
The application has the following:

- A frontend web app based on ReactJS
- An API server based on SpringBoot Framework
- A python API based on flask

## Description
The application allows users to submit a sentiment and it displays whether it is positive or negative. The frontend web app provides an interface for users to enter the text, then sends it to the API server(SpringBoot) which intend sends it to the AI agent(Flask API) for analysis