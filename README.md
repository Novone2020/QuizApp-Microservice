# Quiz Application Microservices

This repository contains the microservices architecture for a Quiz Application. Each service is contained within its own folder and has its own dependencies and configurations.

## Services

- **API Gateway**: The entry point to our application that routes requests to the appropriate microservice.
- **Question Service**: Handles all operations related to quiz questions including creation, update, deletion, and retrieval.
- **Quiz Service**: Manages quizzes, including creating quizzes, adding questions to quizzes, and managing quiz sessions.
- **Service Registry**: Keeps track of the addresses of all service instances that are registered.
