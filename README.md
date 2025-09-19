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

<h2>Post-Install Configuration Objectives</h2>

- Set up User Roles & Permissions
- Configure Users and Agents
- Customize Ticket Fields & Help Topics
- Secure the Installation
- Configure SLA Plans

<h2>Configuration Steps</h2>

<p>

</p>
<img src="https://github.com/user-attachments/assets/2ab8bd98-d0a2-4acb-8e25-5efb7f674c32" />
<p>
I logged into osTicket using localhost/osTicket/scp/login.php. Switch to Admin Panel in the upper righthand corner and navigate to Agents tab.
</p>

</p>
<img src="https://github.com/user-attachments/assets/64f96dfb-db98-428e-b6ea-f78ab86ce9bc" />
<p>
Under the Agents tab, click Roles and under Roles, click View Only.
</p>

</p>
<img src="https://github.com/user-attachments/assets/1363c1b5-94ac-462d-8f59-2762b5db4087" />
<p>
Click on Permissions. As seen, none a currently selected.
</p>

</p>
<img src="https://github.com/user-attachments/assets/8b490059-045a-4337-b1d8-996ae656a03f" />
<p>
Go back by clicking Roles, click on Expand Access and go to Permissions. As seen, most of the permissions are selected.
</p>


</p>
<img src="https://github.com/user-attachments/assets/970704d7-9c02-437d-91f5-a69cd281e3e6" />
<img src="https://github.com/user-attachments/assets/22a1b305-3d3a-4efa-9802-ad2ced55dafc" />
<p>
Back under Roles, click on Add New to create a new role as Supreme Admin.
</p>

</p>
<img src="https://github.com/user-attachments/assets/365c5ff5-6948-46fe-a539-5b97cf623232" />
<p>
Select all permissions under the Ticket, asks, and Knowledgebase tabs to grant full access to make changes and click on Add Role.
</p>

</p>
<img src="https://github.com/user-attachments/assets/6983ebcd-4b8c-454c-843c-11226df6acc4" />
<p>
The new role has been successfully added.
</p>

</p>
<img src="https://github.com/user-attachments/assets/82299e5c-58c0-46b7-a33c-5318fd0bfee4" />
<p>
Go to departments and delete the Maintenance department so that tickets won't go directly to it. To do this, check the box, click More and delete.
</p>


</p>
<img src="https://github.com/user-attachments/assets/82299e5c-58c0-46b7-a33c-5318fd0bfee4" />
<p>
Click Add New Department, click Top-Level Department and select Support, and name it SysAdmins. Click Create Dept at the bottom of the screen.
</p>

</p>
<img src="https://github.com/user-attachments/assets/2631ab6e-a6f3-4ea4-b370-23c3471d2093" />
<p>
Navigate to Teams and click on Add New Team.
</p>


</p>
<img src="https://github.com/user-attachments/assets/2631ab6e-a6f3-4ea4-b370-23c3471d2093" />
<img src="https://github.com/user-attachments/assets/f4fceedb-70d3-4aa9-8edc-dde7f3453f80" />
<p>
Create an online banking team and successfully add it.
</p>

</p>
<img src="https://github.com/user-attachments/assets/345c6262-9259-4640-bf74-31694ed8f636" />
<p>
Under the Settings tab, navigate to Users and make sure the Registration required box isn't checked.
</p>

</p>
<img src="https://github.com/user-attachments/assets/651b2938-05b7-43e4-acd5-e25148880630" />
<p>
Go to the Agents tab and under it, click on Agents and Add New Agent.
</p>

</p>
<img src="https://github.com/user-attachments/assets/8bbea191-e4d2-4225-8305-a4cd91a733bb" />
<p>
Create a new Jane Smith and fill out all required fields.
</p>

</p>
<img src="https://github.com/user-attachments/assets/a5b5962f-8ec1-41e1-b69e-25692ad9ad97" />
<img src="https://github.com/user-attachments/assets/d9e88dd1-73ce-4668-8379-1858dbdbd6b3" />
<p>
Navigate to Access and add her to SysAdmins Department and add her as Supreme Admin. Under the Teams tab, add her to Online Banking then click Create
</p>

</p>
<img src="https://github.com/user-attachments/assets/2858214d-32d0-4c2b-a8a5-daeb85ca1b4f" />
<p>
Jane Smith has been successfully added.
</p>

</p>
<img src="https://github.com/user-attachments/assets/9efbe329-519b-4104-8962-074fd2855d94" />
<p>
Repeat the same process but create a new agent John Doe. Add him to Support department and a View Only role.
</p>

</p>
<img src="https://github.com/user-attachments/assets/ad5fd1c4-47cd-4870-ad9c-fa53c8e217f4" />
<p>
John Doe has successfully been added.
</p>

</p>
<img src="https://github.com/user-attachments/assets/c8976eca-1f7d-4931-b766-610677952b21" />
<p>
Reset passwords to Password1 for both Jane and John for the purpose of this lab by clicking Update.
</p>

</p>
<img src="https://github.com/user-attachments/assets/1e3948da-543c-4e8d-b7e0-6d6237fc438d" />
<p>
To create a new user Karen, go to Agent panel, User tab, then click Add User. 
</p>

</p>
<img src="https://github.com/user-attachments/assets/a23ede55-98b2-473a-9104-4996634f701a" />
<img src="https://github.com/user-attachments/assets/e0760b8a-2649-4cac-8c3c-a25240b18569" />
<p>
Fill out required information and successfully add Karen
</p>

</p>
<img src="https://github.com/user-attachments/assets/77821632-a4f7-4526-9899-cb98f027af9c" />
<p>
In Admin Panel, go to the Manage tab and click on SLA
</p>

</p>
<img src="https://github.com/user-attachments/assets/da78dec7-50cc-4b2a-965c-88505fd95e2b" />
<p>
Under SLA, click on Add New SLA to create a Sev-A 24/7 plan with a 1 hour grace period and click Add Plan.
</p>

</p>
<img src="https://github.com/user-attachments/assets/25626e8b-1763-4987-be43-d132df2485ae" />
<p>
Click Add New SLA to create a Sev-B 24/7 with a 4 hour grace period and click Add Plan.
</p>

</p>
<img src="https://github.com/user-attachments/assets/ab59296f-cb1a-437c-b3a5-508e4af0ad01" />
<p>
Click Add New SLA to create a Sev-C Monday through Friday plan with a 8 hour grace period and click Add Plan.
</p>

</p>
<img src="https://github.com/user-attachments/assets/ab769d6f-76ff-45e9-801a-932342de8dd0" />
<p>
The SLA plans have been successfully added.
</p>

</p>
<img src="https://github.com/user-attachments/assets/0f2a3b8b-7e6a-4ab4-99b6-5c41d9fe0774" />
<p>
Navigate to HelpTopics and click Add New Help Topic.
</p>

</p>
<img src="https://github.com/user-attachments/assets/db2d6498-c57d-4043-8464-3ae6fe6549ca" />
<p>
Create a Business Critical Outage topic with Report a Problem as the parent topic.
</p>

</p>
<img src="https://github.com/user-attachments/assets/d8e026b3-11d7-4fef-bed1-a34a886ee98a" />
<p>
Create a Personal Computer Issues topic with Report a Problem as the parent topic.
</p>

</p>
<img src="https://github.com/user-attachments/assets/d8e026b3-11d7-4fef-bed1-a34a886ee98a" />
<p>
Create a Equipment Request topic with General Inquiry as the parent topic.
</p>

</p>
<img src="https://github.com/user-attachments/assets/2e03e673-6636-4e14-b802-3f43d22e1acf" />
<p>
Create a Password Reset topic with Report a Problem as the parent topic.
</p>

</p>
<img src="https://github.com/user-attachments/assets/6230a9e9-fce5-463f-b981-e24b2533c3ab" />
<p>
To conclude the lab, create Other topic with General Inquiry as the parent topic.
</p>
