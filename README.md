# Vagrant( installation and deploying a vm on Virtaul box ) 

# Install Vagrant: https://www.vagrantup.com/downloads.html

# Download link: https://www.vagrantup.com/downloads ( install older versions as latest versions are not supporting latest versions of Virtual box on Windows OS )

# Install Oracle Virtual Box: https://www.virtualbox.org/

# If you wish to use VirtualBox on Windows, you must ensure that Hyper-V is not enabled on Windows. You can turn off the feature by running this Powershell command:
-> Disable-WindowsOptionalFeature -Online -FeatureName Microsoft-Hyper-V-All
-> You can also disable it by going through the Windows system settings:
   1.Right click on the Windows button and select ‘Apps and Features’.
   2.Select Turn Windows Features on or off.
   3.Unselect Hyper-V and click OK.

==================================================================

# Vagrant boxes link : https://app.vagrantup.com/boxes/search

# Example of installing a Centos7 box 

# Installing steps for Centos7 box
-> vagrant init geerlingguy/centos7 
-> vagrant up 

# You should see centos7 machine on the virtual box 

