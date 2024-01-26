# This project is based on the work of Bret Fisher (https://github.com/BretFisher).

## Project Modifications

This project has been modified to include my learning process that based on the online course of Bret Fisher which I attended.

# Instructions for Assignment

[Build Your Own Dockerfile and Run Containers From It](https://www.udemy.com/course/docker-mastery/learn/lecture/6806638)

# Bind Mounting Demo

This repository demonstrates a simple Docker bind mounting scenario using two containers and a text file.
Bind mounting allows sharing files between the host machine and Docker containers in real-time.

## Contents

1. [Prerequisites](#prerequisites)
2. [Repository Structure](#repository-structure)
3. [Instructions](#instructions)
4. [Details](#details)

## Prerequisites

Make sure you have Docker installed on your machine. If not, you can download it [here](https://www.docker.com/get-started).

## Repository Structure

- `dockerfile-sample-2/`: Directory containing Dockerfile and demo files.
  - `Dockerfile`: Dockerfile for the Nginx container.
  - `index.html`: Sample HTML file served by Nginx.
  - `tests.txt`: Text file used in the bind mounting demo.

## Details

- The Nginx container is configured to serve files from `/usr/share/nginx/html`.
- The text file `tests.txt` is bind-mounted from the host machine to the Nginx container, allowing real-time updates.

Feel free to explore and modify the files in the `dockerfile-sample-2` directory to experiment with different scenarios using bind mounting.

Happy coding!
