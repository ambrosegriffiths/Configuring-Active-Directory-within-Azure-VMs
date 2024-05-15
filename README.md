
<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>
<br><br/>
<h2>This is our first Virtual Machine call DC1</h2>

![image](https://github.com/ambrosegriffiths/Configuring-Active-Directory-within-Azure-VMs/assets/167513668/5d62cc1f-53dd-4030-a120-a07f713729f0)

<p>This is used to connect a Remote desktop control in order to run Active-Directory</p>

<h2>Created DC1 and Client1 to connect RDC</h2>

![image](https://github.com/ambrosegriffiths/Configuring-Active-Directory-within-Azure-VMs/assets/167513668/95c26d51-d80f-4916-9ec6-46e9c8a323bb)

<h2>Ping DC1 </h2>

![image](https://github.com/ambrosegriffiths/Configuring-Active-Directory-within-Azure-VMs/assets/167513668/d8436677-f1d7-4900-8b38-3db3c4b6b467)


<h3>We use Client 1 public Ip adress to connect Remote desktop connection. We will also use the DC1 private ip add to ping DC1 </h3>

<h2>how ping is working out now</h2>

![image](https://github.com/ambrosegriffiths/Configuring-Active-Directory-within-Azure-VMs/assets/167513668/f2120751-c6ac-45b7-be14-764f92e0aa80)

<h2>Installing Active-Directory in DC1</h2>

![image](https://github.com/ambrosegriffiths/Configuring-Active-Directory-within-Azure-VMs/assets/167513668/e67367b0-910a-43ef-8f2c-73b222806c79)

<h2>Deployed new users in Active-Directory</h2>

![image](https://github.com/ambrosegriffiths/Configuring-Active-Directory-within-Azure-VMs/assets/167513668/071d4baa-a819-4d73-bd9b-ffbb6886df1f)

<h2>Creats user in Admins</h2>

![image](https://github.com/ambrosegriffiths/Configuring-Active-Directory-within-Azure-VMs/assets/167513668/b03804ea-47f0-471a-a2fc-323be71a6713)

<h2>Log into our Client 1 account with our user Jane_admin</h2>

![image](https://github.com/ambrosegriffiths/Configuring-Active-Directory-within-Azure-VMs/assets/167513668/1a500697-408c-4b1c-bd49-197685a594db)

<h2>Allowing all users to be able to log in</h2>

![image](https://github.com/ambrosegriffiths/Configuring-Active-Directory-within-Azure-VMs/assets/167513668/acc86a0e-876f-4526-888e-7744d64e5e9e)

<h2>Creating multiple users accounts</h2
                                      
![image](https://github.com/ambrosegriffiths/Configuring-Active-Directory-within-Azure-VMs/assets/167513668/e7379a20-572c-4021-aafa-0880262d8f68)




