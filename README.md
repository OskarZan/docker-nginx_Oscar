# Docker Nginx - Oscar

A simple Docker project that runs an Nginx web server.

## Description

This project demonstrates how to containerize and run an Nginx web server using Docker. It serves a simple static website.

## Getting Started

### Prerequisites

- Docker installed on your machine
- Git (for version control)

### Installation and Running

1. Clone the repository:
   ```
   git clone https://github.com/OskarZan/docker-nginx_Oscar.git
   cd docker-nginx_Oscar
   ```

2. Build the Docker image:
   ```
   docker build -t nginx-oscar .
   ```

3. Run the container:
   ```
   docker run -d -p 8080:80 nginx-oscar
   ```

4. Access the website in your browser at:
   ```
   http://localhost:8080
   ```

## License

This project is open source and available for learning and educational purposes.

## Author

Oscar

