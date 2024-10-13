## Expass 7

### Using a Dockerized application: PostgreSQL
Now my tests can run with a PostgreSQL database instead of an H2 database. 
![ex7](assets/ex7Q1.png)

### Building you own dockerized application
The dockerfile used to build the container:
![ex7](assets/ex7Q2.png)

The docker container is built with the following command:
- `docker build -t image`

The container is then run with the following command:
- `docker run -d -p 8080:8080 --name myapp-container image`