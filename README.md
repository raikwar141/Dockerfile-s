#!/bin/bash
#Use acc to ur os type
yum install docker -y
#apt install docker -y
systemctl start docker
systemctl enable docker
