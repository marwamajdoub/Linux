# Chapter 2: How to Install Kali Linux on VMware
## Introduction
Kali Linux is a powerful and popular operating system used for penetration testing, ethical hacking, and security research. In this chapter, we will walk you through the process of installing Kali Linux on VMware Workstation Player or VMware Workstation Pro. Using a virtual machine allows you to run Kali Linux on your existing operating system without the need for a separate partition.

## Requirements
Before you start the installation process, make sure you have the following:
- A computer with at least 4 GB of RAM and 20 GB of free hard disk space.
- VMware Workstation Player or VMware Workstation Pro installed on your computer. You can download VMware Workstation Player from the [official website](https://www.vmware.com/products/workstation-player/workstation-player-evaluation.html).
- Kali Linux ISO file or the pre-built VMware image. You can download it from the [official Kali Linux website](https://www.kali.org/downloads/).

## Steps to Install Kali Linux on VMware

### Step 1: Download the Kali Linux ISO or VMware Image
1. Go to the [official Kali Linux download page](https://www.kali.org/downloads/).
2. Select the appropriate version for your system. You can choose either the ISO file for a fresh installation or the pre-built VMware image for a quicker setup.
3. Click the download link and save the file to your computer.

### Step 2: Create a New Virtual Machine (Using ISO File)
1. Open VMware Workstation Player or VMware Workstation Pro.
2. Click on "Create a New Virtual Machine."
3. Select "Installer disc image file (iso)" and browse to the location of the Kali Linux ISO file you downloaded.
4. Click "Next."
5. Select the guest operating system. Choose "Linux" and set the version to "Debian 10.x 64-bit" (or the appropriate version for your ISO).
6. Click "Next."
7. Name your virtual machine (e.g., "Kali Linux") and choose a location to save it.
8. Click "Next."
9. Specify the disk capacity. Allocate at least 20 GB of disk space for Kali Linux.
10. Click "Next."
11. Click "Customize Hardware" to adjust the virtual machine settings. Allocate at least 2 GB of RAM and set the number of processor cores to 2 or more.
12. Click "Close" and then "Finish."

### Step 3: Boot and Install Kali Linux
1. Power on the virtual machine.
2. The virtual machine will boot from the Kali Linux ISO file. Select "Graphical Install" and press Enter.
3. Follow the on-screen instructions to install Kali Linux. These steps are similar to installing on a physical machine:
   - Select your preferred language and click "Continue."
   - Select your location and click "Continue."
   - Choose your keyboard layout and click "Continue."
   - Configure the network settings. If you have an internet connection, you can set up the network. Otherwise, select "Do not configure the network at this time."
   - Enter a hostname for your system and click "Continue."
   - Enter a domain name (optional) and click "Continue."
   - Set up a user account by entering your full name, username, and password. Click "Continue" after each step.
   - Select your time zone and click "Continue."
   - Choose the partitioning method. If you're unsure, select "Guided - use entire disk" and click "Continue."
   - Select the disk to partition and click "Continue."
   - Choose the partitioning scheme and click "Continue."
   - Confirm the changes to the disk by selecting "Finish partitioning and write changes to disk" and click "Continue."
   - The installer will now install the base system. This may take some time.
   - Once the base system is installed, the installer will prompt you to configure the package manager. Select "No" for using a network mirror and click "Continue."
   - Choose whether to install the GRUB boot loader. Select "Yes" and click "Continue."
   - Select the device to install the GRUB boot loader (usually the same disk where you installed Kali Linux) and click "Continue."
   - The installation process is now complete. Click "Continue" to reboot your system.

### Step 4: Post-Installation Steps
1. After the installation is complete and the virtual machine reboots, you will be prompted to log in.
2. Enter the username and password you created during the installation process.
3. Once logged in, you can start exploring Kali Linux and its tools.

### Conclusion
Congratulations! You have successfully installed Kali Linux on VMware. Running Kali Linux in a virtual machine provides a flexible and secure environment for testing and learning. In the next chapter, we will explore the basics of using Kali Linux and some essential tools for penetration testing and security research.
