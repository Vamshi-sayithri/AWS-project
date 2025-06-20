# Secure VPC Set up with EC2 instances Aws Project
Project:

Design and configure a VPC: Created a VPC with custom IP ranges. Set up public and private subnets. Configured route tables and associate subnets.

Implemented network security: Setting up network access control lists (ACLs) to control inbound and outbound traffic. Configured security groups for EC2 instances to allow specific ports and protocols.

Provision EC2 instances: Launched EC2 instances in both the public and private subnets. Configured security groups for the instances to allow necessary traffic. Created and assign IAM roles to the instances with appropriate permissions.

Networking and routing: Setting up an internet gateway to allow internet access for instances in the public subnet. Configured NAT gateway or NAT instance to enable outbound internet access for instances in the private subnet. Created appropriate route tables and associate them with the subnets.

SSH key pair and access control: Generated an SSH key pair and securely store the private key. Configured the instances to allow SSH access only with the generated key pair. Implemented IAM policies and roles to control access and permissions to AWS resources.

Test and validated the setup: SSH into the EC2 instances using the private key and verify connectivity. Test network connectivity between instances in different subnets. Validate security group rules and network ACL settings.

By implementing this project, i have gain hands-on experience in setting up a secure VPC with EC2 instances, implementing networking and routing, configuring security groups and IAM roles, and ensuring proper access control. This project will provide a practical understanding of how these AWS services work together to create a secure and scalable infrastructure for our applications.
