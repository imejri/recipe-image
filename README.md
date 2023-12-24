# recipe-image

Application for a Recipe website -> finds other recipes with similar rare ingredients


Git clone 

Cd files

podman build --tag python-podman . 

podman run --publish 5000:5000 python-podman

(outside container): (inside container)

http://127.0.0.1:5000

- Aine Keenan

Python has emerged as a go-to language for students, new programmers, and experienced developers. This general-purpose programming language is dynamically typed, memory-managed, and supports multiple programming paradigms. Python is popular for web development, data science, artificial intelligence and machine learning (AI/ML), scripting for Linux, and more.

Containers are a game-changing solution for packaging your code and dependencies, allowing for your application to run quickly and consistently across any environment. Using containers to support your Python application enables efficient development and deployment.

This article shows how to use containers to support your Python applications. We'll take a pre-configured application and build a Containerfile for it from scratch. Additionally, we will walk through the importance and implementation of each part.

Container parts
A container will include everything your application needs to run on any machine. The main elements (illustrated in Figure 1) include a base image or platform operating system that you want the system calls to virtualize. You also need your application code. Finally, you need all dependencies, like specific versions of programming language runtimes and libraries your code needs to run.

Link to the Red Hat Tuto: https://developers.redhat.com/articles/2023/09/05/beginners-guide-python-containers#
