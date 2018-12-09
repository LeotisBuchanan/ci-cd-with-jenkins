install jenkins on ubuntu

we use docker 
## start jenkins in docker container
docker run -u root --rm -d -p 8089:8080 -v jenkins-data:/var/jenkins_home -v /var/run/docker.sock:/var/run/docker.sock jenkinsci/blueocean


