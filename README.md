<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
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



### Configure Departments
1. Head to `Admin Panel`.
2. Go to `Agents` and click on `Departments`.
   - **System Administrators:** Configure department settings.



### Configure Teams
1. Stay in the `Admin Panel`.
2. Navigate to `Agents` and select `Teams`.
   - **Level I Support**
   - **Level II Support**



### Allow Anyone to Create Tickets
1. Under `Admin Panel`, go to `Settings` and then `User Settings`.
   - Make sure to **uncheck** "Registration Required." This allows anyone to create tickets without registration.


### Configure Agents (Workers)
1. Stay in the `Admin Panel`, then go to `Agents` and choose `Add New`.
   - **Jane:** Assign her to the `System Administrators` department, set her role as **Supreme Admin**, and add her to the `Level II Support` team.
   - **John:** Set him in the `Support` department with a **View Only** role.



### Configure Users (Customers)
1. Switch to the `Agent Panel`, then head to `Users` and click on `Add New`.
   - **Karen**
   - **Ken**



### Configure SLA (Service Level Agreement)
1. Go back to the `Admin Panel`, select `Manage`, and then click on `SLA`.
   - Create three SLAs: 
     - **Sev-A:** 1-hour response time, 24/7 availability.
     - **Sev-B:** 4-hour response time, 24/7 availability.
     - **Sev-C:** 8-hour response time during business hours.



### Configure Help Topics
1. In the `Admin Panel`, go to `Manage` and select `Help Topics`.
   - Create four new help topics:
     - Business Critical Outage
     - Personal Computer Issues
     - Equipment Request
     - Password Reset



---

**Congratulations!** You've successfully configured your osTicket admin panel for smooth support ticket management. In our next tutorial, we'll explore the agent panel to enhance your osTicket experience. If you need help or have questions, don't hesitate to reach out. Happy ticket management on GitHub!

---

Feel free to copy and paste this corrected Markdown-formatted content directly into your GitHub repository. If you have more steps or need further assistance, feel free to ask!
