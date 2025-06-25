**AWS Deployment and Service Models**

**Traditional Computing Model Vs Cloud Computing Model**
 
 ![image](https://github.com/user-attachments/assets/9d7919e3-8199-4936-8d11-eb3f3133bdad)

 ![image](https://github.com/user-attachments/assets/8ac70565-74b5-4ed2-aef9-59fe92a1d24e)

 
**1.	Traditional Computing Model**
•	The traditional computing model has physical servers and computers that need resources for installation and maintenance, which is more expensive.
•	We need technical experts to work with and maintain those physical servers and computers.
•	Here, the server is located at the UCW data center, Vancouver, and the dataset is stored in that HR operations environment in that location.
•	The privacy and accessibility of the dataset are controlled by the HR operations team.
**2.	Cloud Computing Model**
•	In the cloud computing model, 

**Cloud Deployment Models**
 
 ![image](https://github.com/user-attachments/assets/b98a0dc2-af42-47e8-a2b5-c50ea6801eff)

**1.	Private Cloud**
•	Private Cloud is similar to the traditional computing model, where we will have our own data center in our own location, but with a virtual server.
**2.	Public Cloud**
•	The virtual server is located in the AWS data center in the UCW account located in Virginia.
•	The dataset stored in the public cloud is not secure, and it can be accessed publicly.

![image](https://github.com/user-attachments/assets/8fc53ab0-469a-4d48-a2d4-246312d6e51e)

**3.	Hybrid Cloud**
•	In this model, there are two virtual servers, one located at the UCW data center and the other located at the AWS data center.
•	The confidential data will be stored in the server that is located at the UCW data center, and other data that is not confidential will be stored in the AWS data center.

![image](https://github.com/user-attachments/assets/e3485c47-44ed-4790-808b-3b9857bc6343)

**4.	Multi Cloud**
•	When the server is rented from more than one provider, then it is called multi cloud

![image](https://github.com/user-attachments/assets/67196ec0-e4b1-4443-9c56-8eeb6432b076)

**Cloud Service Model**
 
 ![image](https://github.com/user-attachments/assets/78464b97-1df0-4f6e-8d0b-818a2081566b)

 ![image](https://github.com/user-attachments/assets/064e6dc3-3a57-41f5-ae15-a4402a4b886c)

**1.	Infrastructure as a Service (IaaS):**
•	Here we are using only the infrastructure of AWS, that is, the physical server of AWS, which is located in Virginia, is used by the HR operations team of UCW to store data.
•	When we use infrastructure as a service from AWS, it is a general computer for which the HR operations team is responsible for creating the storage volume (EC2 and EBS), network interface (NIC), configuration of the Operating System (OS), and configuration of the CPU.
•	The HR operations team is responsible for the privacy of the dataset stored in the AWS server, and it can be accessed only by the HR operations team.
•	The privacy and accessibility of the dataset is taken care only by HR operations team at UCW.

**2.	Platform as a Service (PaaS):**
•	If we are getting platform as a service from AWS, it will provide infrastructure and platform as a service which is used by the professionals like developers and analysts of the operations team.
•	Here, the platform is designed specifically for the use of the HR operations team, such as AWS Glue, Athena, and AWS GlueDataBlue.
•	This service cannot be used by the end users, like the employees of the organization, who are not aware of this platform service and how to use these services.
•	The HR operations team will be designing the platform that is required for their operations, but the infrastructure design will be completely done only by the AWS operations team.
•	The privacy of the dataset is taken care by both AWS operations team and HR operations team. But the dataset is accessible only by the HR operations team

**3.	Software as a Service (SaaS):**
•	In SaaS, the infrastructure and platform layers are managed by the AWS operations team, and the software layer, which is the end service used and managed by the HR operations team.
•	The end-user software and websites are provided by the AWS operations team, which will be used by the HR operations team.
•	Both the AWS operations team and the HR operations team at UCW are responsible for the privacy and accessibility of the dataset.

**AWS Module 1 Knowledge Check**

 ![image](https://github.com/user-attachments/assets/818a9211-7b19-46b1-b32d-61c37435cd79)

**AWS Cost Analysis**

**Total Cost of Ownership**

The total cost of ownership is to compare the total cost of the traditional computing model and the total cost of the cloud computing model before migrating from traditional model. The total cost includes installation, service, maintenance, facilities, IT labor cost, network cost, and storage cost to have a data center in a traditional method. For cloud computing mode, we need to calculate based on the computing capacity, services, storage, and system traffic (Data Transfer). These estimations will be compared to find out how efficient it is to transfer from the traditional model to the cloud computing model. For AWS cloud computing, we can calculate the pricing using the AWS pricing calculator.
The transformation to AWS cloud computing has many benefits, such as pay for what you use, pay less when you reserve, and pay less when you use more and as AWS grows. It also has other hard benefits such as cost reduction in compute, storage, networking, security, hardware, and software, and soft benefits such as reuse of services and applications, increased developer productivity, improved customer satisfaction, efficiency, global reach, and time saving are also considered. 

![image](https://github.com/user-attachments/assets/820030f4-823b-4efa-9ab9-630789e0cb82)

**AWS Pricing Calculator**

****Price Calculated for Data Storage in Raw Bucket using AWS S3 Service**

![image](https://github.com/user-attachments/assets/bb1bdbba-f116-468c-acf9-d759cbe591e7)
 
**Price Calculated for Data Profiling and Cleaning using AWS Glue Service**
 
 ![image](https://github.com/user-attachments/assets/62ab247c-6d8c-4815-97eb-1dbe806cac02)

**Price Calculated for Data Analysis using AWS Athena service**


**AWS Support Plan**
 
 ![image](https://github.com/user-attachments/assets/d544bd50-0114-4915-aa8f-adbc52527421)

**AWS Module 2 Knowledge Check**

![image](https://github.com/user-attachments/assets/2a854508-bcd7-4e56-a0a8-c8addfe291d2)
 
**AWS Global Infrastructure**
AWS Global Infrastructure provides a flexible, scalable, reliable, and secure cloud computing environment that includes AWS Regions, availability zones, data centers, regional edge cache, and edge locations. Each region has multiple availability zones, which consist of discrete data centers that are designed for fault isolation. All availability zones are interconnected with high-bandwidth and low-latency networking to provide high throughput between the availability zones. 
AWS provides Points of Presence locations, which consist of Edge Locations and a smaller number of Regional Edge Caches that are used with Amazon CloudFront, which is a content delivery network (CDN). The Regional Edge Caches are used for infrequently accessed content.
 
 ![image](https://github.com/user-attachments/assets/e8cdc109-5233-40d9-8693-237df11332fa)

![image](https://github.com/user-attachments/assets/5df09a54-a30a-4c3d-bf1d-6e52e1c57526)

**AWS Module 3 Knowledge Check**
 
 ![image](https://github.com/user-attachments/assets/802613d6-66c0-49f4-81c6-d11467680d6b)

**AWS Identity and Access Management**

**Who is Responsible**
 
 ![image](https://github.com/user-attachments/assets/e2e607e1-9077-4d53-9d7c-7bd6495cd12f)

**AWS IAM Practice Lab 1:**

![image](https://github.com/user-attachments/assets/f1a7d3c2-08b5-44b5-abaf-a176fd922fcd)

**AWS Module 4 Knowledge Check**

![image](https://github.com/user-attachments/assets/4fcaf943-6c38-497d-bb98-e3b4d63ea693)

**Amazon VPC**
**Build Your VPC: Lab 2:**



