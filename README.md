<p align="center">
   
![image](https://github.com/Bybburnam/post-install-config/assets/102566114/574331ab-66e7-4582-97f8-7c764493b53a)

</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

---

## osTicket Admin Panel Configuration Guide

**Welcome to osTicket! Let's get started with setting up your admin panel for efficient support ticket management.**

**Admin vs Agent:** There's an admin panel and an agent panel. You're in the admin panel now. If you ever need to switch, just click "**Admin Panel**" at the top. We'll do tasks as both an admin and an agent, focusing on the admin side in this tutorial.

**Click Admin Panel to Go to Settings:**

### Configure Roles
1. Click on `Admin Panel`.
2. Navigate to `Agents` and then select `Roles`.
   - **Supreme Admin:** Set up the highest admin role. Add role

![image](https://github.com/Bybburnam/post-install-config/assets/102566114/d0436d9b-ec37-487c-8c16-f8511b4b218c)


### Configure Departments
1. Head to `Admin Panel`.
2. Go to `Agents` and click on `Departments`.
   - **System Administrators:** Configure department settings.

![image](https://github.com/Bybburnam/post-install-config/assets/102566114/2b18415a-d2ac-4e6b-83b6-bf414c78b9e0)


### Configure Teams
1. Stay in the `Admin Panel`.
2. Navigate to `Agents` and select `Teams`.
3. Add yourself to the team
   - **Level I Support**
   - **Level II Support**

![image](https://github.com/Bybburnam/post-install-config/assets/102566114/929f19b5-934f-45d6-b726-dda6aaffce01)
![image](https://github.com/Bybburnam/post-install-config/assets/102566114/886bbf37-d2de-4232-bb9a-1b4a21f40d39)


### Allow Anyone to Create Tickets
1. Under `Admin Panel`, go to `Settings` and then `User Settings`.
   - Make sure to **uncheck** "Registration Required." This allows anyone to create tickets without registration.

![image](https://github.com/Bybburnam/post-install-config/assets/102566114/ec235379-b9b3-42a0-9dba-ad3ddd99a02e)


### Configure Agents (Workers)
1. Stay in the `Admin Panel`, then go to `Agents` and choose `Add New`.
   - **Jane:** Assign her to the `System Administrators` department, set her role as **Supreme Admin**, and add her to the `Level II Support` team.
   - **John:** Set him in the `Support` department with a **View Only** role.

![image](https://github.com/Bybburnam/post-install-config/assets/102566114/a19e8ad6-8d92-4f13-be18-1305c5071176)
![image](https://github.com/Bybburnam/post-install-config/assets/102566114/8be3dbc9-9c77-4a8d-90a6-3aa051d40400)
![image](https://github.com/Bybburnam/post-install-config/assets/102566114/86c21f2e-aaab-416c-bf32-d7e1a7c782c2)
![image](https://github.com/Bybburnam/post-install-config/assets/102566114/8299894a-f710-4900-86bd-32a2641887f8)



### Configure Users (Customers)
1. Switch to the `Agent Panel`, then head to `Users` and click on `Add New`.
   - **Karen**
   - **Ken**
     
![image](https://github.com/Bybburnam/post-install-config/assets/102566114/e8b60984-fc4f-4564-97e4-2b96d07a7a79)
![image](https://github.com/Bybburnam/post-install-config/assets/102566114/38280417-7787-47d5-82c9-9232aec49d76)


### Configure SLA (Service Level Agreement)
1. Go back to the `Admin Panel`, select `Manage`, and then click on `SLA`.
   - Create three SLAs: 
     - **Sev-A:** 1-hour response time, 24/7 availability.
     - **Sev-B:** 4-hour response time, 24/7 availability.
     - **Sev-C:** 8-hour response time during business hours.

![image](https://github.com/Bybburnam/post-install-config/assets/102566114/86aeae89-b577-43c1-9b15-68303dfffab5)
![image](https://github.com/Bybburnam/post-install-config/assets/102566114/96bf6b68-7b98-4bc2-bcaf-7c7808fe3bcb)


### Configure Help Topics
1. In the `Admin Panel`, go to `Manage` and select `Help Topics`.
   - Create four new help topics:
     - Business Critical Outage
     - Personal Computer Issues
     - Equipment Request
     - Password Reset
     - 
![image](https://github.com/Bybburnam/post-install-config/assets/102566114/a6608363-28f1-4492-8ae7-9c9795218310)
![image](https://github.com/Bybburnam/post-install-config/assets/102566114/642358c0-4878-4eb2-9291-f30fa4ed5351)
![image](https://github.com/Bybburnam/post-install-config/assets/102566114/ddce6382-92ab-4119-8a10-5455e3a70169)

---

**Congratulations!** You've successfully configured your osTicket admin panel for smooth support ticket management. In our next tutorial, we'll explore the agent panel to enhance your osTicket experience. If you need help or have questions, don't hesitate to reach out. Happy ticket management on GitHub!

![image](https://github.com/Bybburnam/post-install-config/assets/102566114/0eeb2063-391b-4cd9-8115-11309ad214ee)


