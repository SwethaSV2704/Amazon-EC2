# Amazon Elastic Compute Cloud (Amazon EC2)

## AIM
  Launch Your Amazon EC2 Instance.
  Monitor Your Instance.
  Update Your Security Group and Access the Web Server.
  Resize Your Instance: Instance Type and EBS Volume.
  Explore EC2 Limits.
  Test Stop Protection.
  
  
## Objective:

The objective of this experiment is to understand the fundamentals of Amazon Elastic Compute Cloud (EC2). This lab focuses on launching and managing a virtual server, understanding instance types and AMIs, connecting to an EC2 instance, monitoring its status, and performing basic instance operations such as start, stop, and terminate.

## ALGORITHM

Steps 1:
Explore the EC2 service dashboard in the AWS Management Console. Observe the different sections such as Instances, AMIs, Instance Types, Key Pairs, Security Groups, and Elastic IPs.

Steps 2:
Launch a new EC2 instance using Amazon Linux 2 AMI. Select an appropriate instance type (t2.micro) under the free tier. Configure basic settings such as instance name, key pair, and security group.

Steps 3:
Configure a security group to allow inbound access:
  SSH (Port 22) from your IP address
  HTTP (Port 80) from anywhere (0.0.0.0/0)
This security group acts as a firewall for the instance.

Steps 4:
Connect to the running EC2 instance using SSH. Use the downloaded key pair and connect via terminal or PuTTY.

For Amazon Linux:
```
ssh -i "keyname.pem" ec2-user@<Public-IP>
```

Steps 5:
Perform the following operations from the EC2 console:
  Stop the instance
  Start the instance
  Reboot the instance
Observe the state changes of the instance.

Steps 6:

Monitor the EC2 instance using the Monitoring tab. Observe metrics such as CPU utilization, network in/out, and instance status checks.

Steps 7:
Terminate the EC2 instance after completing the experiment to avoid unnecessary AWS charges.
COMMANDS
Include the commands used in the Experiment.

## OUTPUT
<img width="1697" height="778" alt="image" src="https://github.com/user-attachments/assets/4884b1f1-e4a6-48e5-bef9-0a21b278cee0" />
<img width="1023" height="442" alt="image" src="https://github.com/user-attachments/assets/f3fd6a35-5660-4904-87f7-2304510083df" />
<img width="1030" height="463" alt="image" src="https://github.com/user-attachments/assets/aaaed228-0db1-4901-ad9e-b6fc8c41cfaf" />
<img width="1031" height="471" alt="image" src="https://github.com/user-attachments/assets/166564bb-0ef6-4503-a8a1-2c54c58ecdc6" />
<img width="1025" height="467" alt="image" src="https://github.com/user-attachments/assets/22afa098-3fb1-46d7-b7a2-c4384e1a60b2" />
<img width="1022" height="465" alt="image" src="https://github.com/user-attachments/assets/c629f94d-da8f-48f1-8118-72bdaf820b94" />
<img width="982" height="376" alt="image" src="https://github.com/user-attachments/assets/26b1c8f6-37e2-4dc8-a532-b0d5d3bbf28b" />

## RESULT

This experiment provided hands-on experience with Amazon EC2 by demonstrating how to launch, connect, manage, and monitor a virtual server in AWS. It helped in understanding the concept of Infrastructure as a Service (IaaS) and how compute resources can be provisioned and controlled on demand in the cloud.

