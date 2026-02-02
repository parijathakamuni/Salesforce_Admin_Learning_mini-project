Client: Intelogik
Project Name: Skill Improvisation Program
Prepared by: Salesforce Administrator
Date of Document: 27-07-2025
Duration: 2-3 months
Version: 1.0





Final Document will include

Project Overview
Business Objective
Salesforce Features Used
Custom Objects & Fields
Record Types, Page Layouts, and Profiles
Automation Used (Flows, Validation Rules, Assignment Rules, etc.)
Reports & Dashboards
User Roles & Permissions
Screenshots or Diagrams
Deployment & Testing Notes

Table of Contents
Table of Contents	1
Project Work: Story 1	2
1. 1. Introduction	2
1.2. Client Requirements	2
1.3. Salesforce Solution Overview	2
1.4. Feature Mapping: Requirements vs Salesforce Capabilities	3
1.5. Architecture Diagram	3
1.6. Key Features to Implement	4
1.7. Project Timeline & Milestones	4
1.8. Tools & Platforms Used	4
1.9. Summary & Next Steps	4
Project Work: Story 2	4
2.1. Salesforce CRM Requirement Gathering Questionnaire	4
Project Work: Story 3	5
3.1. Requirement Review and Planning Preparation	5
3.1.1 Creating Table Details:	7
3.1.2 The Relationship between them	10
3.1.3 Creating Users in Salesforce	10
3.1.4 Creating Roles in Salesforce	12
3.1.5 Creating Profiles in Salesforce	13
3.1.6 Creating Role Hierarchy in Salesforce	14
3.1.7 Organization Hierarchy - Object access for profile	14
Project Work: Story 4	17
4.1. Data migration from Oracle to Salesforce	17
Project Work: Story 5	23
5.1. Data Cleaning Process: Student Master	23

Project Work: Story 1
1. 1. Introduction
This proposal outlines a Salesforce-based CRM solution tailored to Intelogik Company's business goals. The system will streamline operations, enhance productivity, and provide mobile-friendly access for users across locations.
1.2. Client Requirements
Customizable and scalable CRM solution
Flexible and easily customizable application
Cloud-based with no infrastructure maintenance
Pay-as-you-use pricing model
Remote accessibility across devices
Minimal IT infrastructure
Quick deployment with low-code tools
1.3. Salesforce Solution Overview
Salesforce offers a flexible and powerful CRM solution, with built-in tools to automate business
workflows, manage customer data, and access real-time analytics from anywhere. Its mobile readiness and AppExchange support make it ideal for fast deployment and growth.
1.4. Feature Mapping: Requirements vs Salesforce Capabilities

Client Requirement
Salesforce Capability
Customizable App
Lightning App Builder, Custom Objects
Access Anywhere
Salesforce Mobile App, Cloud Access
No Infrastructure 
100% Cloud-based SaaS
Pay-per-use
User-based licensing
Quick Deployment
Low-code tools, AppExchange integrations

1.5. Architecture Diagram
Below is a conceptual placeholder for a Salesforce architecture showing users, cloud services, and data flows. 
1.6. Key Features to Implement
✅ User Management
✅ Role-Based Security & Permissions
✅ Data Management
✅ Flows Automation
✅ Reports & Dashboards
✅ Deployment using Change set
✅ Mobile-Ready User Access
1.7. Project Timeline & Milestones
Week 1–2: Requirements & Planning
Week 3–4: Configuration & Customization
Week 5: Testing & Feedback Loop
Week 6: Final Deployment & Training


1.8. Tools & Platforms Used
Salesforce Lightning Platform
Flow Builder & App Builder
Change set for deployment
Dataloader
Google Docs / MS Word for Documentation
MS Excel
1.9. Summary & Next Steps
The Salesforce CRM solution meets Intelogik Company’s goals for scalability, flexibility, and mobility. We recommend proceeding with stakeholder approvals and scheduling the kickoff.
Project Work: Story 2
2.1. Salesforce CRM Requirement Gathering Questionnaire

What are the main business processes you want to manage or automate using Salesforce?
Who are the primary users of the system, and what are their roles?
What specific data do you want to track?
Do you already have any data in another system that needs to be migrated to Salesforce?
What reports or dashboards do you want to see regularly?
Do different users need different levels of access to data?
Are there any workflows or approval processes to be automated?
Do you need Salesforce to integrate with any third-party tools?
What is your preferred timeline for implementation and go-live?
How do you plan to handle training and user adoption?
Should the system send automatic notifications, alerts, or emails for specific actions?

Project Work: Story 3
3.1. Requirement Review and Planning Preparation

What business process do they want to execute on Salesforce?
Customer: We have been working in the training industry for a long time. We give IT courses training in online as well as offline modes. We have 300+ courses. We want our entire business process to be run on Salesforce. Right now, we are working on .NET software. We enter students’ details who enrol in the course. Fess paid and pending fees details. Trainer details as 

As well as related information. Also, we run a placement business for candidates in multiple countries. And we take some amount from candidates after placed.

How many users will use the Salesforce platform?
Customer: 5

How many departments will be using Salesforce, and details of department-wise members?
Customer: 
Training department (Harry)
Placement department (Robert)
Senior management department (Shekhar, John, Peter)

What are the roles of each user?
Customer:
1 user works in the CEO position (Shekhar)
1 user works in the training department as Training Coordinator (Harry)
1 user works in the placement department as Placement Coordinator (Robert)
1 user works in the academic department as Senior Manager (John)
1 user works in the placement department as Senior Manager (Peter)

How is the organization hierarchy?
CEO -> Sr Management Academic -> Training Department
CEO -> Sr Management Placement -> Placement Department

Which department/ users of the department will be able to access what data?
Shekhar: All the data of the company
Harry: Course details, Trainer's details, Batch details table, Fees details
Robert: Placement details, Vacancies details table
Peter: All data on placement
John: All data from training

Various types of business data will we be storing in Salesforce?
Customer: Above all data we will store

What are the different types of courses you want to sell?
Customer: Java, .NET, PHP, Salesforce, Oracle (Rest customer wants to add later)

What kind of services will you provide to students?
Customer: Training, Placement

What master data will you provide, like course details, Trainers' info, etc?
Customer: Course info, Trainer’s data, Marketing data, batch details

With all the above data, plan below things:
Table details
The relationship between them
Roles
Profile
Role Hierarchy
Object access for profile

And, all the needed data to take the final steps before execution
