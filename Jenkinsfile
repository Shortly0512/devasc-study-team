Node {
   checkout scm
   docker.withRegistry('https://registry.hub.docker.com', 'dockerhub') {
    def customImage = docker.build ("testing/node-app")
     /* Push the container to the custom Registry */
     customImage.push()
   }
}