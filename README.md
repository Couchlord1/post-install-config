<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
While OsTicket is usuable after a fresh install, proper configuring can help OsTicket more closely resemble real word help desk use cases. This project is a tutorial that outlines the post-install configuration of the open-source help desk ticketing system osTicket. For a tutorial on the installation of OsTicket, one can be found here: (https://github.com/Couchlord1/osticket-prereqs).

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines)
- Internet Information Services (IIS)
- Chatgpt
- Remote Desktop
  
<h2>Operating Systems Used </h2>

- Windows 10

<h2>Configuration Steps</h2>

1. Create Users and Departments
2. Configure service level agreements and topics

<h2>Walkthrough</h2>

<h3>Create Users and Departments</h3>

Replicate a typical IT Help Desk organizational structure by adding teams and departments, then creating agents to fill in roles in those teams and departments. For the purposes of this project I tried to replicated a small IT help desk team:

- From *Admin Panel* >> *Agents* >> *Agents* >> *Add New*

Add 6 additional agents with the job titles of technician, sepcialists and engineer.
  
![Capture](https://github.com/user-attachments/assets/df5b1a94-4576-4366-b9f5-423b50f1a1b1)

- Then, from *Admin Panel* >> *Agents* >> *Teams* >> *Add New*, add 4 more teams
  -   A Level II Support team made up of specialists. This team will handles issues that require deeper technical knowledge than level I.
  -   A Level III support team made up of IT engineers. This team will tackle higher level technical problems and perform root cause anylysis.
  -   A managment team that manages overall IT operations.
  -   A knowledge managment team to made up of managers and engineers that handle feedback and document new solutions in the knowledge base for future reference

![Capture2](https://github.com/user-attachments/assets/6577128a-4c50-4e52-b76f-dc7af63d2fae)

These teams will be spread across the engineering and support departments that are added at *Admin* >> *Agnets* >> *Departments*

![Capture3](https://github.com/user-attachments/assets/f377aa89-6f07-4df4-bc5c-045fec827053)

<h3>Configure SLAs and help topics</h3>

- Moving on, these teams will need to adhere to service level agreements that can be added at *Admin panel* >> *Manage* >> *Service Level Agreements*
  -   Sev-A (Grace Period: 1 hour, Schedule: 24/7)
  -   Sev-B (Grace Period: 4 hours, Schedule: 24/7)
  -   Sev-C (Grace Period: 8 hours, Business Hours)

![Capture4](https://github.com/user-attachments/assets/8cc21a83-e8d7-4cb2-a450-3f09b2541942)

- Expand the Help topics at *Admin Panel* >> *Manage* >> *Help Topic*, with additional categories: Business Critical Outage, Personal Computer Issues, Equipment Request, Password Reset and Other

![Capture5](https://github.com/user-attachments/assets/7d8fe804-cc49-4e43-bd16-3b8856aabb86)

<h2>Demonstration</h2>

osTicket is now configured to better simulate a helpdesk enviroment with defined teams, SLAs and ticket categories. Practice Tickets can be created by using the link "http://localhost/osTicket/open.php" (from within the VM's browser). To  further simulate real world tickets Chatgpt can be used as the basis for possible scenarios:

![Capture6](https://github.com/user-attachments/assets/730b9924-4553-4092-a536-df601e2420e0)


![Capture7](https://github.com/user-attachments/assets/67870207-6838-4800-96c7-5748cd32007b)


![Capture8](https://github.com/user-attachments/assets/bb99530a-df69-45ae-a658-85ebd568dcd1)


![Capture9](https://github.com/user-attachments/assets/d8c15602-7e96-4b11-8b24-6dd97b6e5188)
