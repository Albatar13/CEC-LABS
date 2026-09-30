# CEC-LABS

TP1 :

Step 1:

1 / A virtual machine is a software-based environment that simulates a real computer. It relies on a host machine and work like it had his own CPU, memory, disk and OS.

2 / Virtualization is useful for the isolation between different working environment. It is also useful to mutualise the ressources of one computer (the hosting machine)

3/ Working on a virtual machine helps to use only the ressources that we need, avoid to affect sensible data from the hosting machine. It is maily used to experiment safely without impacting the real system or using different OS on the same machine.

Step 2:

1/ A container is an environment that packs an application (with all his dependencies). The main goal is that it can be easily executed everywhere.

2/ While a VM virtualizes a whole machine a container only virtualizes what the environment needed to run an application. That means that a container doesn't need his own OS ( he uses the hosting machine one) and that it is lighter and run way quicker.

3/ Containers are adapted to the Cloud cause they don't have their own OS, they are light, quick and highly portable. Their replicabity make them ideal for scaling applications efficiently. 

Step 3:

1/ A dockerfile is better for the replicabilty, the portability and we also won't need to install the dependencies manually or configure the evironment on each machine. 

2/ An image docker is the model of the application while a container is a running instance of that image.

Step 4:

1/ Docker compose is better because by creating a shared network it automatizes the connexions between the differents containers and allow us to run it as a single application. This is useful when an application is composed of different services

2/ The docker compose is the architecture definition : it declares all the services and ports we are going to need for the full application. Docker compose use this file to automatically build and run all the services.

3/ Docker compose runs on only one computer which limits a lot the scalabity and availability (Kubernetes works better for that). 

