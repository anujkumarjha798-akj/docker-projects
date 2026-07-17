# Simple Java Docker Application

A beginner-friendly Docker project that demonstrates how to containerize a simple Java application using a Dockerfile. This project is part of my Docker learning journey and focuses on understanding the fundamentals of building and running Java applications inside Docker containers.

---

## 📌 Project Overview

This project contains a basic Java program that prints a message to the console. The application is packaged into a Docker image and executed inside a Docker container.

It demonstrates:

- Writing a basic Dockerfile
- Building a Docker image
- Running a Java application inside a container
- Understanding Docker image creation and container execution

---

## 📂 Project Structure

```text
simple-java-docker/
├── Dockerfile
├── README.md
└── src
    └── Main.java
```

---

## 🛠️ Technologies Used

- Java
- Docker
- Linux (Zorin OS)

---

## 📄 Dockerfile

The Dockerfile performs the following tasks:

1. Uses an OpenJDK base image.
2. Copies the Java source code into the container.
3. Compiles the Java program.
4. Executes the compiled Java application.

---

## 🚀 Build Docker Image

```bash
docker build -t simple-java-app .
```

---

## ▶️ Run Docker Container

```bash
docker run --rm simple-java-app
```

---

## ✅ Expected Output

```text
Hello, Docker!
```

*(Replace this output if your Java program prints something different.)*

---

## 🎯 Learning Objectives

- Understand Docker Images
- Understand Docker Containers
- Learn Dockerfile instructions
- Build custom Docker images
- Execute Java applications inside containers

---

## 📚 Future Improvements

- Add Maven support
- Create a multi-stage Docker build
- Reduce image size
- Push Docker image to Docker Hub
- Integrate with GitHub Actions for CI/CD

---

## 👨‍💻 Author

**Anuj Kumar Jha**

Aspiring DevOps Engineer | Docker | Linux | Bash Scripting | Git & GitHub

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.
