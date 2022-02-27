Node {
   checkout scm
   docker.withRegistry('https://registry.hub.docker.com', 'dockerhub') {
    def customImage = docker.build ("fajarnrs/testing")
     /* Push the container to the custom Registry */
     customImage.push()
   }
}
