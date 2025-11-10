<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

-Azure Subscription – to create Virtual Machine.
- Windows 10 VM (4 vCPUs) – created in Azure and accessible with RDP.
- Valid RDP client – to log into the VM remotely.
- osTicket-Installation-Files.zip – available for download (containing osTicket, PHP, MySQL, IIS tools, etc.).
- Stable internet connection

<h2>Installation Steps</h2>

<p>
<img width="1423" height="787" alt="image" src="https://github.com/user-attachments/assets/7b5248cd-2cdd-477c-8233-5dccd5c27e8f" />

</p>
<p>
Step 1: Created VM & Connect → Made an Azure Windows 10 VM → Logged in via Remote Desktop.
</p>
<br />

<img width="1439" height="930" alt="image" src="https://github.com/user-attachments/assets/2bc97e85-4ae1-460c-953f-1113aa6cc30e" />


</p>
<p>
Step 2: Prepared Files → Installed IIS & Dependencies → Enabled IIS with CGI → Installed PHP Manager, Rewrite Module, VC_redist, and MySQL.
</p>
<br />

<img width="1424" height="902" alt="image" src="https://github.com/user-attachments/assets/3fb41116-213e-44bc-af8d-2883865c893f" />


</p>
<p>
Step 3: Set Up PHP → Created C:\PHP → Unzipped PHP 7.3.8 into it → Registered php-cgi.exe in IIS → Restarted IIS.
</p>
<br />
<img width="1422" height="891" alt="image" src="https://github.com/user-attachments/assets/5c5dc209-08bb-4f20-a422-9624786e0323" />
Step 4: Deployed osTicket → Unzipped osTicket v1.15.8 → Moved “upload” folder into C:\inetpub\wwwroot\ → Renamed it osTicket → Restarted IIS.
<img width="1423" height="890" alt="image" src="https://github.com/user-attachments/assets/3953ad11-ce6f-4e60-ab59-e21383b9b9ca" />
Step 5: Configured osTicket → Enabled PHP extensions (imap, intl, opcache) → Renamed ost-sampleconfig.php to ost-config.php → Set permissions


