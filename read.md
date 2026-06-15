
1. Lancer Jenkins — depuis le dossier jenkins/ :

docker compose up -d

2. Récupérer le mot de passe initial :

docker exec jenkins cat /var/jenkins_home/secrets/initialAdminPassword

6110b920a5134d30beedd87b7710b620

3-Test

http://localhost:8080/

User admin admin

Plugins to install: 
- Blue ocean
- Stage view

Tools to install : 

Maven 3.9.6 with same name as jenkinsFile of project 
