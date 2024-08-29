# Comprehensive project for AZ-104 exam

We can build a scenario where you are responsible for setting up and managing the infrastructure for a fictional company, "Tech Solutions Inc." This project will involve managing identities, governance, storage, compute resources, networking, and security within Azure.

### **Project Title: Complete Azure Infrastructure Deployment for Tech Solutions Inc.**

---

### **Project Overview:**

**Objective:**  
The goal is to set up and manage a scalable, secure, and efficient cloud infrastructure for Tech Solutions Inc. using Azure. You will cover all critical areas including identity management, governance, virtual networking, compute resources, storage solutions, and security.

**Scenario:**  
Tech Solutions Inc. is a growing technology company that requires a robust cloud infrastructure to support its operations. The company needs to manage user identities, secure its resources, deploy and manage virtual machines, configure storage solutions, and ensure network connectivity across its global offices.

### **Project Phases and Associated Labs:**

---

#### **Phase 1: Identity and Access Management**

**Objective:**  
Establish a secure and scalable identity management system using Azure Active Directory (AD).

**Labs:**
1. **Manage Azure Active Directory Identities**
   - Create and configure Azure AD users
   - Create Azure AD groups with assigned and dynamic membership
   - Create an Azure Active Directory (AD) tenant
   - Manage Azure AD guest users

2. **Manage Subscriptions and RBAC**
   - Implement Management Groups
   - Create custom RBAC roles
   - Assign RBAC roles

3. **Manage Governance via Azure Policy**
   - Create and assign tags via the Azure portal
   - Enforce tagging via an Azure policy
   - Apply tagging via an Azure policy

#### **Phase 2: Governance and Resource Management**

**Objective:**  
Implement governance and organize resources effectively to control costs and manage resource allocation.

**Labs:**
1. **Manage Azure resources by Using the Azure Portal**
   - Create resource groups and deploy resources to resource groups
   - Move resources between resource groups
   - Implement and test resource locks

2. **Manage Azure resources by Using ARM Templates**
   - Review and deploy resources using ARM templates

3. **Manage Azure resources by Using Azure PowerShell**
   - Start a PowerShell session in Azure Cloud Shell
   - Create and manage resources using Azure PowerShell

4. **Manage Azure resources by Using Azure CLI**
   - Start a Bash session in Azure Cloud Shell
   - Create and manage resources using Azure CLI

#### **Phase 3: Virtual Networking**

**Objective:**  
Set up and configure a secure and efficient network infrastructure that supports the company’s operations.

**Labs:**
1. **Implement Virtual Networking**
   - Create and configure a virtual network
   - Deploy virtual machines into the virtual network
   - Configure private and public IP addresses of Azure VMs
   - Configure network security groups (NSGs)
   - Configure Azure DNS for internal and external name resolution

2. **Implement Intersite Connectivity**
   - Configure local and global virtual network peering
   - Test intersite connectivity

3. **Implement Traffic Management**
   - Configure the hub and spoke network topology
   - Implement Azure Load Balancer and Application Gateway

4. **Network Access to storage accounts and limit access to private endpoints**
   - Create storage accounts with private endpoints
   - Configure network access to these storage accounts

#### **Phase 4: Compute Resources**

**Objective:**  
Deploy and manage virtual machines and scale resources as needed for different business applications.

**Labs:**
1. **Creating an Azure Virtual Machine via Windows 2019 Datacenter image**
   - Create and configure a Windows VM on Azure
   - RDP into the VM

2. **Create Linux VM through Ubuntu Server 20.04 LTS – Gen 2 image**
   - Create and configure a Linux VM on Azure
   - SSH into the VM and test its functionality

3. **Use CLI to add data disks to VM**
   - Use Azure CLI to create and configure data disks on a VM

4. **Install NGINX server on Linux Virtual Machine via Cloud-Init**
   - Deploy an NGINX web server on a Linux VM using Cloud-Init

5. **Manage Virtual Machines**
   - Configure VM extensions, scale compute, and storage resources for VMs

6. **Deploy software using VM extensions**
   - Install software and manage VM configurations using extensions

#### **Phase 5: Storage Solutions**

**Objective:**  
Set up and manage storage accounts, file shares, and blob storage for the company's data needs.

**Labs:**
1. **Using Blob Storage**
   - Create and configure Azure Blob Storage

2. **Create Storage Account**
   - Understand and set up storage account tiers and redundancy

3. **Manage Azure Storage**
   - Manage blob storage, file shares, and network access for Azure Storage

4. **Understand Azure Blob Storage Tiers**
   - Explore the different storage tiers available for Azure Blob Storage

5. **Work with Azure File shares**
   - Create and configure Azure File shares and sync them with on-premises directories

#### **Phase 6: Security and Monitoring**

**Objective:**  
Implement security measures to protect the cloud infrastructure and monitor resources for performance and reliability.

**Labs:**
1. **Create, assign and manage Azure Policies**
   - Create and enforce policies to ensure compliance and governance

2. **Create Azure Resource Locks and prevent accidental deletes**
   - Implement resource locks to protect critical resources from accidental deletion

3. **Work using resource tags**
   - Tag resources for effective management and cost tracking

4. **Implement Azure Backup services**
   - Set up backup solutions for virtual machines and other critical resources

5. **Use Azure CLI to create a Web App and ensure it runs on Docker images**
   - Create a web app and ensure it runs securely on Docker

#### **Phase 7: Application Deployment and Management**

**Objective:**  
Deploy and manage web applications, databases, and other critical services needed by the company.

**Labs:**
1. **Implement Web Apps**
   - Deploy and manage web apps using Azure services

2. **Build SQL Database by setting SQL server**
   - Set up and manage SQL databases for business applications

3. **Implement Virtual Networking peering and launch a VM in all virtual networks**
   - Ensure network connectivity between different Azure VMs and services

4. **Work with Application Insights to improve the performance of Web app**
   - Monitor and optimize web application performance using Application Insights

---

### **Project Deliverables:**

1. **Documentation:** Detailed documentation of the setup and configurations, including screenshots and explanations.
2. **Configuration Files:** ARM templates, PowerShell scripts, and CLI scripts used during the project.
3. **Monitoring and Reports:** Set up Azure Monitor and Application Insights dashboards and provide performance and security reports.
4. **Final Presentation:** A PowerPoint presentation summarizing the project’s scope, execution, and outcomes.

### **Project Evaluation:**

The project will be evaluated based on:
- **Completeness:** Successful completion of all labs and tasks.
- **Security:** Proper implementation of security best practices.
- **Scalability:** Demonstration of how the setup can scale to meet growing business needs.
- **Documentation:** Quality and clarity of the documentation provided.

This project will give you a deep understanding of how to manage a comprehensive Azure environment, preparing you well for the AZ-104 exam and real-world cloud management scenarios.
