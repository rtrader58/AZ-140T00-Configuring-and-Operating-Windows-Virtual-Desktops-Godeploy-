# AZ-140T00 Configuring and Operating Microsoft Azure Virtual Desktop All Labs Errata

## If you save the lab you may get an error Interation required error when attempting to log into the Azure Portal.  Close the portal and do the following:

Open PowerShell as Administrator at the prompt type the following: <br>

W32TM /resync /force  <br>

Or  <br>

If the time sync failed on my VM because the change was too large.  Checked the date/time and the VM, manually changed the date/time to current date/time  <br>

# Lab 1 – Deploy host pools and session hosts by using the Azure portal (Entra ID) ~60 Minutes (30 Min)

### Exercise 1: Implement an Azure Virtual Desktop environment using Microsoft Entra joined session hosts

Task 1: Prepare the Azure subscription for deployment of an Azure Virtual Desktop host pool <br>
Step 1: Save the credentials and choose Stay signed in > Select No thanks to sign into edge > Select Cancel on the Welcome to Microaoft Azure <br>
Step 3: Ensure you choose the correct Resource Group <br>

### Exercise: Create a New Group for AVD-DAG
Step 3: Replace the XXXXXX with your initials <br>

### Exercise: Create a New Group for AVD-RemoteApp
Step 3: Replace the XXXXXX with your initials <br>

Task 2: Deploy an Azure Virtual Desktop host pool
Step 3: Student password, use the password for Student in the resources tab, add additional characters to make it 12 characters in length (I added 123) <br>

Task 3: Create an Azure Virtual Desktop application group <br>
Step 8: If you get an error there are no virtual machines - in the host poos > session hosts > restart session host <br>

# Lab 2 - Manage host pools and session hosts by using the Azure portal (Entra ID)

### Exercise 1: Manage an Azure Virtual Desktop environment containing Microsoft Entra joined session hosts

Task 5: Configure RDP properties of the host pool <br>
Lab is finished after step 8 <br>
Choose the next lab from the dropdown <br>

# Lab 3 - Implement monitoring by using Azure Virtual Desktop Insights

### Exercise 1: Implement monitoring of an Azure Virtual Desktop environment

Task 1: Register the Azure subscription with the Microsoft.Insights resource provider <br>
Step 3: Select Re-Register > Continue to refresh screen until status shows registered <br>

Task 2: Create an Azure Log Analytics workspace<br>
Step 2: Should read Name not Virtual network name <br>

Task 3: Set up the Virtual Desktop Insights configuration workbook <br>
Step 3: Check diagnostic settings for host pool: > click unset > select your log analytics workspace
Step 13: Select Session host data settings <br>
Lab is completed after step 29 <br>
Select the next lab from the dropdown menu <br>

# Lab 4 - Connect to session hosts (Entra ID)

### Exercise 1: Validate the functionality of Microsoft Entra joined Azure Virtual Desktop session hosts by connecting to them from a Windows 11 client

Task 3: Subscribe to a Azure Virtual Desktop workspace <br>
Lab is completed after step 29 <br>
Select the next lab from the dropdown menu <br>

## Lab 5 – Implement autoscaling in host pools (AD DS) ~60 Minutes

Task 4: Create a scaling plan
Step 7: Capacity threshold (%) is greyed out > Continue on
Step 9: Capacity threshold (%) is greyed out > Continue on

Task 6: Disable host pool autoscaling <br>
Lab is completed after step 3 <br>
Select the next lab from the dropdown menu <br>

## Lab 6 – Implement Azure Private Link for Azure Virtual Desktop

Task 6: Validate the private endpoint functionality <br>

Before creatdoing step 1 create a NSG <br>
Resource Group - az140-111e-RG <br>
Name - Allowfromprivate <br>
Once created > Go to resource <br>
Add an Inbound rule With following settings <br>
Source - My IP Address <br>
Service - Rdp <br>
Allow <br>
Priority - 300 <br>
Name - AllowCidrBlockRDPInbound <br>

Step 15:  Choose the NSG you created <br>
Skip steps 16 - 20 <br>
Step 22: Enable basic plan has been removed - ignore <br>

Task 7: Allow public network access to a host pool and workspace
Lab is completed after step 7 <br>
Select the next lab from the dropdown menu <br>

## Lab 7 – Create custom session host images by using image templates

### Exercise 1: Create custom session host images by using image templates

Task 1: Create a user-assigned managed identity <br>
Step 4: Replace the random in the Name with your initials <br>

Task 2: Create a custom Azure role-based access control (RBAC) role <br>
Step 3: Paste in Notepad and Replace (Random) with Name of the Managed Identity created in Task 1 > Paste into Cloudshell <br>

Task 6: Build a custom image <br>
Step 2:  Build took a total of 45 minutes to build <br>
