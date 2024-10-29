<h1>Jira Ticket Management: Tiered Support and Automated Workflow</h1>


<h2>Description</h2>
Jira is a productivity software that can be used to manage tasks, projects, and IT operations. IT is flexible and effective in its application, commonly employed by software and business teams. This project involves becoming familair with Jira and its features for IT ticket management. It involves opening client communication lines, organizing open requests, and prompt resolution of issues. 
<br/>


<h2>Environments and Technologies Used</h2>

- <b>Jira</b>
- <b>Remote Desktop</b>
- <b>Client Support</b>
- <b>Kanban Organization</b>

<h2>Objectives:</h2>

<b>Understand Jira Service Management</b>
- Jira is a powerful and versatile application, and today, we want to understand and focus on features regarding IT management
</br> 
<b>Establish Ticket Life Style</b>
- Following a ticket from the beginning, as an open request to its conclusion as a resolved issue
  
<br/> 

<b>Evaluate Best Practices and Key Features</b>
- Honing in on features that optimize It operations such as automated alerts, ticket prioritzation, and email-ticket conversion
<br/> 

<h2>Configuration Steps:</h2>

__1. Ticket Creation__ <br/>
<br/>
a. Clients have the option to submit tickets with either through a portal, email address, or real-time chats. Tickets submitted through all three channels are collected in one queue for ease of use: <br/>
<img src="https://github.com/henrykim-projects/jira_ticketmanagement/blob/e363cb21fc788ab0b725805b2dfb69e86f742928/images/jira_1.PNG" height="50%" width="50%" alt="Disk Sanitization Steps"/>
<br/> 
<br/>
b. Post-deployment configuration: <br/>
<img src="https://github.com/henrykim-projects/activedirectory_config/blob/7d2b6b00db83259673f2465f2696081894db7a65/images/nc_8.PNG" height="40%" width="40%" alt="Disk Sanitization Steps"/>
<br />  
<br />
c. Creating the main domain forest:  <br/>
<img src="https://github.com/henrykim-projects/activedirectory_config/blob/7d2b6b00db83259673f2465f2696081894db7a65/images/nc_9.PNG" height="40%" width="40%" alt="Disk Sanitization Steps"/>
<br />
<br />
d. After successfully completeing configuration, the domain name and admin account will be visible:  <br/>
<img src="https://github.com/henrykim-projects/activedirectory_config/blob/7d2b6b00db83259673f2465f2696081894db7a65/images/nc_11.PNG" height="40%" width="40%" alt="Disk Sanitization Steps"/>
<br />
<br />
e. With AD Users and Computers, create a organizational unit for admin accounts: <br/>
<img src="https://github.com/henrykim-projects/activedirectory_config/blob/25b2e12ea93c1007e18c14c32d4346ab17dfd628/images/nc_13.PNG" height="50%" width="50%" alt="Disk Sanitization Steps"/>
<br/> 
<br/>
f. Create admin account. Password expiration and change password settings add layers of account management: <br/>
<img src="https://github.com/henrykim-projects/activedirectory_config/blob/25b2e12ea93c1007e18c14c32d4346ab17dfd628/images/nc_15.PNG" height="50%" width="50%" alt="Disk Sanitization Steps"/>
<br/> 
<br/>
<img src="https://github.com/henrykim-projects/activedirectory_config/blob/25b2e12ea93c1007e18c14c32d4346ab17dfd628/images/nc_16.PNG" height="50%" width="50%" alt="Disk Sanitization Steps"/>
<br/> 
<br/>
The account is now in both Users and Admins groups
<img src="https://github.com/henrykim-projects/activedirectory_config/blob/c6a8cd48df4631062bc775b02b18d89e1df486c4/images/nc_18.PNG" height="50%" width="50%" alt="Disk Sanitization Steps"/>
<br />
<br/>
__2. Adding Routing and Remote Access__ <br/>
<br/>
a. In "Add Server Roles", select Remote Access: <br/>
<img src="https://github.com/henrykim-projects/activedirectory_config/blob/fb1fd1b9678440ccd11c9a9ef883e3d27979df78/images/nc_19.PNG" height="50%" width="50%" alt="Disk Sanitization Steps"/>
<br/> 
<br/>
b. We will configure NAT to connect users to the internet through one IP address, the Domain Controller: <br/>
<img src="https://github.com/henrykim-projects/activedirectory_config/blob/fb1fd1b9678440ccd11c9a9ef883e3d27979df78/images/nc_20.PNG" height="50%" width="50%" alt="Disk Sanitization Steps"/>
<br/> 
<br/>
<img src="https://github.com/henrykim-projects/activedirectory_config/blob/fb1fd1b9678440ccd11c9a9ef883e3d27979df78/images/nc_21.PNG" height="50%" width="50%" alt="Disk Sanitization Steps"/>
<br/> 
<br/>
c. Select the Internet connection we labelled from the setup portion of the project (not the internal network)
<img src="https://github.com/henrykim-projects/activedirectory_config/blob/07da8f3778af75e098ea64190f55abed46404224/images/nc_22.PNG" height="50%" width="50%" alt="Disk Sanitization Steps"/>
<br/> 
<br/>
d. The Domain Controller will have a green indicator to confirm network connectivity
<img src="https://github.com/henrykim-projects/activedirectory_config/blob/2a34d15153eb4b8d00f982d95ce0def14f797953/images/nc_23.PNG" height="50%" width="50%" alt="Disk Sanitization Steps"/>
<br/> 
<br/>
__3. DHCP Server Configuration__ <br/>
<br/>
a. Add DHCP in server roles for remote server adiministration: <br/>
<img src="https://github.com/henrykim-projects/activedirectory_config/blob/07da8f3778af75e098ea64190f55abed46404224/images/nc_24.PNG" height="50%" width="50%" alt="Disk Sanitization Steps"/>
<br/> 
<br/>
b. Manually configure the scope, the range of IP addresses, available as well as the subnet mask : <br/>
<img src="https://github.com/henrykim-projects/activedirectory_config/blob/07da8f3778af75e098ea64190f55abed46404224/images/nc_25.PNG" height="50%" width="50%" alt="Disk Sanitization Steps"/>
<br/> 
<br/>
<img src="https://github.com/henrykim-projects/activedirectory_config/blob/07da8f3778af75e098ea64190f55abed46404224/images/nc_26.PNG" height="50%" width="50%" alt="Disk Sanitization Steps"/>
<br/> 
<br/>
c. It is possible to set the duration for distributed IP addresses. This is commonly seen in cafes, where Wi-Fi access is limited to a couple hours, and additional purchase is necessaru for reconnection: <br/>
<img src="https://github.com/henrykim-projects/activedirectory_config/blob/07da8f3778af75e098ea64190f55abed46404224/images/nc_27.PNG" height="50%" width="50%" alt="Disk Sanitization Steps"/>
<br/> 
<br/>
d. Set the default gateway, as well as the DNS server, to the Domain Controller's IP address: <br/>
<img src="https://github.com/henrykim-projects/activedirectory_config/blob/07da8f3778af75e098ea64190f55abed46404224/images/nc_28.PNG" height="50%" width="50%" alt="Disk Sanitization Steps"/>
<br/> 
<br/>
<img src="https://github.com/henrykim-projects/activedirectory_config/blob/07da8f3778af75e098ea64190f55abed46404224/images/nc_29.PNG" height="50%" width="50%" alt="Disk Sanitization Steps"/>
<br/> 
<br/>
e. Now the network is ready to provide IP addresses within a scope for new users. Current leases, policies, and other management tools are available to facilitate user access: <br/>
<img src="https://github.com/henrykim-projects/activedirectory_config/blob/07da8f3778af75e098ea64190f55abed46404224/images/nc_30.PNG" height="50%" width="50%" alt="Disk Sanitization Steps"/>
<br/> 
<br/>
</p>

<h2>Final Thoughts</h2>
Now that DHCP/DNS, Remote Access, and Domain Services are fully configured, we are ready to add users to our network. Active Directory demonstrated many features that give granular control to how and to whom internet is provided. We also saw modes of access management and identity security in the form of organizational units, admin account controls, and IP lease durations. In the final step, we will add users generated through a Powershell script and confirm network connectivity through a DHCP-provided IP address. 
<br><br/>
<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
