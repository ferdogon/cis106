# NOTES LECTURE 2 INSTALLING UBUNTU
## WHAT IS VIRTUALIZATION?
**Virtualization** is the replication of hardware to simulate a virtual machine inside a physical machine. It is basically using computer inside a computer as long as the hardware specifications are good enough to handle.

###There are 2 general types of Virtualization ;
* Server-side Virtualization:computer:
* Client-Side virtualization:man:
**Main difference between them is where the virtualization is taking place**:+1:

Client-side Virtualization | Server-side virtualization
---|---|
|![Client-Side Virtualization](https://rb.gy/rlb6ms)|![Server-side Virtualization](https://rb.gy/bgadpi)|

For Client-side Virtualization the computer needs a ***hypervisor***.
A ***hypervisor*** is a software that allows the management of virtual machines.
There are 2 types of hypervisors.
* Type 1 Hypervisor(Runs on the hardware)
  Example : Citrix XenServer
* Type 2 Hypervisor(Runs on a host operating system)  
  Example : Oracle Virtualbox
## INSTALLING UBUNTU IN A VIRTUAL MACHINE
For installing ubuntu we need a Hypervisor(software that allows the management of virtual machines).
To install ubuntu we will install **Oracle Virtualbox** which is an example of Type 2 Hypervisor.
The link for the Hypervisor can be found [here](https://www.virtualbox.org/wiki/Downloads) or if that does not work here https://www.virtualbox.org/wiki/Downloads

### Steps to install and configure your Hypervisor with Ubuntu
* Click the new button to open a dialog and name your virtual machine and if you are not sure about what you are doing use **Ubuntu** which will automatically choose the type and the version for you.
* 
![1st step](https://brb.nci.nih.gov/seqtools/images/ubuntu/image005.png)

Secondly you need to adjust your **memory(RAM)** to be allocated for this virtual machine.If you are not sure leave it to recommended for now and change it later.

![2nd step](https://brb.nci.nih.gov/seqtools/images/ubuntu/image007.png)

After selecting the ram amount , Accept the default create a virtual hard disk drive option and click **"Create"**.
![3rd step](https://brb.nci.nih.gov/seqtools/images/ubuntu/createVM.png)

Continue to accept the default 'VDI' drive file type and click 'Next' button.
![4th step](https://brb.nci.nih.gov/seqtools/images/ubuntu/image009.png)

After this step you can either choose Dynamically allocated or fixed size but fixed size will give you a **better performance.**
![5th step](https://brb.nci.nih.gov/seqtools/images/ubuntu/image010.png)

This step is to choose the memory which depends totally on your storage and preference but allocating less than **8GB** may cause system errors.:-1:

![6th step](https://brb.nci.nih.gov/seqtools/images/ubuntu/image011.png)


Once the virtual machine has been created we need to install ubuntu into the virtual machine. In order to install Ubuntu the ISO file is required to integrate Ubuntu into the hypervisor. 
The link to the iso files can be found **[here](https://ubuntu.com/download/desktop)**

After downloading the iso file , Select your new virtual machine and click 'Settings' button. Click on 'Storage' category and then 'Empty' under Controller:IDE. Click "CD/DVD" icon on right hand side and select the ubuntu ISO file to mount. It should look similar to this.
![7th step](https://brb.nci.nih.gov/seqtools/images/ubuntu/image017.png)

Back to Oracle VM VirtualBox Manager, click on the new Ubuntu virtual machine and hit 'Start' button. Now you shall see a 'Welcome' screen. Ubuntu will ask a few simple questions such as;
* Click 'Install Ubuntu' button.
* Click 'Continue' button
* Make sure 'Erase disk and install Ubuntu' option is selected and click 'Install Now' button.
* Ubuntu will ask you a few more questions. If the default is good, click 'Continue' button.

* **After reaching the Who are you? question make sure to note the username and password that you will create and choose a secure password with characters and numbers included.**
![8th step](https://brb.nci.nih.gov/seqtools/images/ubuntu/image030.png)

After the installation is completed the system will prompt for a restart.After the restart Ubuntu is ready to use.:+1:
###Virtualbox Extension Pack
Even though it is **not necessary** Virtualbox Extension Pack can be useful in many ways.
VirtualBox Extension Pack is a binary package intended to extend the functionality of VirtualBox. The Extension pack adds many functionalities to the hypervisor  such as USB 2.0 and USB 3.0 devices, VirtualBox RDP, disk encryption, NVMe and PXE boot for Intel cards.
The link for that can be found [here](https://www.virtualbox.org/wiki/Downloads)
