# Continuous Integration
A software development practice that requires members of the team to integrate their work **frequently**.
Integration is done at least daily. It leads to multiple integrations each day.

![Continuous Integration](https://github.com/ThomasSojan/devopsTechnologyConcepts/blob/main/DevOps%20Professional/DevOps%20CICD/1.Technical%20Practices/CI.png)

The developers(ex. Dev1 and 2 shown in figure) commit code to a source code repository. Post this the build phase activities of static code analysis, unit testing, code coverage by the unit tests and building the executable file are automated through tools and these steps are called in sequence by the continuous integration server. The executable file is placed in the artifact repository for further testing and release. The continuous integration server is configured to orchestrate frequently to ensure continuous integration of code.<br>
**Additional Info:** https://www.thoughtworks.com/continuous-integration
## Tools:
Jenkins, Bamboo and TFS are examples of continuous integration tools that orchestrate the build and deployment activities which are in turn automated using respective tools
