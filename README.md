# Filehub
Filehub is online file conversion system made using flask and setup on aws with the help of jenkins for deployment and docker for buliding a containerized environment
Here's how the components interact in the file conversion system:
- Users interact with the Flask web application to upload files and initiate the conversion process.
- Flask receives the file uploads, manages the conversion process, and communicates with the Jenkins server for automated testing and deployment.
- Jenkins monitors the code repository for changes, triggers builds, runs tests, and deploys the updated Flask application in a Docker container.
- Docker ensures that the Flask application and its dependencies are isolated and run consistently across different environments.

This setup provides a robust and scalable solution for an online file conversion system, allowing for efficient development, testing, and deployment processes.
