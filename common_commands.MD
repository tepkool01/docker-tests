- docker ps --all
- docker run -it CONTAINER_ID sh
- docker logs CONTAINER_ID
- docker exec -it CONTAINER_ID sh
- docker build -t tepkool01/somename:latest .
- docker build -f Dockerfile.dev .
- docker stop CONTAINER_ID
- docker kill CONTAINER_ID
- docker system prune
- docker run -p 8080:8080 IMAGE_ID (sometimes need to add -it flag)
- docker run -d CONTAINER_ID (runs in background)
- docker run -it -p 3000:3000 -v /app/node_modules -v ${pwd}:/app CONTAINER_ID (MUST BE IN POWERSHELL)

## docker-compose
- docker-compose up (add -d flag to run in background)
- docker-compose up --build (rebuilds)
- docker-compose down