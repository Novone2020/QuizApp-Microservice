# Quiz Application Microservices

This repository contains the microservices architecture for a Quiz Application. Each service is contained within its own folder and has its own dependencies and configurations.

# Previous Version

This project is the microservices version of a previous monolithic application I developed. You can check out the monolithic version here.

```bash
git clone https://github.com/ShubhamSukum/SpringBoot_QuizApp.git
```

## Services

- **API Gateway**: The entry point to our application that routes requests to the appropriate microservice.
- **Question Service**: Handles all operations related to quiz questions including creation, update, deletion, and retrieval.
- **Quiz Service**: Manages quizzes, including creating quizzes, adding questions to quizzes, and managing quiz sessions.
- **Service Registry**: Keeps track of the addresses of all service instances that are registered.
