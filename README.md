# Camunda BPM EE Docker image

## Folder Structure
Folder/File | Description
---|---
./camunda-ee-postgresql | Docker image for PostreSQL incl. Camunda tables
./camunda-cockpit | Docker image for Camunda BPM EE Wildfly distro primarily for accessing Tasklist and Cockpit
docker-compose.yml | Docker composition that wires all services together

## Running

- Build and run all Docker images using `docker-compose up -d --build`
- View the logs using `docker-compose logs -f`
- Show down all containers and delete all volumes using `docker-compose down -v`

## URLs
- [Camunda Cockpit](http://localhost:8080/camunda/app/cockpit/default/) (username: demo, password: demo)
- [Docker Compose UI](http://localhost:5000/)