# Day 1 of Terraform Learning path

Before starting with Terraform it is worth to mention what is the logic behind the IaC (Infrastructure as Code). 

>"Infrastructure as Code (IaC) is the process of configuring and managing the infrastructure through a descriptive model. It is all about treating your infrastructure configuration and provisioning in the same way you treat your application source code. The configuration modules are typically stored in version control systems in very well-documented code formats which provides greater accuracy, reduces errors, and increases speed and consistency.

>IAC is one of the most important DevOps practices used in conjunction with continuous delivery. The benefits that lead many businesses to migrate to IAC are changeless infrastructure, an increase in the speed of delivery, scalability, cost savings, and risk mitigation.
IaC allows DevOps teams to use different tools and approaches to automatically control and customize the required infrastructure, instead of manually configuring the servers and operating systems. With the increase in the number of production and delivery cycles, the use of Infrastructure as Code (IaC) tools has changed the way software engineers design, test, and release their applications.

>Automation tools that promote the IaC best practices are necessary to make the process of building and configuring the infrastructure more competitive and effective, reducing the costs and effort involved." 
 
><cite> -- [NexaStack](https://www.nexastack.com/blog/best-iac-tools)<cite>


## Advantages of Infrastructure as Code
- Automated deployment
- Repeatable process
- Consistent environment (such as, production, staging, dev etc.)
- Reusable components
- Self-documented infrastructure architecture

HashiCorp Terraform is the most popular and open-source tool for infrastructure automation. It helps in configuring, provisioning, and managing the infrastructure as code. With terraform, you can easily plan and create IaC across multiple infrastructure providers with the same workflow. It uses the declarative approach to define the required infrastructure as code. Terraform allows users to have a pre-execution check to validate whether the configurations meet the result expectations or not, before updating or provisioning the infrastructure. It enables users to have their desired infrastructure across multiple cloud providers through a single and consistent CLI workflow. You can easily provision different environments using the same configuration and manage the full lifecycle of your desired infrastructure; thus reducing human errors and increasing automation in the infrastructure provisioning and management process.
