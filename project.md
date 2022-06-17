GROUP MEMBERS | MATRIC NO
------------ | -------------
Abdulrahman Alaidaros | 1826053
HASSAN | 1827297
Zakarya Ahmed Babatat  | 1817749
Roki Md Rasel Rana | 1820927

## Table of Contents
* Abstract 	                                                          
* Introduction	 	                                                      
* What is docker?	 	                                                  
* Why use containers in docker?	 	                                    
* What is the difference between docker and virtual machines?	 	     
* Describe some of the docker tools provided	 	                        
* What are docker images?	 	                                          
* How do you manage data and volume in docker?	 	                      
* How does container network communication work?	                      
* How does networking in Kubernetes work?	 	                          
* How do you manage data and volume in Kubernetes?	                    
* How is Kubernetes used for scalability?	 	                         
* Conclusion	 	                                                        
* References	 	                                                        


## Abstract
In this paper, we will analyze Docker and its various futures. We'll look into what Docker is, how it's used, and how it differs from other comparable concepts and use cases. Our experts will thoroughly investigate each subject, using a variety of online resources. We'll cover Docker in this paper.

## Introduction
A computer user's interaction with the machine's hardware is provided by the operating system. An operating   system is responsible for everything from file management and memory management to process management and handling input and output. As the link between the user's commands and the computer's hardware, this software directs the execution of all other kinds of programs.
There are two fascinating operating system issues covered in this term paper: docker and Kubernetes. Docker is a platform for running programs and making the process of developing and distributing them more efficient. Kubernetes, on the other hand, uses container technology. Any containerization technique can theoretically work with Kubernetes. Rot and Docker are two of the most popular third-party integrations for Kubernetes. As a result, more work has been put into refining the integration between Docker and Kubernetes than has been put into any other containerization technique. Both of them shared certain similarities with us. Open-source communities are dear to their hearts. Both are significant open-source initiatives.

## What is docker?
Docker is a free and open-source platform for running applications and streamlining the development and distribution of software applications. Using docker, applications can be packaged in a standard form called a container, which includes all of the necessary components. These containers run on top of the operating system's kernel in an isolated manner. Docker is a virtual machine in a container form. However, unlike a virtual machine, Docker merely requires that apps be supplied with things not already running on the host computer, rather than establishing a virtual operating system from scratch. The application's speed and size are both improved as a result of this. The additional abstraction layer may have an impact on performance. When you consider that containers have been available for over a decade, docker stands out as one of the best breakthroughs since it has new capabilities that other technologies lacked. The ability to construct and govern containers is the first benefit of this system. In addition, docker containers can be created by the developer and used to package apps. Virtualized programs can be used from any location without requiring any additional setups or modifications. On top of that, docker is capable of displaying more virtual scenarios than other breakthroughs, all on the same piece of software. To summarize, third-party instruments can simply cooperate with Docker to facilitate the deployment and management of Docker containers.

## Why use containers in docker?
In order to simplify the process of building, deploying, and running software in containers, the Docker project was created. There are a number of ways in which containers may be used to package up a program and ship all of its components together. There's no need to install anything on a server to run code in a Docker container because the entire filesystem is contained within the container. Containers are segregated from their host system and also from other containers, so that they can be run in a secure environment as a result, the software will always function the same manner, no matter what the circumstances. By eliminating the requirement for a whole OS, TCP, and file system stack for each container in Docker's container-based architecture, the technology is receiving a lot of attention. Docker makes use of containers as well because of the numerous advantages they give, including the following:

1. Speed: With regard to performance, Containers are frequently extolled for their lightning quickness. When discussing the advantages of utilizing docker, it would be impossible not to mention the speed of docker. Because containers are so compact, they may be constructed in a short period of time. As containers are compact, the development, testing, and deployment process may be completed more quickly. Once a container has been constructed, it can be deployed to a test environment and ultimately to a production environment.

2. Portability: Those applications that are built inside docker containers are extremely portable. These portable applications can easily be moved as a single element and the performance remains the same.

3. Scalability: Docker has the feature that it may be deployed in various physical servers, data servers, and cloud platforms. It can also be run on every Linux machine. Containers can simply be transported from a cloud environment to a local host and from there back to cloud again at a quick speed. Adjustments can easily be done; the scale can simply be modified by the user according to the necessity.

4. Rapid Delivery: Docker Containers have a common format, so programmers don't have to worry about each other's work. The administrator is in charge of deploying and maintaining the server with containers, while the programmer is in charge of the apps running inside the docker container. Containers can work in any environment since they have all of the needed dependencies and have been thoroughly vetted. When code is moved between development, test, and production systems, Docker provides a dependable, consistent, and better environment, allowing for predictable results.


5. Density: Docker uses the resources that are available more efficiently because it does not use a hypervisor. This is the reason that more containers can be run on a single host as compared to virtual machines. The performance of a Docker Container is higher because of higher density and no overhead wastage of resources.

## What is the difference between docker and virtual machines?
On the host system, the hypervisor is installed, allowing the guest OS to be installed on top of the hypervisor (the host OS sits on top of the hardware). Shipment of the guest OS is possible. It is compatible with the same operating system on other PCs when shipped.
But the concept of hypervisor is not feasible because there are cases where every application might need their own guest OS. And we cannot run multiple operating systems on the same hardware, since that will waste a lot of resources such as CPU, RAM and others. And another problem with hypervisors is licenses. Every OS has its own licenses, and that would cost a lot of money. This is how Docker is different. Docker sits on the OS, without a hypervisor. And Docker can have multiple containers to run different full-fledged applications, along with their respective dependencies. And the containers on dockers are customizable. One can create their own containers.


# Describe some of the docker tools provided.
### Docker tools: 
tag The Docker ecosystem is growing faster than ever, and we can see a lot of Docker tools available for developers. Some of the most useful docker tools are listed below:

Clair (Security): This one is free to use. You may monitor the security of your containers through static analysis of vulnerabilities in appc and docker containers with this open-source project. Clair is an API-driven analysis engine that looks for known security problems in containers one layer at a time. The indexed contents of container pictures are correlated with important and sensitive data imported from a well-known set of sources to provide lists of vulnerabilities that threaten a container. Clair is an effective method for ensuring the safety of a container.

Docker Notary (Security): Another security-based Docker project tool. It is mainly security for data collection. Digitally sign published collections with this tool and allow the users to confirm the integrity and source of content.

CodeShip (CI/CD): It is a customizable CI platform and provides native support for Docker by working with Docker workflows. It also automates testing and also supports many cloud platforms and orchestration tools.

CircleCI (CI/CD): It ensures delivering value to clients. CircleCI boosts Developers productivity by making the CI process quicker, simpler, and easier. It integrates quickly and allows you to build and deploy immediately after signup. It debugs manually through SSH (Secure shell) and dynamically scales the number of containers at the same time when beginning a project.

Prometheus (Monitoring): Prometheus is quite popular and free to use as well. It helps to do system monitoring and altering. It mainly works to do metric generation and collection. Prometheus excels at recording numeric time series and complements both machine-centric monitoring as well. It is built by SoundCloud.

It is a multidimensional data model and helps to slice and dice at will as well as dimensions like instance, service, endpoint, and methods.

Sysdig Monitor (Monitoring): Sysdig Monitor (formally called Sysdig Cloud) is Sysdig's commercial solution for the generation and analysis of system-level information and real-time data. “Sysdig Monitor is the first commercially available cloud monitoring platform that is fully compatible with Prometheus. Give developers their preferred
monitoring approach without the management headache” according to their official website (https://sysdig.com/products/monitor)

## What are docker images?
### Docker images: 
A Docker image is the set of processes described in the corresponding Docker file. It's a file that has many different layers. Layers of processes are created automatically. Layers are interconnected and reliant on one another. Essentially, an image is a set of instructions for creating a fully-functional application that can run on the target system's kernel. For example, by abstracting instructions, an isolated environment can be built that can nevertheless function. A docker image can be generated by modifying an existing image to fit the needs of the container in question. Docker containers and images are two distinct things. A docker file can also be written from scratch.
Docker image is intermediate between other Docker functions. A Docker image consists of the elements needed to run an application as a container -- for example code, config files, environment variables, libraries and run time. The hierarchy of layers is key to efficient lifecycle management of Docker images, but developers should organize layers that change the most often as high up the stack as possible. It is to handle any kind of unexpected situation.

![GitHub Logo](/images/Picture1.png)









