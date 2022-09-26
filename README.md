# container-docker

1. start docker service

        sudo service docker start
        
2. login docker account

        docker login 

3. Download image hello-world

        docker pull dockercloud/hello-world

4. Create new docker container 

        docker run -d --name {container name} -p 80:80 dockercloud/hello-world

5. Check running container 

        docker ps
        
6. Check the service used port 80

        netstat -tulpn | grep 80
