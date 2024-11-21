# AZ-140T00 Configuring and Operating Microsoft Azure Virtual Desktop Lab 3 Errata

## If you save the lab you may get an error Interation required error when attempting to log into the Azure Portal.  Close the portal and do the following:

Open PowerShell as Administrator at the prompt type the following: <br>

W32TM /resync /force  <br>

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
