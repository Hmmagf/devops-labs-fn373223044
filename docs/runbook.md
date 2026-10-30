## Run with Compose

- **`docker compose up -d`**: Builds and starts all services in the background.
- **`docker compose ps`**: Lists the status of running containers and their exposed ports.
- **`docker compose logs -f`**: Streams live logs from the services for debugging.
- **`docker compose down`**: Stops and removes the containers and networks while keeping volumes (data persists).
- **`docker compose down -v`**: Stops and removes containers, networks, **and** deletes the data volumes (full cleanup, data is lost).