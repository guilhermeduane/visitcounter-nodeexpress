# Node Express Page Visits Counter with Docker Compose

This project demonstrates a simple page visit counter built using Node.js and Express, containerized using Docker and orchestrated with Docker Compose. Every time you visit the page, the visit count increments and is displayed on the page.

## Features

- **Node.js and Express**: Backend server to handle HTTP requests and serve the visit count.
- **Docker**: Containerize the application for easy deployment.
- **Docker Compose**: Simplifies multi-container Docker applications, in this case, for orchestrating the app and any required services (e.g., database, cache).

## Prerequisites

To run this project, you need the following installed:

- **Docker**: [Install Docker](https://www.docker.com/get-started)

## Getting Started

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/node-express-page-visits-counter.git
   cd node-express-page-visits-counter

2. **Run Docker Compose command to build and run:**

   ```bash
   docker-compose up --build
   
