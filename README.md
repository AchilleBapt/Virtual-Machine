# Virtual Machine




This tutorial provides a step-by-step guide to creating a Virtual Machine using Microsoft Azure.<br />


- ### [How to created a Virtual Machine with Microsoft Azure]

- Open Google Drive
- Click on New, select Google Sheets and create a new spreadsheet
- Name your spreadsheet (e.g., "Payroll System")

<img src="https://i.imgur.com/9x9CXBk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

- ### [Design the Layout]
- Name Cells (Date, ourly Rate, Emplyee's name, Houres, Holiday, Holiday Status, T. Houres, R. Houres, Over Time, Houres Paid	Overtime, Paid, Bonus, Other Deductions, Tax (18.2%))

<img src="https://i.imgur.com/x399TAc.png)" height="80%" width="80%" alt="Disk Sanitization Steps"/>

- ### [Input Formulas]
- Will not put formulas in the 4 first cells, the bonus cell and the Other Seductions cell, you will input your on data. The cells will have their on formulas. 
- (Holiday: FALSE, Holiday Status: =IF(E2,(8*B2)) T. Houres: =D2+D3+D4+D5+D6, R. Houres: =IF(G2>40,40,G2), Over Time: =IF(G2<=H2,"0",G2-H2) Houres Paid: =(H2*B2), Overtime Paid: =(B2*1.5)*I2, Tax (18.2%): =I8*18.2%, Gross Pay: =J2+K2+F2+F3+F4+F5+F6+L2, Net Pay: =I8-N2-M2)


<h1>osTicket - Prerequisites and Installation</h1>

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

Sign in to Azure Portal or create an account
Creat a Resource Group
1 Click on Resouce Group
2 Click on + Create
3 Choose your a Subscription 
4 Name the Resource Group
5 Choose a Region
6 Click on Review + create
7 Click on Create

Navigate to Virtual Machines
Click on + Create > Azure Virtual Machine.

Slect Virtual Machine.



<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
