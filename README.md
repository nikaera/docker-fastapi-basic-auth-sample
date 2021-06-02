# docker-fastapi-basic-auth-sample

Docker Compose sample project with BASIC authentication for FastAPI docs path in nginx.

## Getting Started 💨

After launching the container with Docker Compose, access `http://localhost:80/docs` and make sure BASIC authentication is enabled. In this case, set `$USER` and `$PASS` in the environment variables to [set the information for BASIC authentication](https://github.com/nikaera/docker-fastapi-basic-auth-sample/blob/main/docker-compose.yml#L14-L15).

```bash
docker-compose up --abort-on-container-exit

# clean up after docker-compose
docker-compose down --rmi all --volumes --remove-orphans
```
