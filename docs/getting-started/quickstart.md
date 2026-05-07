# Quickstart

Deploy your first application on Najumi Go.

---

# Introduction

Najumi Go is the application deployment platform inside the Najumi Cloud ecosystem developed by Najumi Tech.

The platform enables developers, startups, and engineering teams to deploy applications through a simplified cloud workflow while maintaining production-oriented infrastructure behavior.

This guide walks through the complete deployment lifecycle from account creation to live application delivery.

---

# Create an Account

To begin using Najumi Go:

1. Open the Najumi Cloud dashboard
2. Create a new account
3. Verify your account credentials
4. Sign in to access the platform dashboard

After authentication, users gain access to project management, deployment workflows, runtime infrastructure, and platform services.

---

# Create a Project

Projects are the primary organizational layer inside Najumi Go.

To create a project:

1. Open the dashboard
2. Select **Create Project**
3. Enter a project name
4. Select the project type
5. Add an optional project description
6. Submit the project creation form

Supported project categories may include:
- web applications
- APIs
- backend services
- SaaS platforms
- internal tools
- modern JavaScript applications

After creation, the account owner automatically becomes:
- project owner
- administrator
- primary deployment manager

Project owners can:
- manage members
- configure permissions
- control deployments
- manage services
- configure infrastructure settings

---

# Team Collaboration

Najumi Go supports collaborative project management.

Project owners can:
- invite team members
- assign access roles
- manage permissions
- remove members
- coordinate deployment workflows

This enables engineering teams to manage infrastructure collaboratively inside shared projects.

---

# Create a Service

Services represent deployable runtime units inside a project.

To create a service:

1. Open an existing project
2. Select **Create Service**
3. Choose the infrastructure type:
   - frontend
   - backend
   - database
4. Continue to runtime selection
5. Select a supported framework
6. Complete service creation

Supported runtime environments may include:
- Node.js
- Next.js
- Express.js
- React
- static applications
- additional modern frameworks

After creation, the platform provisions the service environment automatically.

The service may appear after a short provisioning delay while infrastructure resources are initialized.

---

# Deploy an Application

Najumi Go supports multiple deployment methods.

Deployment can begin immediately after service provisioning completes.

---

# GitHub Deployment

To deploy from GitHub:

1. Open the service dashboard
2. Select **Deploy**
3. Choose the target service
4. Select **GitHub Repository**
5. Enter the repository URL
6. Start deployment

The deployment pipeline automatically:
- clones the repository
- prepares the runtime
- installs dependencies
- builds the application
- provisions infrastructure
- starts the runtime service

Deployment logs are streamed in real time during execution.

---

# ZIP Deployment

To deploy using ZIP upload:

1. Open the deployment interface
2. Select **ZIP Upload**
3. Upload the application archive
4. Start deployment

ZIP uploads can be selected from:
- desktop systems
- laptops
- mobile devices
- tablets

The deployment system automatically:
- extracts application files
- prepares runtime infrastructure
- installs dependencies
- builds the application
- provisions routing
- starts the service

Deployment progress and logs are displayed in real time.

---

# Deployment Status

After deployment completes:

- successful deployments become live automatically
- deployment logs remain accessible
- runtime status becomes visible
- infrastructure routing activates automatically

If deployment errors occur, the platform displays:
- build failures
- runtime issues
- deployment errors
- provisioning failures

This enables developers to troubleshoot deployment problems directly from the dashboard.

---

# Automatic Subdomains

Each deployed service receives an automatically provisioned subdomain.

Example:

```text
service-name.najumigo.com
```

This allows applications to become publicly accessible immediately after successful deployment.

---

# Custom Domains

Najumi Go supports custom domain integration.

To connect a custom domain:

1. Open the service dashboard
2. Navigate to the domain configuration section
3. Add the desired domain
4. Verify ownership using provided DNS records
5. Wait for propagation
6. Activate the domain

After DNS propagation completes, the platform automatically:
- verifies ownership
- configures routing
- provisions HTTPS support
- activates SSL

---

# SSL & HTTPS

Najumi Go includes automatic HTTPS support and SSL provisioning.

Security features include:
- encrypted HTTPS traffic
- SSL certificate provisioning
- secure runtime routing
- protected deployment infrastructure

---

# Plans & Billing

All new accounts begin on the Free plan automatically.

The Free plan allows users to:
- create projects
- provision services
- deploy applications
- test infrastructure workflows

As infrastructure usage grows, users can upgrade to larger plans designed for:
- production applications
- scalable services
- SaaS platforms
- growing workloads

Paid infrastructure plans currently begin at:

```text
$4.95/month
```

Higher plans provide expanded infrastructure capacity and runtime resources.

---

# Platform Direction

Najumi Go is part of the broader Najumi Cloud ecosystem developed by Najumi Tech.

Future infrastructure systems will include:
- VPS infrastructure
- object storage
- managed databases
- DNS systems
- email infrastructure
- CDN services
- advanced networking

---

# Organization

Najumi Go is developed and maintained by Najumi Tech.
