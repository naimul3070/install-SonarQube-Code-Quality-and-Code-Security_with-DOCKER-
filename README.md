## Welcoem

### Installation Guide SonarQube A to Z

###### SonarQube is a Code Quality Assurance tool that collects and analyzes source code, and provides reports for the code quality of your project. It combines static and dynamic analysis tools and enables quality to be measured continually over time.

### For SonarQube we need

1.Ubunto 20.4 LTS
2.Docker

Step 1. Inatall Docker
#### update the full system
    sudo apt-get update
#### Install dokcker
    sudo apt install docker.io
### Search for Docker Images
    docker search image name
### Pull the sownarqube images and runn to 9000 port this will search for new image and pull them on docker
    docker run -d --name sonarqube -p 9000:9000 -p 9092:9092 sonarqube
### Start docker and nginx
     systemctl start docker
### Docker status
    docker ps
### Docker lsit
    docker ps -l
### Docker Images
    docker images
# Your sonarqube is ready for browse visit in TCP:9000

###### ID:
    admin
###### password:
    admin
### After loging you will get a password change option and you need to update your default password

<img width="955" alt="image" src="https://user-images.githubusercontent.com/50922314/165480904-6c4131d1-aca1-4cd0-9ba2-3d5b7a9010f9.png">





===============================================================================================================
### Deploy react.js project menally----

-------Pre-requsit
Setp 01.

# Download and configur environment

# Environment setup
## 1.Java >> JAVA_HOME >> spesify the java version

## 2.Jdk  >> path spesify the bin file

## 3.node.js >> install node js

# 4.sonarqube.bat .>>path spesify the bin from sonarqube runtime file


-----STEP02.
# open SonarQbe and create a project by Generate the token and run all the comand in project directory




### Deploy asp.net project menally----

#### ----------Pre-requsit
## -----Setp 01.

##v Download and configur environment

### Environment setup
# 1.Java >> JAVA_HOME >> spesify the java version

# 2.Jdk  >> path spesify the bin file

# 3.node.js >> install node js

# 4.must be install .net sdk


---------STEP02.
# open SonarQbe and create a project by jenerate the token and run all the comand in project directory
