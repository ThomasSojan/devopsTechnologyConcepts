## Popular tools 

Tools include-

* Artifactory

* Nexus 

## Benefits of using an artifact repository 

* The right version of the build is used for QA and the completely tested version goes for release

* Ensures that any changes to source code to meet the quality and testing needs are routed only through the source code repository

* Structures the deployment properly

## Practical tips

* It is important to have multiple repositories for release, dev/test snapshots thereby supporting multiple teams if they are aligned as Dev, Test teams (for example) and provide appropriate permissions(CRUD – Create, read, update and delete)


* In case of shared repositories for multiple projects, there might be one release and snapshot repositories. But based on the usage, each of the project teams would have permissions and a direct path through which their components are baselined


* A good practice is to use as few hosted repositories as possible and control the permissions by using repository targets.
