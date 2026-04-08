# osTicket Help Desk Lab

This project simulates a real help desk ticketing system using osTicket and HeidiSQL 

## Tools: 

- Virtual box
- Windows Server 2025
- Windows 11 Pro
- ADDS, DNS, DHCP, and IIS
- PHP
- MySQL and HeidiSQL 

## Step 1: Installed IIS to setup functioning Windows Server 

### IIS in Server Manager
![IIS in Server Manager](screenshots/IIS.png)

## Step 2: Installed PHP and registered it in IIS handler mappings 

### PHP in IIS Handler Mappings
![PHP in IIS Handler Mappings](screenshots/PHP.png)

## Step 3: Installed MySQL and HeidiSQL and created osTicket database 

### osTicket database in HeidiSQL
![osTicket database in HeidiSQL](screenshots/heidisql.png)

## Step 4: Enabled PHP extensions

### PHP.ini file extensions
![PHP.ini file extensions](screenshots/phpextensions.png)

## Step 5: Download and Setup osTicket

### osTicket Roles setup
![osTicket roles setup](screenshots/osticket%20roles.png)

## Step 6: Configured Agents, Roles, Departments, and End Users

### Agents
![](screenshots/osticket%20Agents.png)
### Departments
![](screenshots/osTicket%20departments.png)
### Users
![](screenshots/osticket%20realusersforAD.png)

## Step 7: Configured SLAs and Help Topics 

### Service Level Agreements
![SLAs](screenshots/osTicketSLAs.png)
### Help Topics
![Help Topics](screenshots/Help%20topics.png)

## Step 8: Practice Scenario: Account lockout 

Sent ticket from AD user Bryce Harper which is received by and assigned to Help Desk Agent JT Realmuto. Agent verifies user identity, unlocks account, and forces password change for user. Ticket is resolved. 

### User account locked 

![Locked Account](screenshots/useraccountlocked.png)

### Communication between user and agent

![osticket communications](screenshots/osticketcommunications.png)

### Unlocking user account 

![Unlocking Account](screenshots/unlockingaccount.png)

### User updating password

![User updating password](screenshots/newpassword.png)

### Ticket Resolved 

![Ticket Resolved](screenshots/resolvedticket.png)


