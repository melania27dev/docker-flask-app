# Flask Docker App

## A small project: a Flask application containerized with Docker
## When you run the application, you will see a simple message: "Main Page"

### Structure
- 'app.py' - the Flask application
- 'requirements.txt' - the required dependencies
- 'Dockerfile' - Configuration

### How to build the image
docker build -t <image_name> .

### How to run the container
docker run -p 5000:5000 <image_name>

### Future ideas for improvements
- add more Flask routes
- create a 'docker-compose.yml'