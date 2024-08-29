# Azure && Cloud Computing

## Day-1

### Cloud

- Cloud computing is a severless computing
- it is a pay as you go service.
- ![alt text](image.png)
- the applications of the cloud computing like netflix,amazon..etc
- Cloud uses NOSQL database.
- private cloud means the cloud which we take the subscription.
- the passwords are stored in the cloud but in the special combination called encryption and decryiption.

### SAAS

- ![alt text](image-1.png)
- Saas delivers Software applicaitons over the internet,allowing users to access and utilize them web browsers or mobile apps.
- Scaling : the group and the project we will be working is
  autoscaling group(asg).
- in the Active directory all the usernames and the passwords are stored .
- in SaaS the level of restriction is more than compared to other services.
- ![alt text](image-6.png)

## IaaS

- ![alt text](image-2.png)
- we have much flexibility in the IaaS because we have much control over the infrastructure.

## PaaS

- ![alt text](image-3.png)
- it is b/w IaaS and SaaS
- PaaS provides the services like development.deployment and managing.
- ![alt text](image-4.png)
- the abstraction for the Saas is high because we don't know how the application is build
- the application is considered as complex if it has variety of the users like there are much users and there are users accessing from the differet locatio and at a same time the user may click same button which says that the application is complex
- the constraints like
  - number of users
  - turn around time(TAT)
  - Storage
- Example is Meta i.e facebook
- ![alt text](image-5.png)
- serverless,deployment,application ,behaviour,infrastructure are the main constriants to categorize an application into Iaas,Paas,Saas
- the printer is a serverless and it is not a deployed , it is an application so it is a SaaS.

### Azure

- it is a cloud platform offering wide range of services, from compute and storage to networking.
- Azure Service :
  - ![alt text](image-7.png)
- Compute :
- VM,containers,serverless computing
- computation means how fast we can achieve the results.
- compute is process used for running the application,execute the process
- containers has the dependencies where ever we install it we can use that resources.

### Azure compute :

- ![alt text](image-8.png)
- VMs,Containers,ServerlessComputing

1. Virtual Machines(VMs)

- On-demand means whenever needed,we can perform scaling

2.  containers deploy and managae containerized applications with azure container service.

- azure has its own container service in which we don't need to worry everything is managed by the azure.

### Azure Storage:

- ![alt text](image-9.png)
- Blob storage,filestorage,queue Storage,Table Storage.

### Azure Networking:

- ![alt text](image-10.png)
- if we want to pass the data through the network we use this VPN gateways.
- Virtual network,load balancers
- virtual network is a private cloud network

### Azure Security:

- Identity management - Azure will maintain the identity by using this identity manaagment service in which it will perform the authentication and the authorzation.
- based on the roles like developer , tester,deployment those are only visible and can be usable to that identity this is managed by the admin i.e azure team
- authentication means validating only the user name and the password.
- in authorization it will decide what resources can be accessed
- ![alt text](image-12.png)

### Azure monitoring:

- Log analysis,Metrics,Alerts
- ![alt text](image-11.png)
- we don't interfear in this we just utilize it.

# Day-2

### Azure WebJob

- the web jobs will automate the tasks in background . it is a convenient way to execute code on a schedule or in response to certain triggers,without having to manage seperate infrsatructure.
- Web jobs is used for tracking the tasks performed by the user they will not intimate the user but at the end of the month it will gives the bill.
- it a background task run by the azure
- ![alt text](image-13.png)
- bill is generated with the help of the azure webjob because it will continusly moniter the users actions.
- ![alt text](image-14.png)
- ![alt text](image-15.png)
- ![alt text](image-16.png)
- ![alt text](image-17.png)

## Containers

- ![alt text](image-18.png)
- the packages has the code ,libraries, and all the dependencies to run a project those all are present and is stored in the containers to save the time .
- the three pillers of the containers are
  - isolation
  - portability
  - Efficency

#### Benfits of the containerization

- ![alt text](image-19.png)

## Docker(in depth)

- ![alt text](image-20.png)
- for deploying purpose we use the dockers
- it a container engine
- ![alt text](image-21.png)
- ![alt text](image-22.png)
- the commands used to run the docker is called the docker client
- docker daemon : it will take lot of space it builds,runs and manages the containers.
- docker registers have multiple images.

### Building the docker images

- ![alt text](image-23.png)
- Azure resource manager(ARM)- means azure has many resources this is managed by the arm.
- API : google maps is an api and that api can be used by the many applications like swiggy,zomato

### Azure Function app

- used to
- Scale behaviuor :what factor determine when to increase and when to decrease
-
