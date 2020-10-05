## Simple server.

### Tools required
- Docker
- GO installation
- Your IDE

### Running the application locally
- Change directory to project directory

- Build docker image with :
 `docker build -t simple-server:latest .`
- Run the image  with :
  `docker run -p 8080:8080 simple-server:latest`
- The application should be accessible on http://localhost:8080. 



