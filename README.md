# simpleDockerPythonApp

This project demonstrates the containerization of a simple Python application using Docker.

## App Architecture

### Creating Docker Image from Scratch

1. **app.py**: 

2. **Dockerfile**:

### Building the Docker Image

To build the Docker image, run the following command in your terminal: `docker build -t my-python-app .` 


- `-t` (or `--tag`) assigns a name to the image.
- `.` specifies the build context, which is the current directory where your Dockerfile is located.

### Running the Docker Container

Once the image is built, you can run the container using: `docker run my-python-app`


This command will execute your Python application inside the container, and you should see the output:


## Conclusion

This project serves as a basic example of how to create and run a Dockerized Python application. You can expand upon this by adding more features or dependencies as needed.