# Deployment-and-configuration-of-a-Private-Cloud-in-AWS
Ex.4 Deployment and configuration of a Private Cloud  in AWS

Aim:
To set up of a Private Cloud  in AWS.
         Setting up of a private cloud in AWS:
Setting up a private cloud within AWS, also known as a Virtual Private Cloud (VPC),
involves creating a logically isolated virtual network that you can use to launch AWS
resources. This provides you with full control over your virtual networking environment,
including resource placement, connectivity, and security.
Amazon Virtual Private Cloud (Amazon VPC) gives you full control over your virtual
networking environment, including resource placement, connectivity, and security. Get
started by setting up your VPC in the AWS service console. Next, add resources to it such as
Amazon Elastic Compute Cloud (EC2) and Amazon Relational Database Service (RDS)
instances. Finally, define how your VPCs communicate with each other across accounts,
Availability Zones, or AWS Regions.
Procedure:
1. Plan Your VPC:
● Determine your needs:
Define your use case, including application requirements, security needs, and
compliance standards.
● Plan IP address ranges:
Choose appropriate IP address ranges for your VPC and subnets to avoid conflicts.
● Select Availability Zones:
Decide which Availability Zones (AZs) you'll use for your resources, considering
redundancy and performance.
● Plan internet connectivity:
Determine if you need public internet access and how to configure it.
● Define security:
Plan your security groups, network ACLs, and access controls to ensure a secure
environment.
2. Create Your VPC:
•	Sign in to AWS Management Console: Access the VPC console and navigate to the VPC dashboard.
•	 Choose "Create VPC": Initiate the VPC creation process.
•	Configure VPC details: Enter the VPC name, CIDR block, Availability Zones, and
•	other necessary settings.
•	Create subnets: Define subnets within your VPC to isolate different parts of your
•	network.
•	Create route tables: Specify how traffic is routed within and outside the VPC.
•	 Create security groups: Define access control rules for your resources.
3. Deploying Resources:
•	Launch EC2 instances: Create and launch virtual machines within your VPC.
•	 Set up RDS instances: Deploy databases for your applications.
•	Configure networking: Connect your resources to the appropriate subnets, security
groups, and route tables.
•	Deploy other AWS services: Integrate other services like S3 for storage and Lambda for serverless computing.
4.Managing and Monitoring:
•	Use AWS CloudWatch: Monitor your VPC and resources for performance and
health.
•	Configure logging and auditing: Track access and activity within your VPC for
security and compliance.
•	Implement security best practices: Regularly review and update your security
configuration.
•	Scale and adjust as needed: Adjust your VPC infrastructure to meet changing
demands.

Snap Shot:

 

Snapshot 1: Create VPC
 <img width="1920" height="1020" alt="Screenshot 2026-10-29 153331" src="https://github.com/user-attachments/assets/8cf2270a-05f9-4f50-a577-a73342f95f46" />

 <img width="1920" height="1020" alt="Screenshot 2026-10-29 153937" src="https://github.com/user-attachments/assets/0025036e-6ac6-4446-bec7-46d9d4237452" />


Snapshot 2: Configuring Subnets
 <img width="1920" height="1020" alt="Screenshot 2026-10-29 154151" src="https://github.com/user-attachments/assets/d611363b-2953-4ee9-a299-6b7b3bcfccce" />

<img width="1920" height="1020" alt="Screenshot 2026-10-29 154521" src="https://github.com/user-attachments/assets/b8c9566a-ffba-478d-b598-2439ac232a7b" />

<img width="1920" height="1020" alt="Screenshot 2026-10-29 154651" src="https://github.com/user-attachments/assets/bb0a4a93-416b-475a-874c-505fde614ed6" />


Snapshot 3: Configure Subnets
 <img width="1920" height="1020" alt="Screenshot 2026-10-29 154658" src="https://github.com/user-attachments/assets/25ecbefe-4cc1-4c9a-9817-77f3ade2c822" />

<img width="1920" height="1020" alt="Screenshot 2026-10-29 160437" src="https://github.com/user-attachments/assets/f5738dc9-13d0-45ac-b450-909cb0b28b32" />

Snapshot 4: Setting Internet gateway

 
Snapshot 5: Setting Internet gateway



 

Snapshot 6: Setting Internet gateway

 
Snapshot 7: Creating route table

 
<img width="1920" height="1020" alt="Screenshot 2026-10-29 160630" src="https://github.com/user-attachments/assets/b6a7d9b0-9803-4596-87c7-d97a68421c62" />


Snapshot 8: Configuring route table
<img width="1920" height="1020" alt="Screenshot 2026-10-29 160437" src="https://github.com/user-attachments/assets/21d6bfc1-696c-41ef-8278-46dd05009557" />


 <img width="1920" height="1020" alt="Screenshot 2026-10-29 160811" src="https://github.com/user-attachments/assets/b6500204-7f67-410b-b81d-e753914b8f2b" />

Snapshot 9: Editing routes

 <img width="1920" height="1020" alt="Screenshot 2026-10-29 160437" src="https://github.com/user-attachments/assets/ef5efe34-5ef4-41b9-ba48-4901349984cf" />
 <img width="1920" height="1020" alt="Screenshot 2026-10-29 155319" src="https://github.com/user-attachments/assets/7669bff2-930f-4868-8550-cad08c45af05" />


Snapshot 10: Creating route table

<img width="1920" height="1020" alt="Screenshot 2026-10-29 160811" src="https://github.com/user-attachments/assets/a4315fa5-5647-4ad0-8c0c-a3b7094d2b1b" />


<img width="1920" height="1020" alt="Screenshot 2026-10-29 161031" src="https://github.com/user-attachments/assets/06928fa9-dfb2-47ad-b85c-5ad4114bef0a" />

<img width="1920" height="1020" alt="Screenshot 2026-10-29 161206" src="https://github.com/user-attachments/assets/9626ffac-af44-4854-b493-61e47195b32b" />

<img width="1920" height="1020" alt="Screenshot 2026-10-29 161437" src="https://github.com/user-attachments/assets/cbfe0c2f-59c1-402e-85b7-b5a8185aa361" />

<img width="1920" height="1020" alt="Screenshot 2026-10-29 162137" src="https://github.com/user-attachments/assets/6ae5c7af-6c08-440d-ad35-0932a2205e29" />



<img width="1920" height="1020" alt="Screenshot 2026-10-30 133906" src="https://github.com/user-attachments/assets/7d33d73b-d13a-4a73-a42c-20c7f01339c1" />













Result:
Thus, a  private cloud on AWS involves using VPCs has been created for  a dedicated, isolated network where we can manage our resources and control access according to our requirements.
 
