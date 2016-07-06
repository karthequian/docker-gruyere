#Intro

This project is a Dockerfile that builds the [Gruyere project](https://google-gruyere.appspot.com/) into a container that can be run on your local machine without having to install it's dependencies. To run this, you'll need to have Docker installed.

#Usage
You can pull this image from dockerhub using:
```
docker pull karthequian/gruyere:latest
```

You can run this image as follows:
```
docker run -d -p 8008:8008 karthequian/gruyere
```

In your web browser, visit port :8008 on your docker host, and you'll see the gruyere webapp. Happy security testing!
