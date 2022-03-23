---
layout: default
---


## [Understanding the basics of Chef](https://www.youtube.com/watch?v=04oITjdLtho)

[//]: #  There should be whitespace between paragraphs. We recommend including a README, or a file with information about your project.

## What Is Chef?
Chef is an automation tool that provides a way to define infrastructure as code. Infrastructure as code (IAC) simply means that managing infrastructure by writing code (Automating infrastructure) rather than using manual processes. It can also be termed as programmable infrastructure. Chef uses a pure-Ruby, domain-specific language (DSL) for writing system configurations. Below are the types of automation done by Chef, irrespective of the size of infrastructure:

* Infrastructure configuration
* Application deployment 
* Configurations are managed across your network


![](https://msystechnologies.com/wp-content/uploads/2018/04/chef.png) 

In Chef, Nodes are dynamically updated with the configurations in the Server. This is called Pull Configuration which means that we don’t need to execute even a single command on the Chef server to push the configuration on the nodes, nodes will automatically update themselves with the configurations present in the Server. My next blog on Chef Tutorial will explain the Chef architecture along with all the Chef components in detail.

Now, let us look at reasons behind the popularity of Chef.

## Chef Key Metrics

* Chef supports multiple platforms like AIX, RHEL/CentOS, FreeBSD, OS X, Solaris, Microsoft Windows and Ubuntu. Additional client platforms include Arch Linux, Debian and Fedora.
* Chef can be integrated with cloud-based platforms such as Internap, Amazon EC2, Google Cloud Platform, OpenStack, SoftLayer, Microsoft Azure and Rackspace to automatically provision and configure new machines.
* Chef has an active, smart and fast growing community support.
* Because of Chef’s maturity and flexibility, it is being used by giants like Mozilla, Expedia, Facebook, HP Public Cloud, Prezi, Xero, Ancestry.com, Rackspace, Get Satisfaction, IGN, Marshall University, Socrata, University of Minnesota, Wharton School of the University of Pennsylvania, Bonobos, Splunk, Citi, DueDil, Disney, and Cheezburger.


![ ](https://dl.cdn-anritsu.com/images/tm/solutions/mt1000a-05/mt1000a-5g-ecpri-01e.jpg?la=en-us) 

## Configuration Management
Don’t worry, there won’t be any heavy definition of Configuration Management in this blog :)

Let us understand Configuration Management this way – suppose you have to deploy a software on top of hundreds of systems. This software can be an operating system or a code or it can be an update of an existing software. You can do this task manually, but what happens if you have to finish this task overnight because tomorrow might be a Big Billion Day sale in the company or some Mega Sale etc. in which heavy traffic is expected. Even if you were able to do this manually there is a high possibility of multiple errors on your big day. What if the software you updated on hundreds of systems is not working, then how will you revert back to the previous stable version, will you be able to do this task manually? AF-course not!

To solve this problem, Configuration Management was introduced. By using Configuration Management tools like Chef, Puppet, etc. you can automate this task. All you have to do is to specify the configurations in one centralized server and accordingly all the nodes will be configured. It allows access to an accurate historical record of system state for project management and audit purposes. So basically, we need to specify the configurations once on the central server and replicate that on thousands of nodes. Configuration Management helps in performing the below tasks in a very structured and easy way:

![ ](https://intellipaat.com/blog/wp-content/uploads/2018/11/How-Chef-Works.png)

### I hope this was useful as IoT get deeper and deeper in our lifes.


```
Thank you readers, and wait for next week blog
For Contact e-mail me at ramirez368@hotmail.com

```
