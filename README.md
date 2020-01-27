# Deploying an API with Flask, Nginx and Docker

First you need to install docker and docker-compose.

### Running the API

You can then run the API

```bash
docker-compose up --build
```

### Calling the API

```
http://localhost:5002
```
Output: Hello World!

Passing parameters
```
http://localhost:5002/add?input1=1&input2=2
```
Output: {"append":"12","sum":3.0}