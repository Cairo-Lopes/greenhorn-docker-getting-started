# greenhorn-docker-getting-started
🚀 Beginner-friendly Docker guides! Dive into containerization basics with step-by-step instructions. Start your Docker journey here! 🐳💻 #Docker #GettingStarted #Greenhorn

**references:** 
* This repository is built upon a Medium article that greatly assisted me in its creation. For more detailed information, please visit the following link:[How Docker Can Help You Become A More Effective Data Scientist](https://towardsdatascience.com/how-docker-can-help-you-become-a-more-effective-data-scientist-7fc048ef91d5 )
* [Dockerfile reference](https://docs.docker.com/engine/reference)
# Why Docker?
## Dockerfile
### Break It Down:
#### FROM

In a Dockerfile, the `FROM` instruction is used to specify the base image that will be used to build the new image. The base image is the `starting point` for constructing the Docker image and contains the operating system and other necessary components.
```docker
 FROM base:${CODE_VERSION}
```
   



