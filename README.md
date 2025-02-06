### What are Build and Package Manager Tools? 
* Application needs to be deployed on a production server
* For that, we want to package application into a single moveable file (artifact), also called "building the code"
* This is what a build tool or package manager tool does

### What is an "artifact"?
* Moveable file that includes application code and all its dependencies
* 
### What does "building the code" mean?
* Compiling the code
* Compressing the code
* Package hundred of files to 1 single file

### What is an "artifact repository"?
* Storage for artifacts. It stores the builded artifacts and dependencies.
* To deploy artifacts multiple times, have backups etc
* You can push docker images to a diffirent articfact repository such as Nexus, DockerHub or ECR etc..

### Why Docker
It makes the process universal. You can run the same docker image on any machine. And you have less types of artifacts to manage. It also make the easier because you can use the same docker image for development, testing and production.