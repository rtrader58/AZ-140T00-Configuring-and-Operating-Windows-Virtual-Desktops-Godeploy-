# AZ-140T00 Configuring and Operating Microsoft Azure Virtual Desktop Labs 1 Errata

## If you save the lab you may get an error Interation required error when attempting to log into the Azure Portal.  Close the portal and do the following:

Open PowerShell as Administrator at the prompt type the following: <br>

W32TM /resync /force  <br>

Or  <br>

If the time sync failed on the VM because the change was too large.  Manually changed the date/time to current date/time  <br>

# Lab 1 – Deploy host pools and session hosts by using the Azure portal (Entra ID) ~60 Minutes (30 Min)

### Exercise 1: Implement an Azure Virtual Desktop environment using Microsoft Entra joined session hosts

Task 1: Prepare the Azure subscription for deployment of an Azure Virtual Desktop host pool <br>
Step 1: Save the credentials and choose Stay signed in > Select No thanks to sign into edge > Select Cancel on the Welcome to Microaoft Azure <br>
Step 3: Ensure you choose the correct Resource Group <br>

### Exercise: Create a New Group for AVD-DAG
Step 3: Replace the XXXXXX with your initials <br>

### Exercise: Create a New Group for AVD-RemoteApp
Step 3: Replace the XXXXXX with your initials <br>

Task 2: Deploy an Azure Virtual Desktop host pool <br>
Step 3: Student password, use the password for Student in the resources tab, add additional characters to make it 12 characters in length (I added 123) <br>

Task 3: Create an Azure Virtual Desktop application group <br>
Step 8: If you get an error there are no virtual machines - in the host poos > session hosts > restart session host <br>
