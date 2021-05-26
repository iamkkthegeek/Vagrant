### Install Vagrant: 

[Download's Page](https://www.vagrantup.com/downloads.html)

### Install Oracle Virtual Box: 

[Download's Page](https://www.virtualbox.org/)

#### Note: Use older version if the above versions are not compatable with each other 

### Tips :

1.If you wish to use VirtualBox on Windows, you must ensure that Hyper-V is not enabled on Windows. You can turn off the feature by running this Powershell command:
  - Disable-WindowsOptionalFeature -> Online -> FeatureName -> Microsoft-Hyper-V -> All

2.You can also disable it by going through the Windows system settings:
  - Right click on the Windows button and select ‘Apps and Features’.
  - Select Turn Windows Features on or off.
  - Unselect Hyper-V and click OK.

---

### Vagrant boxes download link : 

[Download's Page](https://app.vagrantup.com/boxes/search)

---

### Example of installing a Centos7 box 

1.Initialize the VM using `vagrant init`
  - `vagrant init geerlingguy/centos7`

2.Command to bring the box up
  - `vagrant up`

