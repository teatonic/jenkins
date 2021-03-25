# jenkins

## 1. Run the image
'''
sudo docker-compose --project-name jenkins --project-directory $(pwd) up -d
'''

## 2. Retrieve the admin password
'''
docker exec jenkins cat /var/jenkins_home/secrets/initialAdminPassword 
'''

## 3. Install suggested plugins

