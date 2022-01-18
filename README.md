# Terraform learning

Before starting with Terraform it is worth to mention what is the logic behind the IaC (Infrastructure as Code). 

>"Infrastructure as Code (IaC) is the process of configuring and managing the infrastructure through a descriptive model. It is all about treating your infrastructure configuration and provisioning in the same way you treat your application source code. The configuration modules are typically stored in version control systems in very well-documented code formats which provides greater accuracy, reduces errors, and increases speed and consistency.

>IAC is one of the most important DevOps practices used in conjunction with continuous delivery. The benefits that lead many businesses to migrate to IAC are changeless infrastructure, an increase in the speed of delivery, scalability, cost savings, and risk mitigation.
IaC allows DevOps teams to use different tools and approaches to automatically control and customize the required infrastructure, instead of manually configuring the servers and operating systems. With the increase in the number of production and delivery cycles, the use of Infrastructure as Code (IaC) tools has changed the way software engineers design, test, and release their applications.

>Automation tools that promote the IaC best practices are necessary to make the process of building and configuring the infrastructure more competitive and effective, reducing the costs and effort involved." 
 
><cite> -- [NexaStack](https://www.nexastack.com/blog/best-iac-tools)<cite>

HashiCorp Terraform is the most popular and open-source tool for infrastructure automation. It helps in configuring, provisioning, and managing the infrastructure as code. With terraform, you can easily plan and create IaC across multiple infrastructure providers with the same workflow. It uses the declarative approach to define the required infrastructure as code. Terraform allows users to have a pre-execution check to validate whether the configurations meet the result expectations or not, before updating or provisioning the infrastructure. It enables users to have their desired infrastructure across multiple cloud providers through a single and consistent CLI workflow. You can easily provision different environments using the same configuration and manage the full lifecycle of your desired infrastructure; thus reducing human errors and increasing automation in the infrastructure provisioning and management process. Terraform is an open-source infrastructure as code tool that allows you to manage hundreds of cloud services to use a uniform CLI approach. Terraform uses declarative configuration files to codify cloud APIs.


This repo contains test scripts and tutorials used during my learning journey of Terraform. 


## Sources that I am using
### Beginner
- [PluralSight Terraform Beginner Guide](https://app.pluralsight.com/library/courses/getting-started-terraform/table-of-contents)

### Intermediate
- [PluralSight Terraform Deep dive course](https://app.pluralsight.com/library/courses/terraform-deep-dive/table-of-contents)

### HashiCorp Terraform Associate exam preparation
- [HashiCorp Terraform Associate Certification Course by FreeCodeCamp](https://youtu.be/V4waklkBC38)
