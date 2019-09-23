# practice-angular-material

## Docker
### Build and Run
###### Build and Run the docker image with the Docker Compose file
```
 docker-compose -f docker-compose-local.yml up --build
```

### Stop
###### Stop the docker container with the Docker Compose file
```
docker-compose -f docker-compose-local.yml stop
```

### Browse to the app
http://localhost:4201/

### Open a shell in the container
```
docker exec -it practice-angular-material bash
```

### Angular CLI
###### Create a new component, service, or other
The [Angular CLI](https://angular.io/cli/generate) is the recommended way to create a new component, service, guard, or other type of file automatically. Open a shell in the client container to run Angular CLI commands.

###### Component
```
ng generate component components/records/table/records-table
```

###### Service
```
ng generate service services/records/record-form
```
