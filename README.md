# intro-microservices

In this tutorial, we built two different microservices that communicate with each other using REST. We also used Docker to containerize the services and Docker Compose to run them together.

## Prerequisites

- [Docker](https://docs.docker.com/get-docker/)
- [Docker Compose](https://docs.docker.com/compose/install/)
- [Python 3.8](https://www.python.org/downloads/)
- [Visual Studio Code](https://code.visualstudio.com/download)

## Running the services

To run the services, run the following command:

``` bash
docker-compose build 
```

```bash
docker-compose up
```

## Testing the services

To test the services, run the following command:

```bash 
curl http://localhost:5000
```

You should see the following response:

```json
{
  "message": "Hello from the other service!"
}
```

## Cleaning up

To stop the services, press `Ctrl+C` in the terminal where you ran `docker-compose up`.

To remove the containers, run the following command:

```bash

docker-compose down

```

## Resources

- [Docker](https://www.docker.com/)
- [Docker Compose](https://docs.docker.com/compose/)


