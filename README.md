# Course Cloud Computing
### End Semester VCC-TICK STACK
### Member: Shristy Gupta M20CS015
### Submitted To: Dr. Sumit Kalra

For detailed information please read the document uploaded.
Also to run the tick stack dockerized environment below steps are given
VCC-docker-Folder consists of   Docker compose file: It contains four set of docker containers that will be executed link: https://github.com/Shristy-Gupta/End-Sem-VCC-M20CS015/blob/main/vcc-docker-folder/docker-compose.yaml
![image](https://user-images.githubusercontent.com/26459890/144478509-2e0ea3ac-e1e9-4e6d-b10a-864f8fdb0548.png)
VCC-cerificate-Folder consists: These consists of keys which is generated with the help of open ssl commands. The Encryption scheme used is RSA-2048 : https://github.com/Shristy-Gupta/End-Sem-VCC-M20CS015/tree/main/vcc-certificate-folder

To create the open SSL security:
'''sh
openssl req -newkey rsa:2048 -new -nodes -x509 -days 3650 -keyout mycert.pem -out mykey.pem
'''
![image](https://user-images.githubusercontent.com/26459890/144478941-22caed02-3c67-4116-8adf-b205217c6571.png)

To give access rights:




