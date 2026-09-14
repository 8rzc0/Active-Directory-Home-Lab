# Active Directory Home Lab

## Objective

The Active Directory Home Lab project was created to build hands-on experience with Windows Server administration and common Tier 1 IT support tasks. The lab focused on deploying Active Directory Domain Services, joining Windows clients to a domain, managing users and groups, configuring account policies, and practicing common support tasks such as password resets, account unlocks, and access management.

### Skills Learned

- Configured Active Directory Domain Services on Windows Server 2022
- Joined Windows client systems to an Active Directory domain
- Created and managed user accounts
- Performed password resets and account unlocks
- Configured account lockout and password policies
- Managed user permissions and access
- Improved troubleshooting and Windows Server administration skills
- Practiced basic Group Policy administration

### Tools Used

- Windows Server 2022
- VirtualBox
- Active Directory Domain Services
- Group Policy Management
- Windows 10
- Windows 11
- Remote Desktop Protocol (RDP)

## Lab Implementation


### Active Directory Domain Services & Domain Controller

Installed AD DS, created a new forest, and promoted Windows Server 2022 to a domain controller.

<img width="1024" height="768" alt="Apng" src="https://github.com/user-attachments/assets/fd65927b-bb0b-470d-ad5a-55b71264bf88" />

*Ref 1: Selecting the AD DS services to install*

<img width="1024" height="768" alt="VirtualBox_Windows Server 2022_25_08_2026_13_22_28" src="https://github.com/user-attachments/assets/58608167-dce1-4457-bd7c-d0be86fb1491" />

*Ref 2: Confirming the AD DS services install* 

### User Account Management
Created and managed domain user accounts through Active Directory Users and Computers.

<img width="800" height="600" alt="VirtualBox_Windows Server 2022_25_08_2026_15_22_47" src="https://github.com/user-attachments/assets/8936c9ab-e05a-4ac2-b1a3-65f305cc1da4" />

*Ref 3: Creating a new user*

<img width="800" height="600" alt="VirtualBox_Windows Server 2022_25_08_2026_15_24_17" src="https://github.com/user-attachments/assets/0da9d684-4af8-4401-a5a7-d1776b78ee50" />

*Ref 4: Confirming new users account creation*
 
### Domain-Joined Windows Clients
Joined Windows 10 and Windows 11 clients to the AD domain and verified successful domain connectivity.

<img width="1024" height="768" alt="VirtualBox_Windows 10_25_08_2026_16_21_30" src="https://github.com/user-attachments/assets/8c11896c-6621-47bf-a6e8-938d5f3a12e8" />

*Ref 5: Adding Windows 10 user to the domain*

<img width="1024" height="768" alt="VirtualBox_Windows 10_25_08_2026_16_25_48" src="https://github.com/user-attachments/assets/55aa0556-5262-458c-bd5e-504df4abdc27" />

*Ref 6: Confirming that the Windows 10 user has successively been added to the domain* 

<img width="1024" height="768" alt="VirtualBox_Windows 11_25_08_2026_15_59_27" src="https://github.com/user-attachments/assets/42f1fecc-cc43-4fd6-8461-94138e7973b6" />

*Ref 7: Adding Windows 11 user to the domain*

<img width="1024" height="768" alt="VirtualBox_Windows 11_25_08_2026_16_01_29" src="https://github.com/user-attachments/assets/2383defc-fca9-4685-8a84-3ce141b1c4f7" />

*Ref 8: Confirming that the Windows 11 user has successively been added to the domain*

<img width="800" height="600" alt="VirtualBox_Windows Server 2022_25_08_2026_16_24_10" src="https://github.com/user-attachments/assets/74730bd6-7239-492a-84dc-af99ff4701f1" />

*Ref 9: Confirming that both users have successively been added to the domain*

### Group Policy & Account Security
Configured domain password and account lockout policies through Group Policy Management.

<img width="800" height="600" alt="VirtualBox_Windows Server 2022_25_08_2026_17_37_59" src="https://github.com/user-attachments/assets/84dd480e-47c5-4e1e-bfb9-72c53ffd27dd" />
 
*Ref 10: Default GPO password settings*

<img width="800" height="600" alt="VirtualBox_Windows Server 2022_25_08_2026_17_38_24" src="https://github.com/user-attachments/assets/951327d0-ddfc-4358-aa45-aa50c9768969" />

*Ref 11: Changing password age to 90 days*

<img width="800" height="600" alt="VirtualBox_Windows Server 2022_25_08_2026_17_39_10" src="https://github.com/user-attachments/assets/9171eaa1-49d6-4cf2-af87-272c8da815cd" />

*Ref 12: Changing password lock out duration to 360 minutes*

<img width="800" height="600" alt="VirtualBox_Windows Server 2022_25_08_2026_17_42_59" src="https://github.com/user-attachments/assets/8dbced28-3b1f-44b4-ad9b-d3233bf670f6" />

*Ref 13: Confirming GPO changes*

### Account Support & Troubleshooting
Practiced common Active Directory support tasks including resetting user passwords and unlocking locked domain accounts.

<img width="1024" height="768" alt="VirtualBox_Windows 11_25_08_2026_17_51_09" src="https://github.com/user-attachments/assets/302a42e7-81cd-4a49-b9d2-55f936f7b4ea" />

*Ref 14: Account locked out*

<img width="800" height="600" alt="VirtualBox_Windows Server 2022_25_08_2026_17_52_33" src="https://github.com/user-attachments/assets/72b26cc2-8954-4e2e-8205-9c942dc44de8" />

*Ref 15: Unlocking account*

<img width="1024" height="768" alt="VirtualBox_Windows 11_25_08_2026_17_52_51" src="https://github.com/user-attachments/assets/11eec459-f441-42b6-8493-87d1aad14106" />

*Ref 16: Confirming successful account unlock*

### Remote Administration
Enabled Remote Desktop and successfully connected to the Windows Server from a domain-connected Windows client.

<img width="800" height="600" alt="VirtualBox_Windows Server 2022_25_08_2026_16_28_52" src="https://github.com/user-attachments/assets/2a7f777b-6bbf-4bdd-b779-287cf6882a35" />

*Ref 17: Allowing RDP requests to the Windows Server*

<img width="1024" height="768" alt="VirtualBox_Windows 10_25_08_2026_16_30_36" src="https://github.com/user-attachments/assets/6fa7bb71-399d-4b50-a34d-10ad11c50825" />

*Ref 18: Entering the Windows Server IP address* 

<img width="1024" height="768" alt="VirtualBox_Windows 10_25_08_2026_16_31_47" src="https://github.com/user-attachments/assets/88d1afd3-198f-4773-b029-c69d939cc56e" />

*Ref 19: Entering Windows Server Credentials*

<img width="1024" height="768" alt="VirtualBox_Windows 10_25_08_2026_16_33_57" src="https://github.com/user-attachments/assets/0224413c-a961-4f8d-958c-9f036e7d5a5b" />

*Ref 20: Successful RDP connection from a Windows 10 Pro user*
