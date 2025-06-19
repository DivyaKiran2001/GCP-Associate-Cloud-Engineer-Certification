# ☁️ Azure vs GCP Services Comparison

This document provides a side-by-side comparison of core services between **Microsoft Azure** and **Google Cloud Platform (GCP)**, categorized by functionality and use case.

---

## 🔧 Compute Services

| Category              | Azure Service                      | GCP Service                      | Purpose                                      |
|-----------------------|------------------------------------|----------------------------------|----------------------------------------------|
| Virtual Machines       | Azure Virtual Machines              | Compute Engine                   | Run virtual machines in the cloud            |
| Autoscaling           | VM Scale Sets                      | Managed Instance Groups          | Automatically scale VM instances             |
| Containers (K8s)      | Azure Kubernetes Service (AKS)     | Google Kubernetes Engine (GKE)   | Managed Kubernetes for containers            |
| Serverless Functions  | Azure Functions                    | Cloud Functions                  | Event-driven serverless compute              |
| App Hosting           | Azure App Service                  | App Engine                       | Host web apps and APIs                       |
| Serverless Containers | Azure Container Apps               | Cloud Run                        | Run containers without managing infra        |

---

## 💾 Storage Services

| Category              | Azure Service                      | GCP Service                      | Purpose                                      |
|-----------------------|------------------------------------|----------------------------------|----------------------------------------------|
| Object Storage        | Blob Storage                       | Cloud Storage                    | Store unstructured data like images/files    |
| File Storage          | Azure Files                        | Filestore                        | Managed file shares                          |
| Block Storage         | Azure Disk Storage                 | Persistent Disks                 | High-performance storage for VMs             |
| Table/NoSQL Storage   | Azure Table Storage                | Firestore / Cloud Datastore      | Key-value NoSQL database                     |
| Queues & Messaging    | Azure Queue Storage                | Cloud Tasks / Pub/Sub            | Messaging between components                 |
| Archive Storage       | Blob Archive Tier                  | Coldline / Archive Storage       | Long-term, low-cost storage                  |

---

## 🗃️ Database Services

| Category              | Azure Service                      | GCP Service                      | Purpose                                      |
|-----------------------|------------------------------------|----------------------------------|----------------------------------------------|
| Relational DB (SQL)   | Azure SQL Database                 | Cloud SQL                        | Managed SQL Server, PostgreSQL, MySQL        |
| NoSQL DB              | Azure Cosmos DB                   | Firestore / Bigtable             | Globally distributed NoSQL DB                |
| Data Warehouse        | Azure Synapse Analytics            | BigQuery                         | Enterprise data warehouse                    |
| In-Memory Cache       | Azure Cache for Redis              | Memorystore for Redis            | In-memory data caching                       |

---

## 🌐 Networking Services

| Category              | Azure Service                      | GCP Service                      | Purpose                                      |
|-----------------------|------------------------------------|----------------------------------|----------------------------------------------|
| Virtual Network       | Azure Virtual Network (VNet)       | VPC Network                      | Isolated private network in the cloud        |
| Subnetting            | Subnets                            | Subnets                          | IP range divisions within networks           |
| Private Connectivity  | ExpressRoute                       | Cloud Interconnect               | Private, high-speed connection to cloud      |
| VPN                   | Azure VPN Gateway                  | Cloud VPN                        | Secure site-to-site connection               |
| Load Balancing        | Azure Load Balancer / App Gateway  | Cloud Load Balancing             | Distribute traffic to resources              |
| DNS Hosting           | Azure DNS                          | Cloud DNS                        | Manage custom domain names                   |

---

## 🔐 Identity & Access

| Category              | Azure Service                      | GCP Service                      | Purpose                                      |
|-----------------------|------------------------------------|----------------------------------|----------------------------------------------|
| IAM                   | Role-Based Access Control (RBAC)   | Cloud IAM                        | Control who can access what                  |
| Identity              | Azure Active Directory (AAD)       | Cloud Identity                   | User and access management                   |
| Secrets Management    | Azure Key Vault                    | Secret Manager                   | Secure storage for secrets/keys              |
| Policy Enforcement    | Azure Policy                       | Organization Policy              | Apply governance and compliance              |

---

## 📈 Monitoring & DevOps

| Category              | Azure Service                      | GCP Service                      | Purpose                                      |
|-----------------------|------------------------------------|----------------------------------|----------------------------------------------|
| Monitoring            | Azure Monitor + Log Analytics      | Cloud Monitoring + Logging       | View logs and metrics                        |
| Tracing & Errors      | Application Insights               | Cloud Trace / Error Reporting    | App performance and diagnostics              |
| CI/CD Pipelines       | Azure DevOps / GitHub Actions      | Cloud Build / Deploy             | Build, test, and deploy automation           |

---

## 🔄 Migration & Data Transfer

| Category              | Azure Service                      | GCP Service                      | Purpose                                      |
|-----------------------|------------------------------------|----------------------------------|----------------------------------------------|
| Workload Migration    | Azure Migrate                      | Migrate for Compute Engine       | Discover, assess, migrate on-prem workloads  |
| Bulk Data Transfer    | Azure Data Box                     | Transfer Appliance               | Physically transfer large datasets           |
| File Sync             | Azure File Sync                    | ❌ No direct GCP equivalent       | Sync on-prem files to the cloud              |

---

## 📊 Analytics & Integration

| Category              | Azure Service                      | GCP Service                      | Purpose                                      |
|-----------------------|------------------------------------|----------------------------------|----------------------------------------------|
| Data Integration (ETL)| Azure Data Factory                 | Cloud Dataflow / Dataproc        | Data pipeline and transformation             |
| BI & Reporting        | Power BI                           | Looker / Data Studio             | Business intelligence and visualization      |

---

## 📌 Notes

- ✅ Services are matched by functionality, though implementation details vary.
- ❌ GCP has **no direct equivalent** for **Azure File Sync**.
- Categories and services are focused on core cloud infrastructure and platform capabilities.

---

## 📄 License

This README is provided for educational/reference use only.

