# AZ-140T00 Configuring and Operating Microsoft Azure Virtual Desktop Lab 7 Errata

## If you save the lab you may get an error Interation required error when attempting to log into the Azure Portal.  Close the portal and do the following:

Open PowerShell as Administrator at the prompt type the following: <br>

W32TM /resync /force  <br>

Or  <br>

If the time sync failed on the VM because the change was too large.  Manually changed the date/time to current date/time  <br>

## Lab 7 – Create custom session host images by using image templates

### Exercise 1: Create custom session host images by using image templates

Task 1: Create a user-assigned managed identity <br>
Step 4: Replace the (random) in the Name with your initials <br>

Task 2: Create a custom Azure role-based access control (RBAC) role <br>
Step 3: Paste in Notepad and Replace (Random) with Name of the Managed Identity created in Task 1 > Paste into Cloudshell <br>

Task 6: Build a custom image <br>
Step 2:  Build took a total of 45 minutes to build <br>
