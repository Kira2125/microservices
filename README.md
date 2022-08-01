## Microservices


## Initial Configuration
1.	Apache Maven (http://maven.apache.org)  All of the code examples in this book have been compiled with Java version 12.
2.	Git Client (http://git-scm.com)
3.  Docker(https://www.docker.com/products/docker-desktop)


## How To Use

To clone and run this application, you'll need [Git](https://git-scm.com), [Maven](https://maven.apache.org/), [Java 12](https://www.oracle.com/technetwork/java/javase/downloads/jdk12-downloads-5066655.html). From your command line:

```bash
# Clone this repository
$ git clone https://github.com/ihuaylupo/manning-smia

# Go into the repository, by changing to the directory where you have downloaded the 
# Chapter 12 source code and select whether you want the initial or final configuration
$ cd chapter12

# To build the code examples for Chapter 12 as a docker image, open a command-line 
# window and execute the following command:
$ mvn clean package dockerfile:build

# Now we are going to use docker-compose to start the actual image.  To start the docker image, stay in the directory containing  your Chapter 12 source code and  Run the following command: 
$ docker-compose -f docker/docker-compose.yml up
```
