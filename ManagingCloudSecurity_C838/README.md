# Managing Cloud Security C838
# 4042.4.1 Secure Cloud Data Solutions
Secure cloud data solutions to safeguard data, personally indentifiable information, and information resources. 

## Lesson 1 - Architecture concepts, including foudational concepts of cloud computing, cloud evolution, definitions, and busiess requirements. 
### Cloud Characteristics
- Broad Network access
- On-deman self-service
- Resource poooling
- Rapid elasticity
- Measured or "metered" service

### NIST 800-146 Cloud Computing Definition
- The official NIST definitions of cloud computing says, "Cloud Computing is a model for enabling ubiquitous, convenient, on-demand network access to a shared pool of configurable computing resources (e.g., networks, servers, storage, applications, and services) that can be rapidly provisioned and released with minimal management effort or servie provider interaction".

- Broad network access means services are consitently accessible by standar means, such as the suse of a web browser to access a Software as a Service (SaaS) application regardless of the user's location or choice of computer OS, browser, and so on. 
- On-demand self-service refers to the model that allows customers to scale their compute and/or storage needs with little or no inervention from or piror communication with the provider. The services happen in real time. 
- Resource pooling is the characteristic that allows the cloud provider to meet various demands from customers while remaining financially viable. The cloud provier can make capital investments that greatly exceed what any single customer could provide on their own and can apportion the resources as needed so that the resources are not under-utlized. 
- Rapid elasticity allows the customer to grow or shrink the IT footprint as necessary to meet operational needs without excess capacity. 
- Measured or metered service simply means that the customer is charged for only what they use and nothing more. This is much like how a water or power company charges.

### Business Requirements 
The IT department is not a profit center; it provides a support function. 
- A network security administrator has to know what type of traffic to expect based on the business of the organization. 
- The intrusion detection analyst has to understand what the organization is doing, how business activites occur, and where teh business is operating to better understand the nature and intensity of potential external attacks and how to adjust baselines accordingly. 
- The security architect has to undersand the various needs of hte organizational departments to enhance their operation without compromizing their security profile. 

### Functional Requirements 
Those performance aspects of a device, process, or employee that are necessary for the business task to be accomplished. Example: A salesperson in the field must be able to connect to the organization’s network remotely.

### Non-Functional Requirements
Those aspects of a device, process, or employee that are not necessary for accomplishing a business task but are desired to expected. Example: The salesperson's remote connection must be secure. 

## Existing State
A true evaluation and understanding of the business processes, assets, and requirements is essential. 
- Interviewing functinoal managers
- Interviewing users
- Interviewing senior management
- Surveying customers
- Collecting network traffic 
- Inventorying assets 
- Collecting financial records
- Collecting insurance records
- Collecting marketing data
- Collecting regulatory mandates

After sufficient data has been colelcted, a detailed analysis is necessary. This is the point where a business impact analysis (BIA) takes place. 

## Quantifying Benefits and Opportunity Cost
Once you have a clear picture of what your organization does in terms of the lines of business and processes, you can get a better undersstanding of what benefits the organization might derive from cloud migration as well as the costs associated with the move. 

#### Reduction in Capital Expenditure
If your organziation buys a device for use in its internal environment, teh capacity of that device will either be fully utilized or (more likely) not. If the device is used at its fullest capacity, the it's quite likely that the function for which it is needed may experience inefficiencies at some point. 

#### Reduction in Personnel Costs
For most organizations (other than those that deliver IT services), managing data is not a core competency, much less a proitable line of business. Data management is also a specialized skill, and people with IT experience and training are relatively expensive compared to other departments. The personnel required to fulfill the needs of an internal IT environment represent a significant and disproportionally large investment.

####
Reduction in Operational Costs
Maintaining and administering an internal environment takes agreat deal of effort and expense. When an organization moves to the cloud, the cost becomes part of the price of the service, as calcualted by the cloud provider. Therefore, costs are lumped in with the flat-rate cost of the contract and will not increase in response to enhanced operations. 

## Cloud Evolution, Vernacular, and Models
The arrival of the cloud and its related technology has provided a lot of advantages. To incorporate the cloud and these advantages, it is necessary to understand new terminology and how it relates to the terminology of traditional models.

### New Technology, New Options
Ten to fifteen years ago the idea of handing off your data to a third party was insane. Today a combination of technnological capabilities and contractual trust make cloud computing not only appealing but almost a foregone conclusion, in terms of financial viablity. 
- Elasticity: Rather than constantly purchasing computers, servers, data storage systems, and other resources and internally maintaining their infrastructure, an organization can contract with a cloud vendor. 
- Simplicity: Proper cloud implementations allow a user to seamslessly use the service without frequently interacting with the cloud service provider. 
- Scalability: In general, increasing or reducing services can be more easily, quickly, and cost-effectively accomplished than in a non-cloud environment. 

## Cloud Computing Service Models
Cloud service are often offered in terms of three general models, based on what the vendor offers and the customer needs and the reposibilities of each according to the service contract. 
- SaaS: Software as a Service 
- PaaS: Platform as a Service
- IaaS: Infrastructure as a Service

## Infrastructure as a Service (IaaS)
The most basic of cloud service offerings, IaaS allows the customer to install all software, including operating systems, on hardware housed and connected by the cloud vendor. 

## Platform as a Service (PaaS)
PaaS contains everythnig included in IaaS with the addition of OSs. The cloud vendor ususally offers a selection of Oss so that the customer can use any or all of the available choices. 

## Software as a Service (SaaS)
SaaS includes everything in IaaS and PaaS with the addition of software programs. The cloud vendor becomes responsible for administering, patching, and updating this software as well. The cloud customer is basically only involved in uploading and processing data on a full production environment hosted by the provider. 

## Cloud Deployment Models
In addition to viewing cloud offerings in terms of what levels of service are involved, another perspecitive has to do with ownership. You'll be expected to know the facets of both sets of models. 

## Public
The public cloud is what we typically think of when discussing cloud providers. The resources are owned and operated by a vendor as sold, leased, or rented to anyone. 

## Private
A private cloud is typified by resources dedicated to a single customer, no other customers will share the underlying resources. Therefore, private clouds are not multitenant environments. 

## Community 
A community cloud features infrastructure and processing owned and operated by an affinity group; disparate pieces might be owned or controlled by individuals or distinct organizations, but they come together in some fashion to perform joint tasks and functions. 

## Hybrid
A hybrid cloud contains elements of the other models. For example, an organization might want ot retain some private clouds resources but also lease some public cloud space as well. 

# Cloud Computing Roles and Responsibilities
#### Cloud service provider(CSP), or Cloud Provider or Provider
The vendor offering a cloud service
#### Cloud Customer 
The organization purchasing, leasing, or renting cloud services
#### Cloud Broker
A company that purchases hosting services from a cloud provider who then resells them to its own customers.
#### Cloud Access Security Broker (CASB)
A third-party entity offering independent identity and access management (IAM) services to CSP's and cloud customers, often as an intermediary. This can take the form of a variety of services, including single sign-on, certificate management, and cryptographic key escrow. 
#### Regulators (MOUNT UP) 
The entities that ensure organizations are in compliance with the regulatory framework for which they're repsonsbile. These can be government agencies, certification bodies, or parties to a contract. Regulations include the Health Information Portability and Accountability Act (HIPAA), the Graham-Leach-Bliley Act (GLBA), the Payment Card Industry Data Security Standard (PCI DSS), the International Organization for Standardization (ISO), the Sarbanes– Oxley Act (SOX), and so forth. Regulators include the Federal Trade Commission (FTC), the Securities and Exchange Commission (SEC), and auditors commissioned to review compliance with contracted or asserted standards (such as PCI DSS and ISO), among many others.

# Cloud Computing Definitions
#### Business Requirement 
An operational driver for decision-making and input for risk management
#### Cloud App (Cloud Application)
The phrase used to describe a software application accessed via the Internet
#### Cloud Architect
Subject matter expert for cloud computing infrastructure and deployment 
#### Cloud Backup
Backing up data to a remote, cloud based server 
#### Cloud Computing 
The use of computing, storage, and network resources with the capabilities of rapid elasticity, metered service, broad network access, and pooled resources 
#### Cloud Migration
The process of transitioning all or part of a company's data, applications, and services from on-site premises to the cloud
#### Cloud Portability
The ability to move applications and associated data between one cloud provider and another or between legacy and cloud environments
#### Cost-Benefit Analysis
This is comparing the potential positive impact of a business decision to the potential negative impact and weighing whether the two are equivalent or if the potential positive effect outweighs the potential negative. 
#### FIPS 140-2 
A NIST document that describes the process for accediting and cryptosystems for use by the US Federal Government
#### Managed Service Provider 
AN IT Service where the customer dictates both the technology and operational procedures, and an external party executes administration and operational support according to a contract
#### Multitenant
Multiple customers using the same public cloud 
#### NIST 800-53
A guidance document with the primary goal of ensuring that appropriate security requirements and controls are applied to all US federal government information in information management systems
#### Trusted Cloud Initiative (TCI) Reference Model
The TCI reference model is a guide for cloud providers, allowing them to create a holistic architecture that cloud customers can purchase and use with comfort and confidence 
#### Vendor Lock-In
Vendor lock-in occurs in a situation where a customer may be unable to leave, migrate, or transfer to an alternate provider due ot technical or nontechnical constraints
#### Vendor Lock-Out
Vendor lock-out occurs when a customer is unable to recover or access their own data due to the cloud provider going into bankruptcy or otherwise leaving the market

#### CIA TRIAD
- Confidentiality
- Integrity
- Availability


## Lesson 2 - Design requirements, including business requirements analysis, boundaries of cloud models, and design principles for protecting sensitive data.
# 4042.4.2 Secure Cloud Infrastucture
Validate security controls, disaster recovery plans, and continuity management plans to ensure a secure infrastructure for the protection and restoral of information resources. 
# 4042.4.3 Manage Cloud Operations
Secure and manage physical and virtual infrastructures for legal and secure cloud operations.
# 4042.4.4 Cloud Software Assessment 
Security in cloud software to improve security and define secure procedures.
# 4042.4.5 Critical Cloud Requirements
Manage Critical requirements of cloud architecture to build and run that infrastructure.
# 4042.4.6 Legal and Compliance Cloud Requirements
Legal and compliance requirements of cloud operations to protect the organization and ensure ethical behavior.
## Skills
- problem solving 
- communications
- critical thinking
- leadership
- innovation
- tenacity 
