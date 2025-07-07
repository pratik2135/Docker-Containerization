## Virtualization and Containerization Intro.
Virtualization is the process where physical servers are divided/segemented into multiple Virtual Machine (VM) by installing hypervisor on it such that each virtual machine has its own logical isolation of resources.  
Whereas containerization involves creating containers by insatlling conatinerization platform like DOCKER by following either of two cases:  
1. Installing docker (containerization platform on VM like EC2 instance) and create container on it. This method is now most widely used while considering the microservices world of architecture designing of services or application.  
2. Installing docker directly on physical server.

## Why containers are lightweight in nature?
Containers are lightweight in nature because they use a technology called containerization which allows them to share the host operating system's krenel and libraries, while still providing isolation for application and its dependencies. This isolation helps containers to be ligthweight in nature.  
While building docker images each instruction within a dockerfile creates a layer in the image. When you change the dockerfile and rebuild the image, only those layers which have changed are rebuilt. This part makes images lightweight and easy to ship and run.

## Docker
Docker is a containerization platform that provides easy way to containerize your application, such that you can build the images, make them run to create containers and push the images to public or private repositories for centralized sharing on platform like docker hub, quay.io etc.


   

