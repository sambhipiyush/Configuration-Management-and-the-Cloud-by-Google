# Configuration Management and the Cloud by Google on Coursera

<p align="center">
  <a href="javascript:void(0)" rel="noopener">
 <img width=200px  src="google_logo-preview.jpg" alt="google_logo-preview"></a>
</p>

#### Instructor(s) : 

## About this Course

In this course, you’ll learn how to apply automation to manage fleets of computers. You’ll understand how to automate the process for deploying new computers, keeping those machines updated, managing large-scale changes, and a lot more. We'll discuss managing both physical machines running in our offices and virtual machines running in the Cloud.

We'll start by looking into an automation technique called configuration management, which lets you manage the configuration of our computers at scale. Specifically, you'll learn how to use Puppet, the current industry standard for configuration management. We'll look at some simple examples, and then see how we can apply the same concepts to more complex cases. You’ll be a Puppet-master in no time!

Later on, you'll expand your automation skills by understanding how to use the Cloud to help scale your infrastructure. You'll check out some best practices for handling hundreds of virtual machines running in the Cloud and troubleshooting them when things don't go according to plan.

## Syllabus

### WEEK 1

* **Key Concepts**
	* Understand the definition of working at scale and how automation is an essential tool
	* Understand the difference between unmanaged and managed configuration systems
	* List the benefits of infrastructure as code
	* Understand what Puppet is and how Puppet facts work
	* Understand what Puppet resources and classes are
	* Define the principles of configuration management


#### Module 1: Automating with Configuration Management

In this module, you’ll be introduced to the concept of automation at scale and how it can be successfully achieved. You’ll learn what it means to work at scale and how automation is needed to scale effectively. Next, you’ll be introduced to configuration management. You’ll learn the differences between unmanaged and managed configuration management. Then, you’ll dive into infrastructure as code and learn about the benefits it brings, like making your fleet of nodes more reliable and repeatable. This is a major benefit when managing systems at scale. \
\
In the next lesson, you’ll be introduced to Puppet. You’ll learn how to apply basic configuration management and how Puppet agents and masters interact with each other. Next, you’ll do a rundown of Puppet resources and classes. You’ll learn how resources are basic units for modelling your configurations and how classes are a collection of resources used to achieve a single goal. The final lesson will introduce you to the building blocks of domain-specific language. You’ll learn what Puppet facts are and how it uses a program called facter to analyze, store and gather this information. Your final lesson will cover the driving principles of configuration management. You’ll learn about declarative, procedural, and idempotent principals and how they differ from each other.

**Graded:** Qwiklabs Assessment: Debugging Puppet Installation : __Weightage__ 25%

### WEEK 2

* **Key Concepts**
	* Deploy and run Puppet locally
	* Create, modify, and update Puppet rules
	* Understand the concepts of public key infrastructure and secure socket layer
	* Understand the difference between production and testing environments
	* Explore how canaries and development environments are helpful when deploying changes
	* Understand the benefits of multiple environments


#### Module 2: Deploying Puppet

In this module, you’ll dive into deploying Puppet on your local machine. Once you’ve completed that task, you’ll start creating and applying Puppet rules, managing resource relationships, and organizing your Puppet modules, which are a collection of manifests and associated data. Next, you’ll learn about Puppet nodes and node definitions and how they’re used to apply rules to your fleet. Then, you’ll dive into the Puppet certificate infrastructure, which explores the logic behind how the server can trust that a client is really who it claims to be. This topic will introduce the concepts of public key infrastructure and secure socket layer, which can ensure the clients can be trusted. Once you’ve understood these concepts, you’ll get to see a Puppet deployment in action! \
\
Your final lesson will center on updating, modifying, and testing manifests that you’ve deployed to your fleet. You’ll explore Puppet parser validate commands that will allow you to check the syntax to ensure it's correct. Next, you’ll explore the difference between production and testing environments, and how you can safely rollout changes to the testing environment to catch any errors. You’ll also learn about development environments and how you can siphon part of your fleet to an early-adopters or canary track to roll out changes, modification, or updates to that subset of machines.

**Graded:** Qwiklabs Assessment: Deployment Using Puppet : __Weightage__ 25%

### WEEK 3

* **Key Concepts**
	* Understand and define SaaS, PaaS, and IaaS
	* Understand the concept of scaling in the cloud and the different ways of scaling
	* Explain what lift and shift means when migrating to the cloud
	* Deploy an instance in the cloud
	* Understand the difference between auto scaling and load balancing
	* Differentiate between orchestration and automation
	* Define the concept of Infrastructure as Code (IaC)


#### Module 3: Automation in the Cloud

In this module, you’ll learn about cloud services and the different types of cloud services, like SaaS, PaaS, and IaaS. Next, you’ll learn about scaling in the cloud and how to modify the capacity of your service. You’ll learn about horizontal and vertical scaling, which then ties into automatic versus manual scaling. Next, you’ll explore how much control you have over your system, depending on whether you choose SaaS, Paas, or IaaS, and assess which one is right for your business. You’ll rundown the options available to migrate your business to the cloud using strategies like lift and shift. \
\
In the next lesson, you’ll learn how to manage instances in the cloud by creating one! You’ll explore the different options available, like regions, machine types, and lots more. Then, you’ll look into customizing and templating virtual machines to enable you to deploy them at scale. Our final lesson will explore the concept of automating cloud deployments. You’ll learn about load balancers, which ensure that each node receives a balanced number of requests, as well as autoscaling, which shuts nodes on and off, as needed. Next, you’ll learn about orchestration and how orchestration and automation differ. Last up, you’ll learn about infrastructure as code (IaC), or machine readable configuration files that automate configuration management.

**Graded:** Qwiklabs Assessment: Create VM template and Automate deployment : __Weightage__ 25%

### WEEK 4

* **Key Concepts**
	* Understand and explain the different types of storage available
	* Explain the difference between round robin DNS and sticky sessions
	* List the different types of integration testing that are available
	* Understand and explain the concept of SLAs
	* Troubleshoot and debug a system without being physically present
	* Understand what a rollback is and how they can help in a system failure
	* Understand how primary and secondary instances can help in a disaster recovery situation


#### Module 4: Managing Cloud Instances at Scale

In this module, you’ll learn all about storing data in the cloud. You’ll rundown the different types of storage available, like block storage and object storage, and how they differ. You’ll explore load balancing further and dive into some load balancing techniques, like round-robin DNS and sticky sessions. Next, you’ll dive into change management, including the different ways to test your changes and how to push them. You’ll explore different testing methods, like unit tests and integration tests. You’ll also cover continuous integration, the use of continuous deployment, and how to apply A/B testing. Next up, you’ll look at some errors you might encounter along the way, like quotas or limits, and how best to avoid or prepare for these. \
\
In the next lesson, you’ll get an understanding of monitoring and altering, and review some systems that offer it. You’ll then dive into the concept of SLA’s and how to set achievable ones. Next, you’ll look at basic monitoring in GCP, and create altering policies, set up conditions, and choose aggregators to manage the data. The last lesson will explore troubleshooting and debugging our systems. You’ll learn how to troubleshoot and debug remotely, understand. techniques for how to identify where the failure is coming from, and how to recover from a failure when it strikes.

**Graded:** Qwiklabs Assessment: Debugging Cloud Deployment : __Weightage__ 25%

#
#
#### ***Kudos!!!***

Warm Regards, \
Piyush Sambhi \
Email: piyush.sambhi07@icloud.com \
Git URL: https://github.com/sambhipiyush
