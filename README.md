<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket. In this case, Microsoft Azure is utilized to create an administrative virtual machine for the purpose of hosting osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- IIS
- Rewrite Module
- Microsoft C++
- MySQL Server
- Heidi SQL

<h2>Installation Steps</h2>

<p>

  ![OSTicket Prereq 1](https://github.com/kylewilliamsrr/osticket-prereqs/assets/144828759/321801c7-8aff-4eb5-a018-5df2ed07c056)

</p>
<p>
To install osTicket, you first need a webserver such as IIS with Rewrite Module installed, as well as the latest versions of PHP and MySQl. Start by installing IIS in Windows and enabling important features.
</p>
<br />

<p>

![OSTicket Prereq 2](https://github.com/kylewilliamsrr/osticket-prereqs/assets/144828759/3421f2e6-c1f4-43bc-85cc-bd227b638ff7)

</p>
<p>
Download and Install PHP Manager for IIS.
</p>
<br />

<p>

  ![OSTicket Prereq 4](https://github.com/kylewilliamsrr/osticket-prereqs/assets/144828759/c2ea801b-adb9-4737-acf8-88ae1deb1922)

  
</p>
<p>
Create a Directory in C:\\ for PHP.
</p>
<br />

<p>

  ![OSTicket Prereq 3](https://github.com/kylewilliamsrr/osticket-prereqs/assets/144828759/5f704562-54c7-44b8-9667-50e366a6b1da)
  
</p>
<p>
Install Rewrite Module for IIS.
</p>

<p>

  ![OSTicket Prereq 5](https://github.com/kylewilliamsrr/osticket-prereqs/assets/144828759/f698dd35-9e8b-44c4-b7b7-cd22111b003d)

</p>
<p>
Download and install Microsoft C++ so that applications are running smoothly. 
</p>
<br />

<p>

  ![OSTicket Prereq 6](https://github.com/kylewilliamsrr/osticket-prereqs/assets/144828759/8596b726-61b1-4a94-b54d-176078fd15e4)

</p>
<p>
Download and install MySQL Server.
</p>
<br />

<p>

![OSTicket Prereq 7](https://github.com/kylewilliamsrr/osticket-prereqs/assets/144828759/d60e5ea4-e25c-405f-8e2a-645a2e12cc31)

</p>
<p>
Register PHP.
</p>
<br />

<p>

![OSTicket Prereq 8](https://github.com/kylewilliamsrr/osticket-prereqs/assets/144828759/bf10deee-14a6-43b6-bf13-a4da99fdc6b1)

</p>
<p>
Download and install Heidi SQL so that you can observe and edit data from MySQL.
</p>
<br />

<p>

![Basic Installation](https://github.com/kylewilliamsrr/osticket-prereqs/assets/144828759/81055197-390d-46f6-b45d-138d1b5c2898)

</p>
<p>
Now you can download and install osTicket. Start by inputing a Helpdesk name and a default system email. Based on your departments standard operating procedures input an administrator account email and password. More users can be added later. Lastly, type in your database username and password. 
</p>
<br />

<p>

  ![Installation Complete](https://github.com/kylewilliamsrr/osticket-prereqs/assets/144828759/9b99308e-af2e-48f2-a096-042b925da6d1)

</p>
<p>
Installation is complete. osTicket is now available to open new tickets and resolve and view existing tickets. 
</p>
<br />
