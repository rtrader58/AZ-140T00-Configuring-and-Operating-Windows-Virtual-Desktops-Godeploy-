# AZ-140T00 Configuring and Operating Microsoft Azure Virtual Desktop Lab 4 Errata

## If you save the lab you may get an error Interation required error when attempting to log into the Azure Portal.  Close the portal and do the following:

Open PowerShell as Administrator at the prompt type the following: <br>

W32TM /resync /force  <br>

Or  <br>

If the time sync failed on the VM because the change was too large.  Manually changed the date/time to current date/time  <br>

## Lab 5 – Implement autoscaling in host pools (AD DS) ~60 Minutes

Task 4: Create a scaling plan
Step 7: Capacity threshold (%) is greyed out > Continue on
Step 9: Capacity threshold (%) is greyed out > Continue on

Task 6: Disable host pool autoscaling <br>
Lab is completed after step 3 <br>
Select the next lab from the dropdown menu <br>
