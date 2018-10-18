---
title: Docker Image
---

## What is Docker Image?

A Docker Image is a combination of all the system files and parameters which are required for the any specific application. An image holds required resources and settigs for the execution of application.
So, In Docker everything is based on the Images. Now, Let's take a simple and most time first example i.e. "Hello World".
There is a image for that "Hello World". We just need to run that image and will get the output.

Here's the command to run a image `docker run hello-world`. `hello-world` is the image name for that "Hello World" simple application.

Let's go little in details; `docker` commands are specific tells Docker what need to be done and `run` use to tell docker we need to create an instace for the image which is called as `container`.

After that, the instance or container created and been executed and return the output "Hello World".

### To check the images

To check what are the images you have in your docker. There is aimple command for that `docker images` list out all the images you have in your docker.

And here for the given above example, when you will the run the command `docker run hello-world` it will check if you have that image in your docker or not. If it will run the same if not it will download the image from `Docker Hub` if available then run the image.

#### More Information:
- [Docker CLI docs: image](https://docs.docker.com/engine/reference/commandline/image/)
