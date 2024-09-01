HERE IS MY RECENT DEVOPS PROJECT
A CI/CD PIPELINE PROJECT USING JENKINS

THE TASK:
TO BUILD A CI/CD PIPELINE FOR A JAVA APP TO BE PUSHED TO DOCKERHUB USING JENKINS

THE STEPS
-Push the source code Github
-Set-up a pipeline script in Jenkins
-In the script:
   - Define the build tool, Maven in this case (Configure the tool in Jenkins)
   - The stages
     - checkout from git repository, install maven
     - build docker image
     - push image to docker hub (add login credentials as secret text in Jenkins)
  <img width="674" alt="image" src="https://github.com/user-attachments/assets/8786c805-0b8d-4ba8-b13c-a7820b34cb43">

Copy script to create a jenkinsfile, 
push jenkinsfile to github

FUTURE PROJECT - Add some test stages, Push to different Environment, Get Gmail notification,  Push the image directly to kubernetes...
