### Install Vagrant: 

[Download's Page](https://www.vagrantup.com/downloads.html)

### Install Oracle Virtual Box: 

[Download's Page](https://www.virtualbox.org/)

### Tips :

1.If you wish to use VirtualBox on Windows, you must ensure that Hyper-V is not enabled on Windows. You can turn off the feature by running this Powershell command:
-> Disable-WindowsOptionalFeature -Online -FeatureName Microsoft-Hyper-V-All

#You can also disable it by going through the Windows system settings:
 Right click on the Windows button and select ‘Apps and Features’.
 Select Turn Windows Features on or off.
 Unselect Hyper-V and click OK.


===========================================================

### Vagrant boxes link : 

[Download's Page](https://app.vagrantup.com/boxes/search)



============================================================
####Example of installing a Centos7 box 


#### Installing steps Centos7 using Vagrant on Windows Machine
-> vagrant init geerlingguy/centos7 
-> vagrant up 

