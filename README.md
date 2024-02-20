<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://youtu.be/f08AyZ0xp0M)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Enable IIS in Windows with CGI and Common HTTP Features

- Install PHP Manager for IIS

- Install Rewrite Module 

- Install PHP 7.3.8 

- Install VC_redist.x86.exe 

- Install MySQL 5.5.62



<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/VUxl5Y5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  

</p>
<img src="https://i.imgur.com/rAHBTGG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>


<p>
To start the process of setting up this osTicket system. Enabling the Internet Information Service (IIS), CGI, and Common HTTP Features is an required step to initaite the installation files.
</p>
<br />

<p>
<img src="https://i.imgur.com/qmptDlC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

</p>
<img src="https://i.imgur.com/kq511DH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<p>
The first installation is the PHP Manager for IIS. This allows users to configure various PHP settings, version management, and handler mapping within the IIS Manager interface. There are more features besides those previous mention. The second installation is the Rewrite Module. Overall, it helps in enhancing the flexibility and functionality of websites hosted on IIS servers.

  
</p>
<img src="https://i.imgur.com/GTSIaxY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

</p>
<img src="https://i.imgur.com/LGEq4zh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<p>
These particular steps consist of creating the PHP folder on the C drive. By placing PHP files in this folder, user can easily access and manage them within the ticket system setup.


<br />

<p>
<img src="https://i.imgur.com/E1u1QjE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<p>
<img src="https://i.imgur.com/7zGPJyz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<p>
In this final prerequisite installation. The VC_redist or Visual C++ Redistributable is a set of runtime components required for running applications developed with the C++. This insures ticket system will be deployed, ensuring compatibility and proper functioning of the applcation. Installing MySQL allows users to create, read, update, and delete data in the database. MySQL also provides a reliable and scalable platform for storiing and retrieving data, enabling developers to build robust and dynamic web applications.
</p>
<br />
