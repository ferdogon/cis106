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
![1st step]()