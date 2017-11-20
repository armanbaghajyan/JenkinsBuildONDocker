In this Project I installed Jenkins Master Slave to bild the maven job then installed elasticsearch and kibana to viewing output log and then I install rabbitmq to send message to queue and then run python script to send email notification about build.
All Installation and configuration was made on Docker with Docker compose 

- Task Running steps
- Install docker and docker compose 
- Create folder and get to it
- Download project from Git
- Download Jenkins workin dir from link https://drive.google.com/open?id=1DrTGweHJK1JY7lMieJXJHjrRELP5gisZ
- Unzip jenkins.tar.gz to jenkins folder
- Unzip Python.tar.gz to python folder and then open rabbitmq.py file and add email credentials
- And run docker-compose up
- After it create queue and excahange in rebbitmq
- Then login to jenkins and connect to slave
- Then run the build 
