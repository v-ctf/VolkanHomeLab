# Active Directory Domain Services Setup on Windows Server 2022

This lab documents the installation and configuration of Active Directory Domain Services (AD DS) on the Windows Server 2022 virtual machine.

---

## Server Manager Configuration

Computer name set to **WinServer22Lab**.  

![Server Manager Computer Name](../images/setup/Server_Manager_Computer_Name_WinServer22Lab.png)  

---

## Installing Active Directory Domain Services

- Server Manager opened, selected roles  
- AD DS role selected and installed  
- Installation confirmed successful  

![Server Manager Roles Selection](../images/setup/winserver22_roles_server_selection.png)  
![Installation Type](../images/setup/winserver22_roles_installation_type.png)  
![AD DS Role Selected](../images/setup/winserver22_roles_server_roles_AD_DS.png)  
![Installation Confirmation](../images/setup/winserver22_roles_installation_confirmation.png)  
![Installation Completed](../images/setup/winserver22_roles_installation_completed.png)  

---

## Verification

- Server Manager shows AD DS role installed  
- PowerShell confirms installation  

![AD DS Installed - Server Manager](../images/setup/ad_ds_installed_server_manager.png)  
![AD DS Installed - PowerShell](../images/setup/ad_ds_installed_powershell.png)  

## AD DS Domain Controller Setup Verification

The server is promoted to a domain controller and the AD DS role is confirmed.

### Server Manager
![AD DS Role – Domain Controller](../images/setup/winserver22_adds_dc_role.png)

### PowerShell
![AD DS Role Verification – PowerShell](../images/setup/winserver22_adds_dc_role_ps.png)
