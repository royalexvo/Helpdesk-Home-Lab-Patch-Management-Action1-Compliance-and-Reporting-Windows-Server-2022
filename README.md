# Helpdesk Home Lab - Patch Management, Action1, Compliance, & Reporting (Windows Server 2022)

<h2>Description</h2>

This lab demonstrates patch management, endpoint administration, and compliance reporting using Action1 in a Windows Server environment. The goal of this lab is to practice deploying endpoint management agents, managing Windows updates, reviewing compliance requirements, generating audit reports, and performing asset inventory tasks commonly used in help desk, systems administration, and cybersecurity environments.

In this lab, the following tasks were completed:

- <b>Reviewed patch management concepts and best practices</b>
- <b>Discussed compliance frameworks including SOC 2 Type II, PCI, HIPAA, and ISO 27001</b>
- <b>Reviewed common enterprise patch management platforms</b>
- <b>Downloaded the Action1 endpoint management agent</b>
- <b>Transferred the Action1 installer into the lab environment</b>
- <b>Installed the Action1 endpoint agent</b>
- <b>Configured network connectivity for endpoint registration</b>
- <b>Connected a Windows Server 2022 endpoint to Action1</b>
- <b>Verified endpoint status within the Action1 dashboard</b>
- <b>Reviewed endpoint management capabilities</b>
- <b>Identified missing Windows updates</b>
- <b>Configured patch deployment settings</b>
- <b>Configured automatic reboot options</b>
- <b>Deployed Windows updates to a managed endpoint</b>
- <b>Monitored update installation progress</b>
- <b>Reviewed vulnerability management reporting</b>
- <b>Generated endpoint inventory reports</b>
- <b>Reviewed hardware inventory reporting</b>
- <b>Reviewed software inventory reporting</b>
- <b>Reviewed compliance and audit reporting capabilities</b>

This lab demonstrates how organizations manage software updates, maintain compliance requirements, and generate reports used during security audits and asset management reviews.

<h2>Languages and Utilities Used</h2>

- <b>Action1</b>
- <b>Windows Server 2022</b>
- <b>Windows 10</b>
- <b>Oracle VirtualBox</b>
- <b>Control Panel</b>
- <b>TCP/IPv4 Configuration</b>
- <b>Patch Management Dashboard</b>

<h2>Environments Used</h2>

- <b>Domain Controller: Windows Server 2022</b>
- <b>Client Machine: Windows 10</b>
- <b>Oracle VirtualBox</b>
- <b>Action1 Cloud Management Platform</b>

<h2>Program walk-through:</h2>

<p align="center">
<b>Step 1 – Review Patch Management Concepts</b><br/><br/>
Review patch management objectives, compliance requirements, and enterprise update strategies. <a href="https://docs.google.com/document/d/1ZoJNqmKoBNUdmokhD98YzQYhgwixJaWa6etcDTXJYRQ/edit?usp=sharing">[Report on it here]</a>:<br/>
<img src="https://github.com/royalexvo/Helpdesk-Home-Lab-Patch-Management-Action1-Compliance-and-Reporting-Windows-Server-2022/blob/main/1.png?raw=true" height="80%" width="80%" alt="Lab Steps"/>
</p>

<p align="center">
<b>Step 2 – Review Patch Management Platforms</b><br/><br/>
Explore common patch management solutions including Action1, NinjaOne, PDQ, and SCCM. <a href="https://docs.google.com/document/d/1ZoJNqmKoBNUdmokhD98YzQYhgwixJaWa6etcDTXJYRQ/edit?usp=sharing">[Report on it here]</a>:<br/>
<img src="https://github.com/royalexvo/Helpdesk-Home-Lab-Patch-Management-Action1-Compliance-and-Reporting-Windows-Server-2022/blob/main/2.1.png?raw=true" height="80%" width="80%" alt="Lab Steps"/>
</p>

<p align="center">
<b>Step 3 – Access the Action1 Dashboard</b><br/><br/>
Sign in to the Action1 portal and review available endpoint management features:<br/>
<img src="https://github.com/royalexvo/Helpdesk-Home-Lab-Patch-Management-Action1-Compliance-and-Reporting-Windows-Server-2022/blob/main/3.png?raw=true" height="80%" width="80%" alt="Lab Steps"/>
</p>

<p align="center">
<b>Step 4 – Download the Action1 Agent installer for transfer.</b><br/><br/>
Download the endpoint management agent from the Action1 dashboard:<br/>
<img src="https://github.com/royalexvo/Helpdesk-Home-Lab-Patch-Management-Action1-Compliance-and-Reporting-Windows-Server-2022/blob/main/4.png?raw=true" height="80%" width="80%" alt="Lab Steps"/>
</p>

<p align="center">
<b>Step 5 – Transfer the Agent to the Lab Environment</b><br/><br/>
Copy the Action1 installer to the Windows Server 2022 lab machine:<br/>
<img src="https://github.com/royalexvo/Helpdesk-Home-Lab-Patch-Management-Action1-Compliance-and-Reporting-Windows-Server-2022/blob/main/5.png?raw=true" height="80%" width="80%" alt="Lab Steps"/>
</p>

<p align="center">
<b>Step 6 – Install the Action1 Agent</b><br/><br/>
Launch the installer and complete the endpoint agent installation process:<br/>
<img src="https://github.com/royalexvo/Helpdesk-Home-Lab-Patch-Management-Action1-Compliance-and-Reporting-Windows-Server-2022/blob/main/6.png?raw=true" height="80%" width="80%" alt="Lab Steps"/>
</p>

<p align="center">
<b>Step 7 – Configure Internet Connectivity</b><br/><br/>
Enable internet access and allow the endpoint to register with Action1 services:<br/>
<img src="https://github.com/royalexvo/Helpdesk-Home-Lab-Patch-Management-Action1-Compliance-and-Reporting-Windows-Server-2022/blob/main/7.png?raw=true" height="80%" width="80%" alt="Lab Steps"/>
</p>

<p align="center">
<b>Step 8 – Verify Endpoint Registration</b><br/><br/>
Confirm that the Windows Server endpoint successfully appears within the Action1 dashboard:<br/>
<img src="https://github.com/royalexvo/Helpdesk-Home-Lab-Patch-Management-Action1-Compliance-and-Reporting-Windows-Server-2022/blob/main/8.png?raw=true" height="80%" width="80%" alt="Lab Steps"/>
</p>

<p align="center">
<b>Step 9 – Review Endpoint Management Features</b><br/><br/>
Explore software deployment, update management, scripting, remote desktop, and endpoint administration capabilities:<br/>
<img src="https://github.com/royalexvo/Helpdesk-Home-Lab-Patch-Management-Action1-Compliance-and-Reporting-Windows-Server-2022/blob/main/9.png?raw=true" height="80%" width="80%" alt="Lab Steps"/>
</p>

<p align="center">
<b>Step 10 – Review Missing Updates</b><br/><br/>
Identify missing Windows updates and security patches detected on the managed endpoint:<br/>
<img src="https://github.com/royalexvo/Helpdesk-Home-Lab-Patch-Management-Action1-Compliance-and-Reporting-Windows-Server-2022/blob/main/10.png?raw=true" height="80%" width="80%" alt="Lab Steps"/>
</p>

<p align="center">
<b>Step 11 – Configure Patch Deployment Settings</b><br/><br/>
Select available updates, configure reboot preferences, and prepare the deployment job:<br/>
<img src="https://github.com/royalexvo/Helpdesk-Home-Lab-Patch-Management-Action1-Compliance-and-Reporting-Windows-Server-2022/blob/main/11.png?raw=true" height="80%" width="80%" alt="Lab Steps"/>
</p>

<p align="center">
<b>Step 12 – Deploy Windows Updates</b><br/><br/>
Execute the update deployment task against the Windows Server endpoint:<br/>
<img src="https://github.com/royalexvo/Helpdesk-Home-Lab-Patch-Management-Action1-Compliance-and-Reporting-Windows-Server-2022/blob/main/12.png?raw=true" height="80%" width="80%" alt="Lab Steps"/>
</p>

<p align="center">
<b>Step 13 – Monitor Update Installation Progress</b><br/><br/>
Track update progress and verify successful patch deployment through the dashboard:<br/>
<img src="https://github.com/royalexvo/Helpdesk-Home-Lab-Patch-Management-Action1-Compliance-and-Reporting-Windows-Server-2022/blob/main/13.png?raw=true" height="80%" width="80%" alt="Lab Steps"/>
</p>

<p align="center">
<b>Step 14 – Review Compliance and Vulnerability Reports</b><br/><br/>
Explore built-in reports used for compliance audits, vulnerability management, and security reviews:<br/>
<img src="https://github.com/royalexvo/Helpdesk-Home-Lab-Patch-Management-Action1-Compliance-and-Reporting-Windows-Server-2022/blob/main/14.png?raw=true" height="80%" width="80%" alt="Lab Steps"/>
</p>

<p align="center">
<b>Step 15 – Review Asset Inventory Reporting</b><br/><br/>
Generate endpoint, hardware, and software inventory reports to the shared VM folder for auditing and asset management purposes:<br/>
<img src="https://github.com/royalexvo/Helpdesk-Home-Lab-Patch-Management-Action1-Compliance-and-Reporting-Windows-Server-2022/blob/main/15.png?raw=true" height="80%" width="80%" alt="Lab Steps"/>
</p>
