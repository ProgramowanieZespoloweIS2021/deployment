# deployment
Repository with deployment infrastructure (Kubernetes).


## Running containers locally using docker-compose
Run the following command:
```
docker-compose up -d
```
and wait for about 20 seconds. To access services from the host, use following ports with `localhost`:
 - `8080` for offers service
 - `8081` for orders service
 - `8082` for cart service
 - `8083` for users service
 - `8084` for authentication service
