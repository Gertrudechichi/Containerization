Businesses can decide to host their application on an Ec2 instance which can provide the compute resources needed to run the application. 
Ec2 instances just like any other virtual machine runs on top of a host. The hypervisor provides the virtualization environment while allocating 
resources from the host to the servers running on the host and bringing about multitenancy. 

However, for virtual machines such as EC2 instances, an operating system is required to launch the EC2 instance.
The operating system running on top of the instance is required for the EC2 instance to to successfully host an application.
The operating system running on top of the ec2 instance uses some of the EC2 instance resources and hence an application running on top of an EC2 instance may not have sufficient
resources to operate efficiently as compared to containerized applications.

The idea of containerization helps to mitigatee this issue. With containers such such docker, the application and its dependencies are packaged into a container and no
guest Operating system is required for the application to run on the docker container. The docker container runs directly on top of the host and utilises resources sufficinetly
from the host. 
The absence of a guest operating system is one of the factors that constitute the lightweight nature of containers. Again, the dockerized application will be able to use 
enough resources from the host.

Dockerfile is primarily used to build a single docker image loaclly which can be pushed to dockerhub.The docker image obtained from a dockerfile can be used to create multiple containers but this cannot be daone simmultaneously.The docker compose file can be used to build images by referencing a dockerfile created locally or by simply pulling images from the dockerhub.with this, the dockercompose file is able to run multiple containers at the same  time to host the busiiness logic 

In this lab the dockercompose file was used to build an image of a docker file stored locally from the frontend directory and another image of  a dockerfile in the backend directory.The dockercompose file pulled an image from the docker hub as well. With these images, the dockercompose file was able to run three containers simultaneously to host their corresponding appliactions.




![image alt](https://github.com/Gertrudechichi/Containerization/blob/c6a436b85003859599f08543e6a3648a04c46eb7/Screenshot%202025-05-20%20230338.png)


![image alt](https://github.com/Gertrudechichi/Containerization/blob/c6a436b85003859599f08543e6a3648a04c46eb7/Screenshot%202025-05-20%20230356.png)

![image alt](https://github.com/Gertrudechichi/Containerization/blob/c6a436b85003859599f08543e6a3648a04c46eb7/Screenshot%202025-05-20%20230408.png)

![image alt](https://github.com/Gertrudechichi/Containerization/blob/c6a436b85003859599f08543e6a3648a04c46eb7/Screenshot%202025-05-20%20230437.png)

![image alt](https://github.com/Gertrudechichi/Containerization/blob/c6a436b85003859599f08543e6a3648a04c46eb7/Screenshot%202025-05-20%20230454.png)

![image alt](https://github.com/Gertrudechichi/Containerization/blob/c6a436b85003859599f08543e6a3648a04c46eb7/Screenshot%202025-05-20%20230509.png)

![image alt](https://github.com/Gertrudechichi/Containerization/blob/c6a436b85003859599f08543e6a3648a04c46eb7/Screenshot%202025-05-20%20230524.png)

![image alt](https://github.com/Gertrudechichi/Containerization/blob/c6a436b85003859599f08543e6a3648a04c46eb7/Screenshot%202025-05-20%20230538.png)

![image alt](https://github.com/Gertrudechichi/Containerization/blob/c6a436b85003859599f08543e6a3648a04c46eb7/Screenshot%202025-05-20%20230558.png)

![image alt](https://github.com/Gertrudechichi/Containerization/blob/c6a436b85003859599f08543e6a3648a04c46eb7/Screenshot%202025-05-20%20230634.png)
