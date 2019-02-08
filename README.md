# Azure Core Enablement and Security Control Plane
Azure Control Plane In-A-Box  ETA April 2019 for first workloads (Core Services and Virtual Machine) and May 1st 2019 for all 5 of the top priority workloads. 
1. Core Services (networking, security, etc)
1. Virtual Machine (Windows and Linux) 
1. To Be Defined
1. To Be Defined
1. To Be Defined

## Problem Statement
There are a massive number of companies adopting Azure that are required to implement infrastructure in a secure way.  Azure as a platform is very secure but the security of any system is only as strong as the weakest link.  It is a huge challenge for companies to understand what they need to do to deploy resources securely into Azure while meeting regulatory compliance and preventing mistakes or bad actors from compromising parts of the system.  The time it takes to do this is often measured in months even with full teams working on the solution.  We (all Microsoft customers) need an easy onramp to put workloads into Azure and make sure guard rails and remediations are implemented to make sure they stay secure and compliant.  Additionally, guidance is needed on compliance monitoring and where to go to frame the requirements for onboarding to cloud services and Azure. 

Our current plan is to leverage Azure Policy Samples https://github.com/Azure/azure-policy and create additional policies needed by many companies as a "best practice" or many needed by compliance regulations. Later (Phase II) we will add Blueprint and perhaps Custodian to the mix.

## Project Goals
* Auto-deployment of Control Plane Security Policies MVP/Proof of Concept – 5 Workloads to start.  First workload (currently in planning) is Windows Virtual Desktop running on Azure.  This workload will include all additional service needed to run this workload (storage, networking, etc) so when the workload is deployed, all dependent components are also deployed in a compliant way.
* Auto-deployment of infrastructure for testing to confirm proper configuration of security policies
* Allow user to *select* and customize policies for workload(s) they wish to deploy. (Self-Service Portal)
* Provide options to easily modify standard/default options on the fly
* Provide a way to *save* configuration so it can be restored, tweaked and run again
* Hack-in-a-box: Instructions and resource to run a 5-day hack where the outcome is 2-3 workloads running securely in Azure with best practices and policies implemented
* Inspire and recruit community development efforts
* Leverage existing Open Source Projects as much as possible
* Leverage Best Practices https://aka.ms/MyASIS https://docs.microsoft.com/en-us/azure/architecture/cloud-adoption/overview

## Next Steps
* Build out project design document 
* Create Tracking Project 
* Collect Education resources
* Create wireframe 
* Create Azure DevOps Project 
* Create Storyboards (Dan, Tommy & Gil)
* Create GitHub Project Repo (Dan)
* Build Backlog
* Decide on language(s)  PowerShell + … (Python?)
* Recruit vTeam

## 1 Core Services
1.  Azure Subscription	
1.  Azure Resource Group
1.	Azure Policy Service
1.	Azure Management Group & Role Based Access (RBAC)
1.	Key Vault
1.  Azure Application gateway
1.	Virtual Network
1.	Azure Blob Storage 
1.	Azure Table Storage
1.	Managed Disks
1.	Network Security Group
1.	Azure DNS
1.	Azure AD
1.	Express Route
1.  Windows Virtual Machines/Linux Virtual Machines

## 2 Virtual Machine Workload 
1.	Azure Application gateway
1.	Azure Policy Service
1.	Azure Management Group & Role Based Access (RBAC)
1.	Key Vault
1.	Virtual Network
1.	Azure Blob Storage
1.	Managed Disks
1.	Network Security Group
1.	Azure DNS
1.	Azure AD
1.	Windows Virtual Machines/Linux Virtual Machines

## 3-5 To Be Determined

## Owners 
Tommy Patterson, Dan Stolts

## Contributors  
* Gil Isaacs
* Stefan Gordon
* Your Name GOES HERE!!! PLEASE VOLUNTEER  send email with your github id and skills to dstolts@microsoft.com

## Help Needed
1. Python3 Developer
1. PowerShell Developer
1. Azure CLI Developer
1. Blog Post Writers - Story Tellers that can take a single challenge; sift through the facts and create a sucinct and easy to follow solution.
1. Policy Creator - Create Azure Policies (easy to learn if you do not already know how)
1. ARM Template Authors - Create and Test ARM Templates
1. DevSecOps Leadership / Coaching
1. Azure DevOps (product) experts - Manage backlog, create pipelines, Create tests, etc. 
1. Azure systems monitoring and auditing - compliance, audit and DecSecOps in general with monitoring
1. If you have these or other skills you think may be helpful, please reach out to dstolts@microsoft.com
