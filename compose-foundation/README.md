
# Docker Compose Multi-Container Lab

## Overview

This project demonstrates how to build and manage a multi-container application using Docker Compose.

The stack includes:

* **Nginx** – Web server
* **PostgreSQL** – Relational database
* **Redis** – In-memory cache
* **Docker Volume** – Persistent database storage
* **Environment Variables** – Configuration using a `.env` file

## Project Structure

```text
compose-lab/
├── compose.yaml
├── .env
└── README.md
```

## Services

| Service    | Purpose                         |
| ---------- | ------------------------------- |
| Nginx      | Serves web traffic              |
| PostgreSQL | Stores application data         |
| Redis      | Provides fast in-memory caching |

## Features

* Multi-container application
* Automatic Docker network creation
* Persistent PostgreSQL storage using Docker volumes
* Environment variable configuration
* One-command deployment with Docker Compose

## Run the Project

```bash
docker-compose up -d
```

## Stop the Project

```bash
docker-compose down
```

## Skills Demonstrated

* Docker
* Docker Compose
* Container Networking
* Persistent Volumes
* Environment Variables
