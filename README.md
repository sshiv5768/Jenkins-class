# Jenkins-class

## What is Jenkins?

- It is an Open-source CI/CD engine.
- It is simple scheduler which internally calls/executes linux or windows commands.
- It was designed for CI/CD.
- When you install Jenkins, a new user gets created.Whatever you do in Jenkins will be run as Jenkins user.

### Things to keep in mind while working with Jenkins

- Ensure all the environmental variables like ``PATH``,``JAVA_HOME``,``PYTHON_HOME``, etc are defined correctly.
- Ensure the software that you are going to use is correctly installed and configured.
- Ensure user have all necessary permissions.

## Installation

- [Refer this page](https://www.jenkins.io/doc/book/installing/) for installation steps.

## Run with Docker

 With the help of Docker, you don't need to follow long installation steps.

- First install Docker, [Follow this steps](https://docs.docker.com/engine/install/) for Docker installation.

- Run below command for pulling latest Jenkins image from Docker hub.

```#docker
    docker pull jenkins/jenkins:lts
```

- Now run below command to run jenkins on port ``8082``.
  
  ```#docker
  docker container run -p 8082:8080 jenkins/jenkins:lts

  ```

- Go to port ``8082`` and you will see below screen.  
  
  ![Screenshot from 2022-02-19 17-34-21](https://user-images.githubusercontent.com/40575397/154800118-5ff9eb6c-9071-4298-bd1a-c50a9c7d4d67.png)

It's the starting screen of Jenkins. It will ask you for the administrator password, which is already present in your terminal. I already marked it for you.

![Screenshot from 2022-02-19 18-04-22](https://user-images.githubusercontent.com/40575397/154801409-a5dda3b6-f5ce-4f18-87e9-9e1a2fb323cb.jpg)



  
  
  
  
