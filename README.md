Businesses can decide to host their application on an Ec2 instance Which can provide the compute resources needed to run the application. 
Ec2 intances just like any other virtual machine runs on top of a host . The hypervisor provides the virtualization environment while allocating 
resources from the host to the servers running on the host and bringing about multitenancy. However, for virtual machines such as EC2 instances, an operating system is
required to launch the EC2 insatnce.The OS running on top of the instance is required for the EC2 instance to to successfully host an application.
The os running on top of the ec2 insatnce uses some  of the resources .and hance an apploication running on top of an EC2 instance may not have sufficaint reaources to
operate efficiently.
The idea of containerization helps to mitigatee this issue. With conatiners such such docker, the applcaition and its dependencies are packaged into a conatiner and no
guest Operating system 
is required for the application to run on the docker container. the docker container runs directly on top of the host and utilises resources sufficisntly from the hsot. 
The absence of a guest operating system is one of the factors that constitute the the lightweight nature of containers. Again, the dockerised application will be able to use 
enough resources from hthe host.

this lab shows a step bys tep procedure in 
