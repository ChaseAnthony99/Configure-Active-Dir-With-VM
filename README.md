<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

 Set up a virtual machine environment. 

Install Windows Server OS on the virtual machine.

Install Active Directory Domain Services role.

Promote the server to a domain controller.

Configure DNS settings on the domain controller.

Create user accounts and groups in Active Directory.

Configure Group Policy Objects (GPOs) for managing settings.

Implement an organizational unit (OU) structure for organizing objects.

Configure replication between domain controllers.

Test and validate Active Directory functionality.

Implement backup and recovery procedures for Active Directory.

Monitor and maintain the Active Directory environment on the virtual machine.




<h2>Deployment and Configuration Steps</h2>

Set up a virtual machine environment: Create a virtualized environment using a hypervisor software like VMware or VirtualBox.

Install Windows Server OS on the virtual machine: Install a Windows Server operating system on the virtual machine where Active Directory will be deployed.

Install Active Directory Domain Services role: Add the Active Directory Domain Services role to the Windows Server through the Server Manager or PowerShell.

Promote the server to a domain controller: Use the Active Directory Domain Services Configuration Wizard to promote the server to a domain controller.

Configure DNS settings on the domain controller: Ensure that the DNS settings on the domain controller point to itself for DNS resolution.

Create user accounts and groups in Active Directory: Use the Active Directory Users and Computers console to create user accounts and groups.

Configure Group Policy Objects (GPOs) for managing settings: Use the Group Policy Management Console to create and link GPOs for configuring settings and policies.

Implement an organizational unit (OU) structure for organizing objects: Create OUs in Active Directory to organize users, groups, computers, and other objects based on your organizational structure.

Configure replication between domain controllers: Configure Active Directory replication to ensure that changes made on one domain controller are synchronized with others.

Test and validate Active Directory functionality: Test user authentication, group membership, GPO application, and other Active Directory features to ensure they are functioning correctly.

Implement backup and recovery procedures for Active Directory: Set up regular backups of Active Directory data and implement recovery procedures in case of data loss or corruption.

Monitor and maintain the Active Directory environment on the virtual machine: Use monitoring tools and perform regular maintenance tasks such as patching, optimizing performance, and addressing any issues that arise.

