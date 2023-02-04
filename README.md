<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- HeidiSQL_12.3.0.6589
- mysql-5.5.62
- osTicket-v1.15.8
- php-7.3.8-nts
- PHPManagerForIIS

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/nM0iEhP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Before installing the prerequisites for osTicket, you want to enable IIS with CGI. IIS being Internet Information Services which is a web server that allows the computer to serve up websites because osTicket runs from a website and we need to configure IIS in order to run osTicket on the computer.
</p>
<br />

<p>
<img src="https://i.imgur.com/zx6neXh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After installing PHP Manager, Rewrite module and a list of others from above, you want to register PHP from within the IIS server and then restart the server.
</p>
<br />

<p>
<img src="https://i.imgur.com/EXVEtRm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After doing a couple of settings on the IIS server, you download and install the HeidiSQL, which is basically a server as well and do a couple of settings on it, after which you install the osTicket software successfully as can be seen from the picture above.
</p>
<br />
