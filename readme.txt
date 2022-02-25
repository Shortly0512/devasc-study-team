1. Create Github Account
- create a new repository, also push this code to the repo

2. Docker Instance
Please create an Virtual Machine with the following requirements : 
- Installed Docker & Run Docker at the start up.
- Installed Nginx & Run Nginx at the start up.
- Create Dockerfile to create simple app images
- Run Simple Application on docker, but not published to public.
- Only nginx port can be accessed from public
- Simple Application can only accessed from nginx port.

3. CI/CD Pipeline
- create virtual machine, with installed jenkins.
- Integrate you jenkins to your github repository.
- Please create CI process, where :
  * it will run docker build on every changes in the github repository
  * when the docker build complete, please push the docker images to docker registry e.g dockerhub
- Please create CD process, where : 
  * deploy new images from CI process to Docker Instance. 