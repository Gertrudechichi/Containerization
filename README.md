Businesses can decide to host their application on an Ec2 instance which can provide the compute resources needed to run the application. 
Ec2 instances just like any other virtual machine runs on top of a host. The hypervisor provides the virtualization environment while allocating 
resources from the host to the servers running on the host and bringing about multitenancy. 

However, for virtual machines such as EC2 instances, an operating system isrequired to launch the EC2 insatnce.
The Operating system running on top of the instance is required for the EC2 instance to to successfully host an application.
The Operating system running on top of the ec2 instance uses some its resources and hence an application running on top of an EC2 instance may not have sufficient
resources to operate efficiently.

The idea of containerization helps to mitigatee this issue. With conatiners such such docker, the applcaition and its dependencies are packaged into a conatiner and no
guest Operating system is required for the application to run on the docker container. the docker container runs directly on top of the host and utilises resources sufficinetly
from the host. 
The absence of a guest operating system is one of the factors that constitute the the lightweight nature of containers. Again, the dockerized application will be able to use 
enough resources from the host.

In this lab a dockerfile was used to create an image for a container. Here, the docker compose file used the image obtained from the dockerfile to create multiple containers , orchestrated and managed them to host an index.html file .





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
