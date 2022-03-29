# CICD Activities
## Application life cycle management(ALM) tool
ALM tool can be used for tracking and managing the user stories, team activities and ceremonies. This tool can be linked to the entire lifecycle and once the integration is completed, the user story is marked complete in the ALM tool. **Jira** is a popular tool for ALM.
## Rapid prototyping
As part of the design phase a rapid prototyping and design tool may be used. The UXPin tool helps for UI design and prototyping. The Infosys Rapid prototyping tool can also be used.
## Version control system
A distributed version control system would be useful if the teams are distributed.**Git** is a popular tool. Other tools like **SVN** and **CVS** may also be used.
## Static and dynamic code analysis
This step involves the execution of quality rules as defined by the static code analyzer on the source code and test cases to ensure that the code meets quality guidelines for emergent design and incremental software development. These rules are configurable, new rules may be added and gating conditions(threshold conditions for code quality) in the static analyzer tool.**Sonarqube** is a popular tool.Others include **CheckStyle,Findbugs,StyleCop and JSHint**.<br>
Dynamic code analysis may also be done by executing the code and analyzing the code for performance, memory utilization etc. **JProbe** may be used for dynamic code quality analysis.
## Code review
Code review process may be automated or automated using tools. Tools like **Jupiter** and **Crucible** helps.
## Unit testing
Unit tests need to be automated so that they can be run multiple times. A standard xUnit framework like **JUnit** can be used. They help maintain and reuse test objects and also help execute them for unit testing.
## Code coverage
In order to check the coverage of the source code by the test cases a code coverage tool is used.**JaCoCo** and **Cobertura** are popular tools as they are lightweight and provide the code coverage granularly in terms of class/file/package level coverage.
## Build automation
The code which meets the quality conditions (gating) set needs to be integrated and built. Automated build tools are used for this purpose. These tools help in creating versions of the binary file. This is done through a build script.<br>
**ANT, Maven, Grunt and Gradle** are popular tools.
## Baseline in artifact/binary repository
The built artifacts needs to be stored in the binary repository in order for the next stages in the pipeline to pick the artifacts.<br>
**Artifactory** from JFrog is a useful tool. **Nexus** can also be used.
