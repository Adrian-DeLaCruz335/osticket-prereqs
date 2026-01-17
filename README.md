<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop Protocol (RDP) to securely connect to the virtual machine
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- An active Azure account
- A virtual machine running Windows 10
- Remote Desktop access enabled on port 3389
- The osTicket installation ZIP package

<h2>Installation Steps</h2>

<p>
<img width="600" alt="image" src="https://github.com/user-attachments/assets/d70bbd2d-59d2-440d-9e24-3daf90a468b7" />

</p>
<p>
1. The first step involved deploying a virtual machine in Azure, which would be used to run the osTicket help desk system.
</p>
<br />
</p>

<p>
<img width="765" height="407" alt="image" src="https://github.com/user-attachments/assets/98fd4aac-b815-4092-b0e1-f760df196d23" />
___

</p>
<p>
2. I then downloaded the osTicket installation ZIP file and extracted it to the desktop inside the virtual machine. The extracted files contain everything needed to install and run osTicket.
  </p>
</p>
<br />

<p>
<img width="1060" height="669" alt="image" src="https://github.com/user-attachments/assets/f3aad521-2cd6-44d5-ad2a-7b6f715fff95" />


</p>
<p>
3. Next, Internet Information Services (IIS) was enabled on the Windows machine, with CGI selected under World Wide Web Services → Application Development Features. Enabling CGI allows the server to execute PHP scripts used by osTicket.
  </p>

</p>
<br />

<p>
<img width="843" height="663" alt="image" src="https://github.com/user-attachments/assets/36bd1298-7178-4a1c-81f6-a747869c10cf" />


</p>
<p>
4. In this step, PHP was configured in IIS so the web server can communicate with the PHP interpreter. This allows PHP scripts, which osTicket relies on, to run properly.
</p>
</p>
<br />

<p>
<img width="455" height="582" alt="image" src="https://github.com/user-attachments/assets/b6b67d8e-05a0-4556-8efe-5a1780fd084c" />

</p>
<p>
5. HeidiSQL gives a visual way to work with the database, making it simpler and safer to set up tables, manage users, and control permissions
</p>
<br />
<p>
<img width="452" height="458" alt="image" src="https://github.com/user-attachments/assets/b92a0c94-fa32-432d-85fe-eeb605dae976" />
 <img width="842" height="545" alt="image" src="https://github.com/user-attachments/assets/24f540ea-ed3d-4cc4-bf58-fd6bfb136f5c" />


</p>
<p>
Using HeidiSQL, I set up a database called "osTicket". It will serve as the central storage for all tickets, user accounts, and configuration settings for the help desk system.
</p>
<br />
<p>
<img width="600" alt="image" src="https://github.com/user-attachments/assets/3a6d3ff0-df9b-4da0-95a4-dd7813f28317" />
</p>
<p>
Finally, osTicket is fully installed. Now we can start managing support tickets and users.

</p>
<br />
