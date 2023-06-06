<p align="center">
<img src="https://i.imgur.com/1DzaLJx.jpg"/>
</p>

<h1>Windows 11 on VirtualBox without an online account</h1>
This is useful if you want to try out Windows 11 without having to sign in with a Microsoft account,
or if you need to install Windows 11 on a machine that doesn't have an internet connection.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: Windows 11 on VirtualBox without an online account](https://youtu.be/_16wpQ-Guog)

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
Step 1: Download and install VirtualBox
	
	-The first thing you need to do is download and install VirtualBox. 
		
	-You can get it from the VirtualBox website. 
	
- https://www.virtualbox.org/
</p>
<p>
<img src="https://i.imgur.com/wDELCwD.png"/>
<img src="https://i.imgur.com/S1zAZN8.png"/>

</p>
<br />


<p>
Step 2: Download the Windows 11 ISO file

- https://www.microsoft.com/en-us/software-download/windows11

</p>
<p>
<img src="https://i.imgur.com/UVCDudX.png" />
</p>
<br />


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
	
	-Click on the "Finish" button.

</p>
<img src="https://i.imgur.com/bW0bN62.png" />
<img src="https://i.imgur.com/FxdQ758.png" />
<img src="https://i.imgur.com/fvbT3b7.png" />
<img src="https://i.imgur.com/7gPS9C3.png" />
<br />


<p>
Step 4: Start the installation of Windows 11
	
	-Click on the "Start" button in VirtualBox
	
	-Press any key to boot from CD or DVD.
	
	-Go into Network Settings, in the “Attached to” drop down menu choose “Not attached” then click OK.
	
	-The installation process will begin. Follow the on-screen instructions to complete the installation.
	
	-Choose "I don't have a product key.
	
	-Choose the windows 11 version you wish to install.
	
	-Choose “Custom: Install Windows Only”.
	
	-Choose “New”. Then click “Next”.
	
</p>
<img src="https://i.imgur.com/9UHX0yv.png" />
<img src="https://i.imgur.com/TvjuEF3.png" />
<img src="https://i.imgur.com/MIr9UIn.png" />
<img src="https://i.imgur.com/Efb8DKo.png" />
<img src="https://i.imgur.com/kosiSVo.png" />
<img src="https://i.imgur.com/kosOpQg.png" />
<img src="https://i.imgur.com/i9quBVr.png" />
<img src="https://i.imgur.com/qJ1F3cz.png" />
<br />

<p>
Step 5: Create a local account
	- On the “Oops, you've lost internet connection” or “Let's connect you to a network” page, 
use the “Shift + F10” keyboard shortcut. 
	
	-In Command Prompt, type the OOBE\BYPASSNRO command to bypass network requirements on Windows 11 and press Enter.

	- The virtual machine will restart.
	
	- Click on “I don’t have internet” and “Continue with limited setup”.
	
	- Continue with the installation.
</p>
<img src="https://i.imgur.com/J0p6ATc.png" />
<img src="https://i.imgur.com/uGTdsJo.png" />
<img src="https://i.imgur.com/mDsbbXc.png" />
<img src="https://i.imgur.com/c9mIVJC.png" />
<br />

<p>
Step 6: Finish the installation with VirtualBox Guest Additions ISO file
	
	- On the bottom menu click on the disc image and choose “Remove disk from virtual drive”.
	
	- On the top menu, go into “Devices” and Choose “Insert Guest Additions CD Image”.
	
	- Install Guest Additions.
	
	- After the reboot you should be able to go fullscreen.
	
	- -Go into Network Settings, in the “Attached to” drop down menu choose “NAT” then click OK.
<p>
<img src="https://i.imgur.com/8RmHadM.png" />
<img src="https://i.imgur.com/91UQsv4.png" />
<img src="https://i.imgur.com/sYMrgdD.png" />
<img src="https://i.imgur.com/Hh3W7wA.png" />
<img src="https://i.imgur.com/q5PHFPb.png" />
<img src="https://i.imgur.com/1DzaLJx.jpg" />

<h1>That’s it!</h1>

</p>
<br />


