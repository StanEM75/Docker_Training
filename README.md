# Docker_Training

This is my first project on Docker. I created a basic application and put it into a Docker Image.
Then, I ran a container.

---

## 📑 Content
- app.py: An application using FastAPI and that returns simple sentences.
- requirements.txt: List of required dependencies for the application to run effectively.
- .dockerignore: Files to be ignored.
  
- main.py: Part of uv local virtual environment (can be ignored for Docker).
- pyproject.toml: Part of uv local virtual environment (can be ignored for Docker).

## 📘 Use Dockerfile to create the Docker Image

File: `Dockerfile`

Create this file in Docker sandbox. --> https://www.docker.com/play-with-docker/

## 🖼️ Build the Docker Image

Run `docker build -t docker_training:1.0`

- 🖼️ build tells Docker to create the image.
- 📤 -t is for applying a tag.
- 📂 `docker_training` is the name of the repository containing all the files we want to run.
- 📄 1.0 is the tag (here we want to say this image is the version 1).

## 🪧 Run a container based on this Docker Image

Run `docker run -d -p 8000:8000 docker_training:1.0`

- 🔂 -d tells Docker to run the container in the background to avoid printing all the logs while running.
- 🛳️ -p precises the port of the local device to connect to, as well as the Docker port for the app. The two are 8000.
- 📂 `docker_training` is the name of the image containing all the files we want to run.
- 📄 1.0 is the tag (here we want to say this image is the version 1).


