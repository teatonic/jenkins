# jenkins

## 1. Run the image
'''
sudo docker run --detach --publish 33712:8080 --volume jenkins_home:/var/jenkins_home --name jenkins jenkins/jenkins:lts 
'''

## 2. Retrieve the admin password
'''
docker exec jenkins cat /var/jenkins_home/secrets/initialAdminPassword 
'''

## 3. Install suggested plugins

