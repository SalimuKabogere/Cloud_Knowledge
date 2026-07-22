A container packages your application with everything it needs to run
These could be 
>>Config files
>>Dependencies
>>Environmental variables


---
![[Pasted image 20260722171122.png]]There are two orchestration services on AWS

---

ECS and EKS
ECS
>>This is fully managed service basing on the parameters that you set
>>Works for streamlined and integrated applications

EKS
>>Kubernetes managed service
>>Open source
>>Automates containerised applications


---
AWS offers a container registry to tell where the containers are stored
That is the ECR: Elastic Container Registry
>>Stores container images

Where do these images actually run, 
AWS offers two service, 
>>EC2 : You manage the virtual machines
>>Farget: Serverless , you only manage the containers

**How it works all together**
Push your container to ECR
Choose an orchestration platform, either ECS or EKS :These are orchestration platforms
Select which compute to run your container eg EC2 or Fargate: these are hosting platforms