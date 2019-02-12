# connect-integration-CallVU
## Amazon Connect Integration for Callvu 
quickstart-callvu
This Quick Start deploys the CallVU architecture to your AWS Cloud environment. This multi-layered deployment is built for secured environment featuring separate subnets and advanced routing rules. Use this Quick Start as a building block for your deployments on AWS. You can choose to create a new VPC environment for your CallVU architecture or deploy it into your existing VPC environment. After you deploy the Quick Start, you can add other AWS services, infrastructure components, and software layers to complete your test or production CallVU environment on the AWS Cloud.
 

The integration creates the following:  
•	A highly available architecture that spans multiple Availability Zones.
•	2 Auto Scale Group instances running Amazon Elastic Compute Cloud (Amazon EC2) with Windows Server 2016, to host the CallVU core services and web applications.
•	An Amazon Relational Database Service (Amazon RDS) for SQL Server DB instance to synchronize the traffic between the private and public subnets; to store CDRs for reporting services
•	An Amazon Simple Storage Service (Amazon S3) bucket for storing CloudTrail files.
•	Lambda function as an interface to the digital engagement platform
•	SNS client for sending text messages

To integrate CallVU’s Digital Engagement Platform with Amazon Connect  
•	Step 1:	Sign up for an AWS account, if you don't already have one.
Getting an account will automatically sign you up for Amazon Connect and all other AWS services.  
•	Step 2:	Create a new Amazon Connect instance for the integration, or use an existing instance.  
•	Step 3:	Deploy the integration.

Complete the parameter fields. Deployment takes about an 1 hours and 30 minutes. You can deploy the Quick Start in all AWS Regions with Amazon Connect support (N. Virginia, Oregon, Sydney, Frankfurt) and Ohio.
•	Follow the instructions in the AWS Visual Connect Manual to create your own Visual IVR.
 

