## Sonarqube features

Sonarqube is a web based open source tool to manage code quality. It has the following features - <br>
Can check the source code for -

* standard architecture and design principles

  * comments

  * coding rules

  * code complexity

  * duplication in code

* Covers many languages like Java, C,C++

* Has rules, thresholds and alerts can be configured online

## Working of sonarqube

1.Sonarqube has a list of built-in rules for different languages

2.Rules can be configured as per needs called a profile. Sonarqube has a feature which allows the users to create custom quality profiles on various parameters like defects, code smells, issues etc. Default profile is called Sonarway. Customized profiles can be created and attached to projects by activating required set of rules

3.There are three ways to execute sonarqube

* Sonar runner (command line)

* Build script

* Sonar Lint (plugin to Eclipse)

4.When these profiles are applied to a project, analysis is performed and a dashboard is created

5.The dashboard provides the following details:
* Code demographics – no. of lines of code, files etc

* Bugs in code

* Code smells

* Code coverage details

* Duplications in code

* SQUALE rating for technical debt

6.Quality gates can be applied to ensure that code that does not pass the quality conditions do not move forward to the next stage. 
