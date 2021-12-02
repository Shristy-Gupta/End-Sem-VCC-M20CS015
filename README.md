# Course Cloud Computing
### End Semester VCC-TICK STACK
### Member: Shristy Gupta M20CS015
### Submitted To: Dr. Sumit Kalra

For detailed information please read the document uploaded.
Also to run the tick stack dockerized environment below steps are given
VCC-docker-Folder consists of   Docker compose file: It contains four set of docker containers that will be executed link: https://github.com/Shristy-Gupta/End-Sem-VCC-M20CS015/blob/main/vcc-docker-folder/docker-compose.yaml
![image](https://user-images.githubusercontent.com/26459890/144478509-2e0ea3ac-e1e9-4e6d-b10a-864f8fdb0548.png)
VCC-cerificate-Folder consists: These consists of keys which is generated with the help of open ssl commands. The Encryption scheme used is RSA-2048 : https://github.com/Shristy-Gupta/End-Sem-VCC-M20CS015/tree/main/vcc-certificate-folder



There are two components in the project 1) To run the container in the dockerize environment and 2) To enable security 
1) To run the four stacks in different components we need to run the docker compose file that contains four set of docker containers.
2) Security is enabled by following ways:
  a)	SSL security is established, the steps are mentioned as above: The certificates and the keys are generated and the steps are described above
  b)	Kapacitor is made secured with the help of password protection 
  c)	Influx DB is secured with the help of password protection 
  d)	Any anomaly or unauthenticated access will be detected and alerted out of TICK dashboard with the help of alert system

To create the open SSL security:
```
openssl req -newkey rsa:2048 -new -nodes -x509 -days 3650 -keyout mycert.pem -out mykey.pem
```
![image](https://user-images.githubusercontent.com/26459890/144478941-22caed02-3c67-4116-8adf-b205217c6571.png)

To get more information please visit https://www.youtube.com/watch?v=qBb7-lLYgM4 

TICK STACK file can now be accessed and will look like:
![image](https://user-images.githubusercontent.com/26459890/144496068-c1c2272f-0190-402c-bdf3-973834197e06.png)
![image](https://user-images.githubusercontent.com/26459890/144496086-cb2e99d2-19be-4c66-9c38-022362c2b1c6.png)
Also the alert rules will look like:
![image](https://user-images.githubusercontent.com/26459890/144496119-4d94052a-da33-4a5f-b3b6-8731b23af9e6.png)
![image](https://user-images.githubusercontent.com/26459890/144496175-f0b3e89e-ea88-4ae6-ba44-1f19d33f4daa.png)






