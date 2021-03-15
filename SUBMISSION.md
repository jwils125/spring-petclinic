# Instructions
**TODO:** Jessica Wilson 1983073

**TODO:** Add your screen captures to a new directory called [images](images).

**HINT:** Embed your screen captures as requested in the sections below. You can embed the image using the following syntax:

```
![Screen Capture #1](images/my-screen-capture.jpg)
```

HW 8 Deliverables [50 pts]
DOCKER
- Your docker File. Please provide a link to this  File rather than a screen capture. https://github.com/jwils125/spring-petclinic/blob/master/Dockerfile
- Your running docker instance as shown by a ps command. ![Screen Capture #1](images/dokcerpsRunning.PNG)
- Your browser accessing the main page of the website from your local container. ![Screen Capture #1](images/browserAcessFromLocalContainer.PNG)
DOCKER COMPOSE - MYSQL ONLY
- The output from the docker-compose up command. ![Screen Capture #1](images/docer-composeUpOutput.PNG)
- Your browser accessing the "Veterinarians" page of the website from your local container when you run the application from the host system. ![Screen Capture #1](images/SQLConnectionLocally.PNG)
- A section of the stack trace generated when you attempt to run the application container that has been updated to use MySQL. ![Screen Capture #1](images/RestartWithPropertyCommentedOut.PNG)
DOCKER COMPOSE - APP SERVER AND MYSQL
- Your updated docker-compose.yml  File containing the application server, built from your local Docker File, and the existing MySQL configuration. Please provide a link to this  File rather than a screen capture.
- Your updated application-mysql.properties  File containing the URL change for the database server. Please provide a link to this  File rather than a screen capture. https://github.com/jwils125/spring-petclinic/blob/master/docker-compose.yml
- The output from the docker-compose up command. ![Screen Capture #1](images/BothDocker-composeUpOutput.PNG)
- Your browser accessing the "Veterinarians" page of the website from your local container. ![Screen Capture #1](images/PetClinicAfterDockerCompose.PNG)



___________________
- Your Github account showing that is has been forked from the depaulcdm/springpetclinic repository. ![Screen Capture #1](images/forkedRepositoryScreenshot1.PNG)
- Your Travis CI dashboard showing a successful first build. ![Screen Capture #1](images/TravisCISuccessfulFirstBuild.PNG)
- The section of the POM file showing the coordinates after you’ve changed them. ![Screen Capture #1](images/ChangedPOMCoordinates.PNG)
- Your Travis CI dashboard showing a successful build after your change of the group ID. ![Screen Capture #1](images/SecondBuildPassingWithGroupIdChange.PNG)
- The section of the POM file showing the coordinates after you’ve commented them out. ![Screen Capture #1](images/CommentedOutCoordinatesinPOM.PNG)
- Your Travis CI dashboard showing the unsuccessful build after the breaking change. ![Screen Capture #1](images/TravisCIFailureBuild.PNG)
- Your Github repository with the readme.md file selected showing the build failed status after the Travis CI build fails. ![Screen Capture #1](images/BuildErrorStatusInGitHub.PNG)
- The section of the POM file showing the coordinates after you’ve fixed them. ![Screen Capture #1](images/ChangedPOMCoordinates.PNG)
- Your Travis CI dashboard showing the successful build after the breaking change has been fixed. ![Screen Capture #1](images/TravisCISuccessfulFinalBuild.PNG)
- Your Github repository with the readme.md file selected showing the build success status after the Travis CI build has recovered. ![Screen Capture #1](images/BuildPassingStatusInGitHub.PNG)