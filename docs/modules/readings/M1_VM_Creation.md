---
title: "Setting up your virtual machine"
layout: single
permalink: /docs/modules/readings/VM/
sidebar:
 nav: modules
output:
  pdf_document: default
  word_document: default
geometry: margin=2.54cm
---

Follow these instructions to create your Virtual Machine for the semester. This material was adapted from ENV 872 - Environmental Data Analytics and developed by Prof. John Fay.

## 1. Creating the VM
* Navigate to Duke's Virtual Computing Manager: [https://vcm.duke.edu/](https://vcm.duke.edu/)

* Log in. (Multifactor authentication is required...)

* Click **Reserve a VM**.

* From the **New Virtual Machine Reservation** list, select *Windows Office 2016* and click **Reserve**. (Alternatively, click the *Available Apps* tab, then select the *Windows Office 2016* option from there...) Accept the Terms of Use and then your VM assembly will begin!
  
  >*It may take some time - up to 30 minutes - for your virtual machine to build. **Please don't delete then re-request a machine while waiting for your machine to be built as this will just slow things down more.** An email will be sent to you when the machine is ready to use. Remember that before you can remote desktop into the machine, you'll need to be using a VPN connection.*
  >
  >> ***NOTE: I've heard reports that build times during peak periods have been in the hours! If you haven't received an email stating your machine is ready, then its still building. Canceling and restarting will only increase build times for everyone.***
  >
  >*Note the name of your machine, something like `vcm-12345.vm.duke.edu`. You can use this to access your machine via remote desktop. Or you can always return to https://vcm.duke.edu/ to log into your machine.*
  >
  >*Also note that VMs are set to power down every night. This is to conserve power. However, if you are likely to use your machine consecutive days or will have processes running over serval days, you may consider switching off the "Automatic power downs" option.*
 
 
 
* When your machine has been built, click the **Remote Desktop** button. (
 
  > ??? *Don't forget that you'll need to use Duke's VPN if you are not doing this from a machine already on the campus network!*
  >
  > ??? *You may wish to save instead of open the remote desktop `vcm-XXXXX.vm.duke.edu.rdp` file. I recommend saving it to your desktop so that you'll have an easy shortcut to your virtual machine.*
  >
  > ??? *The first time you use your machine, it may have to download and install a number of Windows updates, requiring a restart to complete. It's best to let this happen and restart when asked.* 
  >
  > ??? *If you get a "failed to connect" error, it's possible that your machine is not finished being built. Wait a few more moments; if after 20 minutes or so you still cannot connect, seek help.*
  >
  > ??? *You may get a warning stating "The publisher of this remote connection can't be identified. Do you want to connect anyway." That's ok; check the "Don't ask me again" and you won't get this for this machine anymore.*
 
 
* Log in using your Duke NetID **<u>preceded by `WIN/`</u>** (e.g. `WIN/jpfay`) and your Duke password.


## 2. Installing base software using "chocolatey"

* Open Windows PowerShell as administrator
 
  * Right-click Windows PowerShell from the Windows Menu and select Run as Administrator
* At the PowerShell prompt, type the following to install Google Chrome, Notepad++, and 7zip:
  ```powershell
  choco install googlechrome notepadplusplus 7zip -y
  ```
  The script will fetch the installers and install them! You should see some icons on your desktop.



