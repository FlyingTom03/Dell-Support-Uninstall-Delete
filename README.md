# Dell-Support-Uninstall-Delete
Powershell script to uninstall Dell Support Assist and delete the Support folder.

This was created when we had an issue with dell laptops filling up their storage with SARemediation backup files.

These files reached about 15 GB each and filled the hard drive making the device unusable.

I created a script that can be deployed in Intune and uninstalls the Support Assist app (which auto removes SARemediation)
Then it deleted the Dell SARemediations hidden folder in the C drive, this frees up space and devices work fine.

Everyone welcome to download and use this code, will just need saving as a .PS1 file using Powershell ISE
