# JenkinsSolution

1) Make sure that you have added Jacoco code coverage report plugin and Html publisher plugin in your project
2) Install maven in jenkins. Follow - https://www.tutorialspoint.com/jenkins/jenkins_maven_setup.htm
3) Install Jenkins on your local machine
4) Install the JaCoCo plugin in Jenkins. Manage Jenkins -> Add Plugins
5) Create a new Jenkins job
6) Provide the git repository in which your code is present 
7) Provide your git credentials
8) Add Maven build step with clean install instruction
9) Add jacoco plugin in Post build step to generate code coverage report

If stuck on some instruction please refer to the images.

