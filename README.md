# jenkins
Repository for test

docker run -d --name Jenkins -p 8080:8080 -p 50000:50000 -v /your/home:/var/jenkins_home jenkins/jenkins:lts-jdk11


docker run -d --name Jenkins -p 8080:8080 -p 50000:50000 -v /var/jenkins_home jenkins/jenkins:lts-jdk11



verificar a senha do admin para instalação:
/var/jenkins_home/secrets/initialAdminPassword


