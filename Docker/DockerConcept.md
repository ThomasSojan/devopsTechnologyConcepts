# Docker Concepts
## What is Container?
* A way to **package** application with **all** the **necessary dependencies** and **configuration**
*  **Portable artifact**, easily shared and moved around
* Portability and everything packaged in one isolated environment makes development and deployment process **efficient**

## Where do containers leave?
Containers leaves in **container repository**
* Public repository(DockerHub)
* Private repository(for orgnizations)
## Before container
* **Installation process different** on each OS environment
* **Many steps** in deployment can cause something could go wrong (Setting up of new environment is tedious)
* There are chances for getting **dependency conflict**
## After container 
* Application and services are in it's own **isolated environment**
* Packaged with all needed configuration 
* Inside a container there are application,configuration and start scripts
* One command to install the application
* Run same app with 2 different version without conflict
* No **environmental configuration** needed on server

## Container structure
* Containers are in the form of layer of image
* It has a base image mostly **Linux Base Image**
* **Application image** on top of the base image(For ex: postgres,mongodb...)
## Docker Image Vs Docker Container
### Docker Image
* **actual package** which includes application package together with configuration and dependencies
* **artifacts**, that can be moved around
### Docker Container
* Containers are docker image in **running state**
## Docker Vs Virtual Machine

* Docker virtualize application layer of an OS
* VM virtualizes both application layer and kernel of an OS
* Docker containers are small (megabytes) but VMs are large
* Docker containers start and run much fast
* VM can run on any host

 
