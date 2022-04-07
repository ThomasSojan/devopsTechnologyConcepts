# Build Automation

## Steps involved:
* Getting the latest version of the program files from Configuration Server

* Compiling the programs

* Performing Static analysis on the programs/code to get feedback on design

* Running automated test (Unit/System test cases)

* Collecting Metrics on Code Coverage of each program during Unit Testing

* Packaging the programs into some form of binaries like .war or .jar or .ear files

* Placing the binary file into a central repository from where the SIT or UAT team can pick up for deployment and testing.

## What is build automation?

A build automation tool helps in the following –

* Compilation of code

* Testing and integrating the changes

* Packaging the binaries

* Deployment to test server

## Popular tools 

Some of the build tools that are widely used in industry are:

* Apache ANT

* Apache Buildr

* Sbt

* Tup

* Gradle

* Visual build

* Apache Maven

* Grunt 

## Maven Lifecycle Phases
* clean - This goal is responsible to clean up ‘target’ folder in eclipse before build process is initiated.

* compile- This goal is responsible to compile all the .java files and create .class files

* sonar:Sonar -This goal is responsible to trigger the Static code analyzer tool ‘SonarQube’ that is responsible to generate the static code metrics

* test- This goal is responsible to run the Junit testcases written and kept in the folder ‘src\test\java\ut….’

* cobertura:cobertura -This goal is responsible to consolidate the outcome of the ‘Test’ goal and generate Code Coverage report and make the same available in ‘\site\cobertura\ folder in eclipse.

* war:war - This goal is responsible to create a .war (Web Archive) file

* deploy- This goal is responsible to deploy the .war file at pre-defined server.

## Practical tips

* Build every time a change is checked in


* Ensure that the steps of static/dynamic analysis, unit testing, code coverage etc are also included


* If the build is broken, the development team needs to fix it immediately
