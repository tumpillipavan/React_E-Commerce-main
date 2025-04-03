# Running the Project with Docker

To run this project using Docker, follow the steps below:

## Prerequisites

Ensure you have Docker and Docker Compose installed on your system. Refer to the [Docker installation guide](https://docs.docker.com/get-docker/) for assistance.

## Build and Run the Application

1. Clone the repository and navigate to the project directory:

   ```bash
   git clone https://github.com/ssahibsingh/React_E-Commerce
   cd React_E-Commerce
   ```

2. Build and start the application using Docker Compose:

   ```bash
   docker-compose up --build
   ```

3. Access the application in your web browser at `http://localhost:3000`.

## Configuration

- The application runs on Node.js version `22.13.1-slim` as specified in the Dockerfile.
- The application exposes port `3000` for HTTP traffic.
- Modify the `docker-compose.yml` file to adjust configurations as needed.

## Notes

- Ensure no other services are using port `3000` on your host machine to avoid conflicts.
- For production deployment, consider using a reverse proxy and secure the application with HTTPS.

For further assistance, refer to the [Docker documentation](https://docs.docker.com/).