# Continuous Integration and Continuous Delivery
![CICD](https://github.com/ThomasSojan/devopsTechnologyConcepts/blob/main/DevOps%20Professional/DevOps%20CICD/1.Technical%20Practices/CD.png)

The development team commits the source code and automated test cases to the version control system. The continuous integration tool is scheduled to run at a specific frequency (best practice is to run daily).It polls the version control system (specific repository where the code is committed) for changes and triggers the various tools which can be used to automate the build cycle activities. The CI moves to next stage only if the previous stage meets the gating conditions set. These are explained below:

  1.The CI tool invokes the static code analysis tool. This checks the quality of code against the set rules.

2.The CI tool then invokes the automated unit test cases. Only if they pass or as per the gating criteria set, the next stage is invoked.

3.In order to check if the unit test cases cover the code, the code coverage tool is invoked next by the CI tool. 

4.The CI tool then invokes the build script for building the executable file. At the end of the integration, the binary file is baselined into a binary repository.

5.The continuous integration tool may trigger the environment provisioning tool which provides provisions and configures the test environments (functional, performance testing etc).

6.The CI tool then triggers deployment automation tool to deploy the application into the provisioned environment and executes the automated QA test cases and if the gating conditions are met for the execution of the tests moves to the next stage.

7.The CI tool then invokes tools to provision the pre-production deployment environment.The deployment tool deploys the working version of the software to the pre-prod environment configured and runs all the automated acceptance tests.

8.If the acceptance tests pass, steps 7 and 8 are repeated for production environment and the software is deployed automatically after going through release management process.

9.The workflow and approval mechanisms are configured using and in release management tools. The changes done get reflected in production environment i.e. release to production.
