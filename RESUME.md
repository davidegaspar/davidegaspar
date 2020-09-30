# Davide Gaspar

*Source https://github.com/davidegaspar*

London, United Kingdom

Senior Software Engineer based in central London currently working in the Cloud Platform Team.

Strong belief in the DevOps culture, were diverse multi-skill teams build and run all their software, including Infrastructure, Testing, Observability and Security.

## Core Principles

Customer oriented, focused on delivery in a timely fashion with the right quality.

Not afraid of Ownership, and will pursue long term value over short term gain.

Seek diverse perspectives and operate at all levels.

Insist on the highest standards, hire and develop the best.

## Notable Projects

### Domain Driven Design (DDD)

After attending Domain-Driven Design Europe 2020 in Amsterdam, I have been reading the related books on the topic, and will undergo training in Q4 2020 (already booked).

### Labs @ CondeNast

In order to lower the barrier of entry and spread best practices across engineering, along with another colleague, pioneered a set of step by step guides to deliver field tested solutions for specific engineering problems.

Engineers can now, kickstart development quickly, implement "cookie cutter" solutions fast, and build on it. At the same time they own all the code and are able to run it without waiting for other teams. It's also a great way to learn software design patterns and best practices.

Currently our Labs cover topics like Deployment, Secrets and Infrastructure as Code, but topics like Observability and Migrations are in the works.

### Kubernetes Clusters @ CondeNast

Built several Kubernetes clusters around the globe in multiple regions, both fully managed and AWS EKS. These clusters serve both internal and external customers and run websites that serve millions of users like Vogue and GQ digital consumers. All the tooling needed for engineers is built in, like logging, metrics, auto scaling and failover systems.

### CircleCI Infrastructure @ CondeNast

CircleCI Enterprise serves 150+ engineers around the world.

Designed and built the supporting infrastructure with IaC, including DNS, Load balancing, Scaling, Zero Trust Authentication and Backup systems.

Responsible for maintenance and monitoring (SLOs), configuration, upgrades and engineer experience.

### AWS account provisioning @ CondeNast

Provisioned 20+ AWS accounts for markets and Hubs around the world. With the use of IaC (Terraform) via Pipelines (CircleCI), deployed Okta SSO integration, Cloud Governance tools (CloudHealth / Stealthwatch) and Terraform state storage and locking.

### Services and UI migration to AWS @ eFinancialCareers
Successfully helped migrate all our stack to AWS, by building a template micro service stack that ran Docker applications on EC2 using Terraform. All micro services now follow a standard Infrastructure Stack including WAF, ELBs/ALBs, CloudFront, Nginx, Docker, ASG/EC2, CloudWatch Metrics Alarms and Dashboards and Splunk logging. All micro services have a Pipeline (CodePipeline) complete with Github and Jenkins integration, that build, deploy and test each service. All micro services have a Runbook for On Call support.

### DNS Migration @ eFinancialCareers
Successfully migrated 6000+ eFinancialCareers DNS records to Route53 using terraform and created a suite of NodeJS scripts to run tests and batch updates.

### CloudFormation Templates @ DHI
Ongoing effort to build CloudFormation templates that solve common problems in the Organization. Including Artefact Store, CodeBuild Integration, Serverless logs in Splunk, Serverless metrics in InfluxDB, GitHub WebHook Integration, Secrets in Parameter Store and several Managed Policies.

## Experience

### CondeNast - London, UK - Dec 2018 to Present (WIP)

#### Senior Software Engineer @ Cloud Platform Team

- Part of a cross timezone, diverse, fully remote, Agile team.
- We serve around 200 Engineers globally in 11 markets and 3 Hubs.
- We provide multi-region AWS environments, Global Kubernetes Clusters, CircleCI, ELK Logging, Datadog Monitoring and Terraform for IaC, as well as custom tooling like APIs and CLIs written in Golang and NodeJS.
- Involved in the Incident Management process and On Call, participated in the investigation and resolution of incidents as well as correspondent post-mortems.
- **Team Mission:** Lead, educate, advocate the principles and practices of DevOps across all of CondeNast, Build tools, provide services and help teams to efficiently own the life-cycle of their applications, Consulting with teams through pairing to facilitate optimal use of the platform.
- **Edge Services Management:** Owner of CDN (Fastly), responsible for TLS Certificates management, IaC Best practices (Terraform), and Engineer access.
- **DNS Management:** Owner of root zones domain registration, responsible for zone delegation and IaC Best practices (Terraform).
- **Consulting:** Education and Onboarding of Engineers into our Cloud Platform, ran Clinics and Pairing/Troubleshooting sessions with Engineers. Surveyed the Engineering Organization on DevOps Maturity to understand the main gaps across CondeNast Engineering in order to address them. Responsible for demos, announcements and general platform updates to the wider Engineering Organization. 
- **Infrastructure as Code (IaC) Management:** responsible for Orchestrated (CircleCI Pipelines) AWS account Provisioning via IaC (Terraform), owner of Best Practices and distribution of Terraform Modules for all Engineering.
- **Build Systems:** Owner of custom docker images and docker image repository (Quay.io) distribution, security scan, access and availability.
- **Deployment Systems:** Owner of helm charts used by Engineers to deploy to Kubernetes as well as best practices like rollback strategies.
- **Pipeline/Orchestration Systems:** Owner or CircleCI Enterprise and SaaS, responsible for SLOs, upgrades and secret management.
- **Cloud Governance:** Designed and built the Audit log system. Owner of resource Tagging best practices as well as cost saving and security integrations.
- **Access Management:** Management of Engineer access via Okta SSO Integration, Github, VPN, Pritunl Zero (Beyond Corp Proxy) and secure secret storage via 1Password and Keybase. Owners of the Joiners/Movers/Leavers process for several of the services we provide.

### DHI Group Inc - London, UK - Oct 2015 to Nov 2018

#### Senior Software Engineer @ Cloud Platform Engineering Team - 1 year
- Joined a cross time zone team (US) to provide tools, templates and direction to common team challenges, including logging, monitoring, IAM permissions and CI/CD solutions.
- Pioneered our internal CloudFormation CLI tool (Python) that mimics CodePipeline allowing Engineers to deploy nested test stacks in seconds while enforcing naming and tagging policies.
- Produced several architecture diagrams, detailed documentation, guidelines and best practices for teams across the organization.
- Investigated and provided a Secret Management solution for teams that can be used within CloudFormation buy leveraging Parameter Store and Lambda based CloudFormation Resources.
- Provided a solution to ship AWS Lambda logs to Splunk as a CloudFormation template.
- Provided a solution to ship AWS Lambda metrics to InfluxDB as a CloudFormation template.
- Provided an Artefact Store solution to store encrypted application artifacts as a CloudFormation template, by leveraging S3, KMS and Managed Policies.
- Provided several CodeBuild templates with different integrations (CodePipeline and GitHub) as CloudFormation templates.
- Created a CloudFormation template that manages GitHub WebHooks and allows teams to build and run tests on Pull Requests.
- Ran a proof of concept on ECS Fargate, as part of our cross organization effort to investigate the benefits and drawbacks of Containers versus Lambda solutions.

#### Senior Software Engineer @ eFinancialCareers Team - 1 year
- Successfully helped migrate all our stack to AWS.
- Successfully migrated all eFinancialCareers DNS records to Route53.
- Lead the Infrastructure design process, including Virtual Machines (EC2) and Serverless (AWS Lambda).
- Built the Infrastructure, Tooling and Delivery for our Login ReactJS Web Components as well as the Components themselves using Terraform and AWS (CodePipeline, S3, CloudFront, WAF, Jenkins).
- Set the standard for several types of Pipelines, including legacy systems, micro services and UI. There are now 50+ pipelines of which 15 have no human intervention from Source Control (GitHub) to Production and include Unit, Black Box, End to End and Smoke tests.
- Created and maintained several AWS Lambda based systems to provide Deployment Windows, Email Alert notifications and automated JIRA tickets to aid our move into Continuous Delivery.
- As a Senior Engineer worked on a daily basis with internal consumers of our services, including development, marketing and product teams.
- Mentored several new engineers in AWS services and team workflow.
- Responsible to design an improved On-boarding process, where engineers have clear setup instructions, an assigned mentor, pair with other engineers and are provided with On Call training.
- Participated and provided feedback in several interviews from Junior to Senior level engineers across our skill stack (Java, Angular, AWS).
- Helped build a canned Jenkins and Selenium based on EC2 that can be spun up in minutes

#### Javascript Developer @ eFinancialCareers Team - 1 year
- Responsible to continuously improve our WebStore product (AngularJS) with analytics, A/B Testing solutions, and Business features, as well as End to End tests (Protractor).
- Augmented the UI projects with build and optimization tools, as a way to improve the development flow (Gulp and NPM).
- Lead an effort to improve our team's git workflow by simplifying the branching strategy and Pull Requests flow.
- Built several development environments using Vagrant to speed up the On-boarding process and help with the team's Windows to Mac migration.

### Lead Galaxy - London, UK - Oct 2014 to Oct 2015

#### Full Stack Web Developer
As Full Stack Developer I worked in diverse types of projects including:
Landing pages, Newsletter design, code and optimization, Wordpress setup, customization and speed optimization, Bespoke websites design, code and speed optimization, Website analytics and Conversion tracking (Google, Facebook, Twitter and Bing), Admin Platform (AngularJS), Database design (SQL), API design, implementation and documentation (PHP, Node.js and ASP .NET), In- house automation tools (Node.js), Systems troubleshoot (Website, Email, Analytics and Conversion Tracking), Documented Workflow and Website tools, Brand design (logos, digital ads), Print design (business cards, stands, badges and magazine ads).

### Vitamin London - London, UK - Nov 2013 to Sep 2014 (1y)

#### Front & Middle-End Web Developer
I worked in a small team, and very closely with the Digital Designer and the Back-End Developer to bring the best possible product to the client. Smaller projects include Shopify and Wordpress setup, customization and plugins. Medium sized projects include website redesign, fully responsive websites and micro-websites. And bigger projects consist of custom-made web platforms with full- blown API’s, desktop client apps and mobile client apps. In addition to client projects I develop in- house web tools and frameworks, like a photo cropping tools, image sliders, image pre-loaders and javascript UI kits. Testing is also a big part of my process, and I use various local and remote tools to test in different browsers and devices making sure every product is fully operational and performs efficiently.

### Self-Employed - Lisbon, Portugal - 2011 to 2013

#### Freelance Web Developer

Worked on various improvements and new features in existing websites in the hospitality industry.

## Education

### University of Lisbon (UL) - Faculty of Fine Arts Lisbon (FBAUL) - 2012 to 2013
MA in Equipment Design (6 Units)
Lisbon, Portugal
Units completed successfully and with an overall average of 15 points (out of 20).

### Laureate International Universities - Universidade Europeia - 2009 to 2012
BA Hons in Information Systems, Web and Multimedia
Lisbon, Portugal
Degree Completed with an overall average of 15 points (out of 20).

## Interests
- Robotics
- Product Design
- Photography
- Travel
- Food
- Home Automation
- Japanese Culture
- Gaming

## Languages
- Portuguese (Native)
- English (Advanced)
- Japanese (Beginner)