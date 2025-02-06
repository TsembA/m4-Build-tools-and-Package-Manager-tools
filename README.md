### What are Build and Package Manager Tools? 
Lets say the application needs to be deployed on a production server.
For that, we want to package application into a single moveable file (artifact), also called "building the code".
This is what a build tool or package manager tool does. For example, a build tool is used to manage the dependencies of a project.

### What is an "artifact"?
* Moveable file that includes application code and all its dependencies

### What does "building the code" mean?
* Compiling the code
* Compressing the code
* Package hundred of files to 1 single file

### What is an "artifact repository"?
* Storage for artifacts. It stores the builded artifacts and dependencies.
* To deploy artifacts multiple times, have backups etc
* You can push docker images to a diffirent articfact repository such as Nexus, DockerHub or ECR etc..

### Build Tools for different programming languages
* Java: maven | gradle
* JavaScript: npm | yarn | webpack
* Python: pip
* C/C++: conan
* C#: NuGet
* Golang: dep
* Ruby: RubyGems

But, concepts very similar to other programming languages

### Why Docker
Docker Image is an alternative for all other artifact types.
It makes the process universal. You can run the same docker image on any machine. And you have less types of artifacts to manage. It also make the easier because you can use the same docker image for development, testing and production.