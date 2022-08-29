# Docker

**1. What is Docker ?**
Docker is an open platform for developers and sysadmins to build, execute and ship distributed applications.
**2. What is a Docker container ?**
A container is an isolate environnements that allows to run and distribute an application.
**3. What is a Docker image ?**
The application and in its dependencies grouped in a way to put them in a container.
**4. How to create a Docker container ?**
`docker create [options] image`
**5. How to list Docker containers ?**
`docker ps`
**6. What is the difference between `docker --version` and `docker version` ?**
- `docker --version` gives the version of the cli tool.
- `docker version` gives the informations for the client and the server, like the architecture and the OS. 
**7. How do we limit the cpu usage of a Docker container ?**
In the `dockerfile`, with the various --cpus options.
**8. What is Docker Hub ?**
**9. How do we configure a Docker container ?**
With a `dockerfile`, a yaml file that contains the various options needed.
**10. What is PaaS ?**
Platform As A Service.

The client pay for access to a platform instead of a specific application.