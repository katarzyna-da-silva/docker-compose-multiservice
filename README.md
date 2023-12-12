# docker-compose-multiservice

image for writefreely, wikijs, wordpress, on various databases

***DOCUMENTATION***

***https://docs.docker.com/compose/***


# Multiservice Docker Compose Project

This repository demonstrates the usage of Docker Compose to run multiple services. In this setup, we have included WordPress, Wiki.js, WriteFreely, PostgreSQL, MySQL, and MongoDB.

## Usage Guide

Make sure you have the following installed on your machine:

- [Docker](https://docs.docker.com/get-docker/)
- [Docker Compose](https://docs.docker.com/compose/install/)

### Getting Started

1. **Clone the Repository:**

    ```
    git clone https://github.com/your-username/your-repo.git
    ```

2. **Navigate to the Project Directory:**

    ```
    cd your-repo
    ```

3. **Run Docker Compose:**

    ```
    docker-compose up
    ```

   This command will download the necessary images and start the containers in the background.

4. **Access the Services:**

   - WordPress: [http://localhost:8080](http://localhost:8080)
   - Wiki.js: [http://localhost:8081](http://localhost:8081)
   - WriteFreely: [http://localhost:8082](http://localhost:8082)

### Notes

- Services like PostgreSQL, MySQL,have default credentials set in the `docker-compose.yml` file. Consider changing them for production use.
- The `docker-compose.yml` file includes volume definitions for data persistence.




