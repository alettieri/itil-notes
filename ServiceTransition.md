# Service Transition

Time to deliver what has been designed. Receive [Service Design Package (SDP)](ServiceDesign.md#service-desing-package) and bring it into the Operational Stage.
This is the time adjustments will need to be made based on Design changes due to business circumstances, assumptions or requirement changes.

* Majority of IT projects do not yield desired results/outputs.
* Near 80% of incidents are caused by failed changes and activities within IT.

### Objectives

* Planning & managing changes
* Manage risk
* Deploy releases
* Set expections and ensure Business __Value__
* Provide Knowledge and information about service

> Change Management

### Scope

* New or changed services
* Service retirement
* Transfer of Services between Service Providers
* Change of service management capabilities

> Transfer of Services between service providers

### Value to the Bussiness - Slide 5

Business is in constant change

Service Transition provides:

* More accurate estimations for projects
* Clear way of working

![Service Transition Graph](assets/service-transition.png)

## Technology and Architecture in Service Transition

__ON TEST__

* Service Knowldege Management
* Configuration Management System (CMSDB)

> Part of Knowledge Management System
>
> Store everything about CI

### Process

* Change Management
* Service Asset and Configuration Management
* Release and Deployment Management
* Service Validation and Testing
* Change Evaluation
* Knowledge Management
* Transition Planning and Support

Design &rarr; __Transition__ &rarr; Operation


## Change Management

* Respond to customer's changing business requirements while maximizing value and reducing incidents, disruption and re-work
* Ensure changes are recorded and evaluated
* Changes are prioritized, planned, tested, implemented, documented and reviewed
* Ensure all changes to configuration items are recorded in Configuration Management System CMS
* Optimize overall business risk - it is correct to minimize business risk.

### Scope

* Change management covers all Changes

> Change Management Touches everything

## Objectives

All changes are:

* Recorded + Evaluated
* Prioritized
* Authorized/Rejected
* Planned
* Tested
* Implemented
* Documented
* Reviewed

## Concepts

### Service Change

Addition, MOdification or Removal of a service component and its associated documenation.

> Not every hange is important, but every improvement is a change

### Request for Change (RFC)

* Formal request for a service change
* Issued by anyone involved
* Paper based, email, self-help tool

### Change Proposal

Reserved for significant/highlevel changes.

Normally created by service Portfolio Management process and is passed to Change Management for authorization. 

> Back to [Service Strategy](#ServiceStrategy.md)

__Should Include:__
* Description of new, changed or retired service including Business outcomes and warranty + utility(value) to be provided
* What is the business case, including risks, issues and alternatives, budget and financial value

> What is the value we're going to get out of it?

### Scope

Can come from different tiers:

* Strategic
* Tactical
* Operational

### Types of Requests and Changes

__On Test__

#### Types of Requests

##### Normal Change
##### Standard Change
##### Emergency Change

> ####### Who can submit an RFC?
> Anyone source involved Service Management lifecycle stages of services

### Activities - Slide 17 &larr;

__On Test__

### Seven Rs of Change Management

__On Test__

* Raised
* Reason
* Return
* Risks
* Resources
* Responsible
* Relationship

### Planning and Scheduling

#### Change Schedule
Authorized changes with proposed implementation date

#### Projected Service Outage (PSO)

* Predict downtime.

> Gives you a way to mediate breeches in Service Plan??

#### Change Process Models

* Need an exit plan

### Authorizing Change - Slide 20

### Change Advisory Board (CAB)

Body that exists to __support__ the authorization of changes and to assist Change Management in the assessment and priortization of changes. 

Members:

* Customer
* User Manager
* User Group
* Application Devs
* Specialist/Tech Consultant
* Services and Operations
* Third Partices

### Review and Close Change

Change Review should:

* Meet objectives
* Users, customers are content
* Side effect
* Resources consumption
* Time and Cost

### Roles

#### Change Manager

Main authority that has the final say in Authorizing a Change. Members (CAB or ECAB) are ultimately an advisory body to the Change Manager.

### Interfaces within Service Management

Pretty much everything. 

* Process Improvements via Change Management

### Metrics

Judging the effectiveness.

Measurements should link back to business goals, cost and service availability

* Volume of change
* Frequency of change
* Ratio of accepted to rejected
* Time to execute

### Challenges

* Change in culture
* Bypassing process
* Close relationship with Serviec sset and Configuation Management





## Service Asset and Configuration Management (SACM)

### Roles

#### Service Asset Manager

Responsible for Asset Management System including the policy, plan, process, tols and reports

#### Configuration Manager

Responsbile for Configuration Managerment System

> Updates DB

### Transition Planning and Support

Provide overall planning for service transtions, coordinate resources that they require

Plan and coordinate the resources
Establish new or changed services into supported environments within the predicted cost, quality and time estimeates

Comprehensive plans

### Scope

* Coordinate efforts to enable mulptile transitions to be managed at the same time
* Priortize conflicting requirements
* Plan budget resources needed to fulfil future requirements for service transition

* Review and improve performance of transition
* Ensure service transitions are coordinated


## Release and Deployment Management

Define and agree deployment plans

* Ensure integrity of release package
* Record and track all release packages in [Definitive Media Library (DML)](#definitive-media-library-dml)
* Manage stakeholders
* Check delivery of Utility and Warranty (Value)
* Manage reisks
* Ensure knowledge transfer
* Package, build, test and deploy releases
* Establish services as described in Service Package
* Hand over services to operations
* Includes all configuration items

> ####### Definitive Media Library (DML)
 Records all of our software, licenses and documentation

## Concepts

### Release
Collection of hardware, software, documentation, processes or other components

> Not all releases are contained in DML or stored in DML. Software and Documentation would be stored in DML. 

### Release Unit
Components of an IT service that are normally released together

### Release Package/Release Design
One or more release units to upgrade from as-is to to-be situation

> Firm images are a good example

### Release Approaches

* Big Bang
	* Push out to everyone at once
* Phased
	* Push to small group of user base at a time
* Push
	* Administratively push changes
* Pull
	* Allow clients to pull changes
* Automation
	* Processing all of the above
* Manual

### Four Phases - Slide 37

__On Test__

[Change Management](#change-management) oversees and authorizes all of Relase Management.

* Release and deployment planning
* Release build and test
* Deployment
* Review and close

### Release Policy

Should be defined for one or more services:

* Unique identification, numbering and naming conventions
* Roles and Responsibilities at each stage
* Expected frequency for each type of release
* Exit and entry criteria and authority for acceptance of the release into each Service Transition stage

#### Types - Slide 39

* Major Release
* Minor Release
* Emergency Release
	* [Known Errors](#ServiceOperations.md)

### Roles

#### Release and Deployment Manager

Plann, design, build, configure and test all software and hardware for Relase Package

#### Release Packaging and Build Manager
#### Deployment Staff
#### Early Life Support

### Release and Deployment Model

Include:

* Approach
* Processes
* Procedures
* Resources

Define:

* Structure
* Environments
* Roles





## Knowledge Management

Improve quality of management decision-making 

### Objective
Enable the service provider to be more efficient and improve quality of service, increase satisfaction and reduce cost of service.


> KM - There to support decision making


### Data Information Knowledge Wisdom DIKW Model - Slide 42

__On Test__

> It's important not to make decisions on bad knowledge. 

Data is stored in traditional database, like a CMDB. Information can be found as the Configuration Management System (CMS). Knowledge is stored in the Service Knowledge Management System (SKMS). Wisdom can be managed and stored or managed by a tool.

### Service Knowledge Management System - Slide 44

