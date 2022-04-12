## Containerization using Docker
Docker is a tool designed to make it easier to create, deploy, and run applications by using containers. Containers allow a developer to package up an application with all of the parts it needs, such as libraries and other dependencies, and ship it all out as one package.  Docker containers wrap up software and its dependencies into a standardized unit for software development that includes everything it needs to run: code, runtime, system tools and libraries. This guarantees that your application will always run the same and makes collaboration as simple as sharing a container image.

## Best practices

* Security and governance is of utmost importance when containers are used for production deployments. A minimalist OS which is hardened and patched should be used as the host OS and monitoring needs to be done continuously on security vulnerabilities.

* The container must contain continuous monitoring tools to provide visualization and analytics

* Containers are transitory and hence data should be made persistent and protected after the association with the container is over

* Containers present a potential situation where many virtual machines are spawned and lying unused. A proper container lifecycle management should be put in place in association with the CICD pipeline

## The benefits are as follows:

* Instant startup of operating system resources

* Container Environments can be replicated, template-ized and validated for production deployments.

* Greater performance with security

## Popular tools 

* Docker

* Kubernetes

* Apache Mesos

* Microsoft containers
