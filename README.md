# Django Project with Docker

## Docker Commands
run the following command to build the Docker image:
```bash
$ docker build -t my-django-app .
```
Replace my-django-app with the desired name for your Docker image. Once the image is built, you can run it using:
```bash
$ docker run -it -p 8000:8000 my-django-app
```

This will start a new container from the my-django-app image and map port 8000 on the host machine to port 8000 in the container. You can then access your Django app by visiting http://localhost:8000 in your web browser.