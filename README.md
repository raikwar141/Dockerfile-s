#For Runing Dockerfile you need Docker-engine for that run this line of codes 
...............................................
#!/bin/bash
#Use acc to your os type
yum install docker -y
#apt install docker -y
systemctl start docker
systemctl enable docker
