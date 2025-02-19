<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
- Chatgpt

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>
<p>
osTicket can be used to simulate realword use cases for help desk scenarios. To get a more accurate represenation of ticket life cycles, osTicket has to be configured post install by:
</p>
<p>-Creating Fictional users and agents

  -Configuring service level agreements

-Configuring Help Topics</p>

<h2>Configuration Steps</h2>

![image](https://github.com/user-attachments/assets/054d8502-39e8-456b-9d36-34de45af9684)
<p>
As an admin, make sure that only registered users can make tickets by going to: Agent Panel >> Settings >> Registartion Required
</p>

![image](https://github.com/user-attachments/assets/16dec255-83ce-4a0c-8900-d5f851930a4d)
![image](https://github.com/user-attachments/assets/bc4ed5a7-e91d-46a3-8e75-e15ae854ccf4)
![image](https://github.com/user-attachments/assets/d5a95294-2eb4-46fa-82f5-1b81899635f2)
<p>
Now, try to simulate a work enviroment by creating departments and teams. Then create fictional agents and users to assign to those departments and teams. All of these configurations can be done from the Agent Panel. For this project, I chose to create a support team for online sales.
</p>

- Admin Panel >> Agents >> Roles

- Admin Panel >> Agents >> Departments

- Admin Panel >> Agents >> Teams

- Admin Panel >> Agents >> Add New

- Admin Panel >> Users>> Add New

![image](https://github.com/user-attachments/assets/33f79a01-5b20-4ca6-8222-adfc71a3dc24)
<p>
Continue adding help topics to better simulate a help disk ticket
</p>

![image](https://github.com/user-attachments/assets/213b74e9-9c93-443d-94f6-3aef0d5003ea)
<p>
Configure the SLA to replicate the excpecations of an employer regarding productivity
</p>

At this point, osTicket is now installed and properly configured for practice tickets. In order to create made up help desk scenarios, Chatgpt can be used to simulate potential tickets a help desk technician can come across as shown below:

![image](https://github.com/user-attachments/assets/74c626bf-625c-416a-b161-f38fea8666a1)
![image](https://github.com/user-attachments/assets/5fcdb63c-e8b9-4228-8921-a50bafc6f27f)
![image](https://github.com/user-attachments/assets/00d0a879-b086-46be-a8c2-9ca73d28dfa2)

osTicket has now been installed and configured to simulate an actual help desk workplace enviroment!
