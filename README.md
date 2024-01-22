<h1>VirtualBox Kali Linux</h1>

<b>Disclaimer: This is only for the Kali Linux OS. If you want to install a different OS then adjust the settings for that specific OS.</b>

<h2>Description:</h2>
The project consists of creating a Kali Linux home lab environment on a virtual machine using VirtualBox. You can use this virtual machine to learn test cybersecurity tools and learn new cybersecurity techniques.
<br/>

<h2>Environments Used:</h2>

- <b>VirtualBox</b>
- <b>Kali Linux</b>

<h2>Table of contents:</h2>

[Walk-through](#walk-through)

<h2>Walk-through:</h2>

1. Download [VirtualBox](https://www.virtualbox.org/).

After downloading open VirtualBox and you will see the main screen.
![virtualbox main page](https://github.com/ntieu4328/Virtual-Box-Kali-Linux/assets/156137990/886a6c7c-219b-43f4-b635-2f4755a13311)

As you can see, I already have 2 virtual machines ready. I will walk you through building a new one.

2. Download the [Kali Linux iso](https://www.kali.org/get-kali/#kali-platforms).
   
3. Press "New".
   
![new vm](https://github.com/ntieu4328/Virtual-Box-Kali-Linux/assets/156137990/bcda14d8-1d70-49da-b6b6-46e25123c613)

4. Virtual machine Name and Operating System Page:
![Virtual machine name and operating system](https://github.com/ntieu4328/Virtual-Box-Kali-Linux/assets/156137990/1aeaf8c3-6b77-4b5c-99d5-2050223a207c)

5. Hardware Page:
   
![Hardware](https://github.com/ntieu4328/Virtual-Box-Kali-Linux/assets/156137990/e2bf0529-7f31-4b3b-bce5-71792d591ed4)

<b>Change the Base Memory and Processors to anywhere in the green depending on what you are going to be doing on the VM.</b>
If you are going to run more memory/processor intensive programs then increase.

6. Virtual Hard Disk Page:
   
![virtual hard disk](https://github.com/ntieu4328/Virtual-Box-Kali-Linux/assets/156137990/103990b3-098d-430e-9013-f133f185be15)

<b>20.00 GB should be enough. If you want to increase or decrease the disk space go ahead.</b>

7. Press "Finish"
   
8. Go to Settings

![new vm](https://github.com/ntieu4328/Virtual-Box-Kali-Linux/assets/156137990/bcda14d8-1d70-49da-b6b6-46e25123c613)

9. Go storage --> Click "Empty" --> Click CD icon --> Choose Disk File --> Select Kali Linux iso file

![select kali iso](https://github.com/ntieu4328/Virtual-Box-Kali-Linux/assets/156137990/b85aa655-85bb-4e5c-8266-5b5a76e58757)

<b>Optional:</b>
If you want to make it so you can copy and paste commands or drag and drop files into the VM from the actual OS then follow these steps:
Settings --> General --> Advanced --> Shared Clipboard: Bidirectional --> Drag'n'Drop: Bidirectional

10. Start the Kali Linux Virtual Machine

11. Choose Graphical install:

![Graphical Install](https://github.com/ntieu4328/Virtual-Box-Kali-Linux/assets/156137990/178a3e3c-797c-4dae-85e2-cbea7230e697)

12. Now it will go through the setup process of the actual operating system:
<b>Tailor the settings to what you need</b>
- Language: English
- Location: United States
- Configure the keyboard: American English
- Hostname: kali
- Domain name: kali
- Full name for the new user: user
- Username for your account: user
- Password: **********
- Select your time zone: Pacific
- Partition disks: Guided - use entire disk
- Select disk to partition: Choose the disk
- Partitioning scheme: All files in one partition
- Partition disks: Finish partitioning and write changes to disk
- Write the changes to disks?: Yes
- Choose software to install: Leave default
- Install the GRUB boot loader to your primary drive?: Yes
- Device for boot loader installation: Second option

<b>Kali Linux virtual machine using VirtualBox has been created!!!</b>
