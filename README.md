<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>Windows 11 on VirtualBox without an online account</h1>
This is useful if you want to try out Windows 11 without having to sign in with a Microsoft account,
or if you need to install Windows 11 on a machine that doesn't have an internet connection.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: Windows 11 on VirtualBox without an online account](https://youtu.be/LOzmM5ZjKi0)

<h2>Environments and Technologies Used</h2>

- VirtualBox (Virtual Machine/Compute)
- Windows 11 ISO

<h2>Operating Systems Used </h2>

- Windows 11</b> (22H2)

<h2>List of Prerequisites</h2>

- Download and install VirtualBox
- Download the Windows 11 ISO file
- Create a new virtual machine
- Start the installation of Windows 11
- Finish the installation with VirtualBox Guest Additions ISO file
- Link to Installation files used in the tutorial. 
	- https://www.virtualbox.org/
	- https://www.microsoft.com/en-us/software-download/windows11
		
		
<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/50g1Hcp.png" alt="osTicket logo"/>

</p>
<p>
Step 1: Download and install VirtualBox
		-The first thing you need to do is download and install VirtualBox. 
		-You can get it from the VirtualBox website.
		- https://www.virtualbox.org/

</p>
<br />

<p>
<img src="https://i.imgur.com/NvK35hU.png" height="80%" width="80%" />
</p>
<p>
Step 2: Download the Windows 11 ISO file
		- https://www.microsoft.com/en-us/software-download/windows11

</p>
<br />

<p>
<img src="https://i.imgur.com/tVzhLQc.png" height="80%" width="80%" />

</p>
<p>
Step 3: Create a new virtual machine
		-Once VirtualBox is installed, open it up and click on the "New" button.
		-In the "Name" field, type a name for your virtual machine. 
		-In the "Folder" drop-down menu, select the location you want your virtual machine to be installed.
			- I personally like to install it on an external SSD in its own folder.
		-In the "ISO Image" drop-down menu, select the "Win11_22H2_English_x64v2.iso" ISO image we just downloaded.
		-Check the box "Skip Unattended Installation".
			-We will choose the Windows 11 version later on.
		-Click on the "Next" button.
		-Allocate memory and storage for your virtual machine.
		-In the "Memory" field, enter the amount of memory that you want to allocate to your virtual machine. 
		-The recommended amount of memory is 4 GB.
		-In the "Processors" field enter the amount of CPUs that is reasonable for your system.
		-In the "Virtual Hard Disk" section, click on the "Create a virtual hard disk now" button. 
		-Choose a size that is at least the minimum size recommended which is 64GB.
		-Click on the "Create" button.

</p>
<br />

<p>
<img src="https://i.imgur.com/NvK35hU.png" height="80%" width="80%" />
</p>
<p>
Step 4: Start the installation of Windows 11
		-Click on the "Start" button in VirtualBox
		-Press any key to boot from CD or DVD.
		-The installation process will begin. Follow the on-screen instructions to complete the installation.
		-Go into Network Settings, in the “Attached to” drop down menu choose “Not attached” then click OK
</p>
<br />

<p>
<img src="https://i.imgur.com/Z3e5wdX.png" height="80%" width="80%" />
</p>
<p>
Step : Create a local account
- Download and install (PHPManagerForIIS_V1.5.0.msi) https://drive.google.com/file/d/1VizgW40b2A6ndsOh0RE4sASGbfOa54rg/view?usp=drive_link
</p>
<br />

<p>
<img src="https://i.imgur.com/LmmaKIZ.png" height="80%" width="80%" />
</p>
<p>
Download and install the Rewrite Module (rewrite_amd64_en-US.msi) https://drive.google.com/file/d/1bF7qvZlsmzSpX2ApytklyoU91P8FdXwg/view?usp=drive_link
</p>
<br />

<p>
<img src="https://i.imgur.com/vjVDFcn.png" height="80%" width="80%" />
</p>
<p>
Download and install download PHP 7.3.8 (php-7.3.8-nts-Win32-VC15-x86.zip) https://drive.google.com/file/d/1UGPXw3MQ6rU7J7vqVkJIupUo29q-t7ch/view?usp=drive_link
</p>
<br />

