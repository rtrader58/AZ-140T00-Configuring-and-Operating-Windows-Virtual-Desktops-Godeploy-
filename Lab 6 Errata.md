# AZ-140T00 Configuring and Operating Microsoft Azure Virtual Desktop Lab 6 Errata

## If you save the lab you may get an error Interation required error when attempting to log into the Azure Portal.  Close the portal and do the following:

Open PowerShell as Administrator at the prompt type the following: <br>

W32TM /resync /force  <br>

Or  <br>

If the time sync failed on the VM because the change was too large.  Manually changed the date/time to current date/time  <br>

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
