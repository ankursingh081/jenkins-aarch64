### Start the Container

`$docker run --name jenkins-master --detach -v jenkins_home:/var/jenkins_home -p 8080:8080 -p 50000:50000 ankursingh081/jenkins-aarch64`


Access the **Jenkins Console** at `http://localhost:8080/`
