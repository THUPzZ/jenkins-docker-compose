# jenkins-docker-compose
$docker-compose up -d 

#fist time unlock jenkins
$docker exec jenkinscore cat /var/jenkins_home/secrets/initialAdminPassword
copy key
openbrowser myipserver:8080
paste key 


