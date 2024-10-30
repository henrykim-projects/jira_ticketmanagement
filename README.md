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

<b>Establish Ticket Life Style</b>
- Following a ticket from the beginning, as an open request to its conclusion as a resolved issue
 
<b>Evaluate Best Practices and Key Features</b>
- Honing in on features that optimize It operations such as automated alerts, ticket prioritzation, and email-ticket conversion 


<h2>Configuration Steps:</h2>

__1. Ticket Creation__ <br/>
<br/>
a. Clients have the option to submit tickets with either through a portal, email address, or real-time chats. Tickets submitted through all three channels are collected in one queue for ease of use: <br/>
<img src="https://github.com/henrykim-projects/jira_ticketmanagement/blob/e363cb21fc788ab0b725805b2dfb69e86f742928/images/jira_1.PNG" height="50%" width="50%" alt="Disk Sanitization Steps"/>
<br/> 
<br/>
b. Requests can be submitted by category such as "Common Requests" or more specific hardware or application issues. <br/>
<img src="https://github.com/henrykim-projects/jira_ticketmanagement/blob/4111203b8a55746b597952c64a6fc1b12c7e2622/images/jira_2.PNG" height="50%" width="50%" alt="Disk Sanitization Steps"/>
<br /> 
Once an option is selected, the user can elaborate and provide information on their issue:
<img src="https://github.com/henrykim-projects/jira_ticketmanagement/blob/4111203b8a55746b597952c64a6fc1b12c7e2622/images/jira_3.PNG" height="50%" width="50%" alt="Disk Sanitization Steps"/>
<br />  
<br />
__2. Responding to Tickets__ <br/>
<br/>
a. Submitted tickets appear in a queue. The queue contains helpful information such as request type, the reporter, summary, time created, and status. 'Open' indicates tickets that are ready for work while 'Waiting for Support' tickets need a response from the IT team.: <br/>
<img src="https://github.com/henrykim-projects/jira_ticketmanagement/blob/9f40d4fe26704066f4697824795eda5001725df0/images/jira_6.PNG" height="50%" width="50%" alt="Disk Sanitization Steps"/>
<br/> 
<br/>
b. The status of the ticket can be further changed. For example, they can be elevated to a higher tier for further support, cancelled when the user no longer needs support, and resolved for when the issue is done: <br/>
<img src="https://github.com/henrykim-projects/jira_ticketmanagement/blob/02921ef59197addbe046df564ca11e07da68fc4c/images/jira_14.PNG" height="50%" width="50%" alt="Disk Sanitization Steps"/>
<br/> 
When the IT staff decides to assign themselves a ticket, the issue's urgency and impact are indicated lending to triage and risk management for issues that affect a higher volume of devices or severity:  
<img src="https://github.com/henrykim-projects/jira_ticketmanagement/blob/02921ef59197addbe046df564ca11e07da68fc4c/images/jira_7.PNG" height="50%" width="50%" alt="Disk Sanitization Steps"/>
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
