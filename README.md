<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
For osTicket users who have completed the installation process, this tutorial outlines the essential post-installation configuration steps. We'll guide you through setting up departments, configuring email settings, and defining user roles to optimize your new help desk system.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines: Windows 10 recommended for this guide)
- Remote Desktop
- osTicket System Software
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)
<h2>1- Configure Roles</h2>

- Go to the **Admin Panel** on the top right menu. *(Note: You may/may not know which panel you are in, make sure if you click 'Admin', you're in the Admin Panel. Same goes to Agent Panel.)*
  
- Navigate to **Agents** and select **Roles**.

- Create a **Supreme Admin** role and select every options and save.

<h2>2- Configure Departments</h2>

- In the **Admin Panel**, go to **Agents** and click on **Departments**.
  
- Set up a **System Administrator** department.
  
<h2>3- Configure Teams</h2>

- While you're still in the **Admin Panel**, hover back to **Agents** tab and choose **Teams**.

- Create **teams** named **Level I Support** and **Level II Support.**

<h2>4- Allow Anyone to Create Tickets</h2>

- In the **Admin Panel**, select **Settings** and choose **User Settings**.

- Enable **Registration Required** to ensure users must register and log in to create tickets.

<h2>5- Configure Agents (Workers)</h2>

- Within the **Admin Panel**, under **Agents**, click on **Add New.**

- Add **agents** like "Jane" and "John" and create their logins (username and password, something easy as purpose for this tutorial).

<h2>6- Configure Users (Customers)</h2>

- Visit the **Agent Panel** and go to **Users**, then click **Add New.** *(Note: you're creating customers users as an experience in order to place tickets in the osTicket.)*

- Add users such as "Karen" and "Ken." Create their logins also.

<h2>7- Configure SLA (Service Level Agreements)</h2>

- From the **Admin Panel**, head to **Manage** and select **SLA**.

- Set up **SLAs** rules like "Sev-A" (1 hour, 24/7), "Sev-B" (4 hours, 24/7), and "Sev-C" (8 hours, business hours).

<h2>8- Configure Help Topics</h2>

- Lastly, go to the **Admin Panel**, click **Manage**, and choose **Help Topics**.

- Create topics such as "Business Critical Outage," "Personal Computer Issues," "Equipment Request," and "Password Reset."

-----

<h1>Conclusion</h1>
By following these straightforward steps, you've successfully configured your portfolio to manage roles, departments, teams, tickets, agents, users, SLAs, and help topics. Your setup is now ready to serve your needs effectively.

-----

# [Next: osTicket - Ticket Lifecycle (https://github.com/katieb11/ticket-lifecycle)
