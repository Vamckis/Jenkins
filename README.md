# Jenkins

- docker pull jenkins/jenkins
- docker run -itd -p 8080:8080 --name jenkins_container jenkins/jenkins
- Use the browser to navigate to: localhost:8080
- To get at the token at the path given on the login screen: docker exec -it jenkins_container /bin/bash
- Naviugate to var/jenkins_home/secrets/initialAdminPassword to get key
