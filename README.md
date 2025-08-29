# Docker_Training

This is my first project on Docker. I created a basic application and put it into a Docker Image.
Then, I ran a container.

---

## 📑 Content
- app.py: An application using FastAPI and that returns simple sentences.
- requirements.txt: List of required dependencies for the application to run effectively.
- .dockerignore: Files to be ignored.
  
- main.py: Part of uv local virtual environment (can be ignored for Docker).
- pryproject.toml: Part of uv local virtual environment (can be ignored for Docker).

## 📘 Use DOCKERFILE to create the Docker Image

Notebook: `Create_Variables.ipynb`

I've created a notebook called `Create_Variables` where I just practiced some basic Python concepts, among which there are:
- ✅ Variables and typing  
- 🔁 Loops and conditions  
- 🧩 Functions  
- 📚 Lists and dictionaries

## 🗂️ Part 2: Structure a data project

Folder: `mon_projet_ia`

I've created a folder called `mon_projet_ia` where I just checked how to organize a data project, with useful subfolders:
- 📊 data: Contains raw and processed data --> 1 raw_data.csv containing random values and 1 processed_data.csv containing processed data of raw_data.csv
- 📤 models: Contains results of models trainings --> Nothing here
- 📄 notebooks: Contains notebooks for exploration --> Copy of `Create_Variables.ipynb`
- 📚 src: Contains data preparation files, model trainings and reusable functions
- ➡️ tests: Contains tests to be applied --> Here 1 test to calculate the area of a circle

## 🪧 Part 3: Add unit tests

Subfolder: `mon_projet_ia/tests`

I've created a subfolder called `tests` in `mon_projet_ia` where I just implemented some unit tests related to mathematical functions stored in `mon_projet_ia/src/utils/maths_utils.py`.
