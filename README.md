# Ex.3(A-C) Virtualization: Installation and Configuration of Oracle VirtualBox & Kali Linux, and Execution of Linux Commands

## Aim:

To set up a virtualized environment using Oracle VirtualBox, install Kali Linux as a guest OS, and execute fundamental Linux commands.

a) Installation and Configuration of Oracle VirtualBox

Aim:
To install and configure Oracle VM VirtualBox.

Pre-requisites:
Machine with Internet access
Minimum 4 GB RAM
Sufficient storage space
Steps:
Download Oracle VM VirtualBox:

Visit Oracle VirtualBox Official Site
Download installer for your OS (Windows/macOS/Linux).
Install Oracle VM VirtualBox (Example: Windows):

Launch Installer → Allow Changes → Click Next.
Choose Installation Options → Click Next.
Accept Network Interface Warning → Click Yes.
Click Install.
Finish Installation and Launch VirtualBox.
Configure VirtualBox:

Open VirtualBox.
Click New → Name VM → Select Type (Linux/Windows) and Version.
Allocate:
Minimum 2 GB RAM
Create Virtual Hard Disk (20 GB recommended).
Start Virtual Machine and provide ISO to install OS.
Result:
Thus, Oracle VM VirtualBox was installed successfully.

3.b) Installation and Configuration of Kali Linux
Aim:
To install and configure Kali Linux in Oracle VirtualBox.

Pre-requisites:
Oracle VM VirtualBox Installed
4 GB RAM and 20 GB Storage Minimum
Kali Linux ISO image
Steps:
Download Kali Linux ISO:

Visit Kali Linux Official Site
Download 64-bit ISO (Installer version).
Create a New Virtual Machine:

Open VirtualBox → Click New.
Name: "Kali Linux" → Type: Linux → Version: Debian (64-bit).
Allocate Memory:

Minimum 2 GB RAM (recommended 4 GB).
Create Virtual Hard Disk:

Select VDI (VirtualBox Disk Image).
Choose Dynamically allocated.
Set Disk size to 20 GB or more.
Configure ISO Image:

Settings → Storage → Controller: IDE → Empty CD → Choose Disk File → Select Kali Linux ISO.
Start Installation:

Boot Virtual Machine → Choose Graphical Install.
Set Language, Region, Keyboard.
Configure Network → Set Hostname (e.g., kali).
Set root password.
Disk Partitioning: Use entire disk → All files in one partition.
Install System → Install GRUB Bootloader → Finish Installation.
Login to Kali Linux:

Use root credentials.
(Optional) Install Guest Additions:

Devices → Insert Guest Additions CD Image → Follow steps inside Kali.
Snapshots:
AWS Account Creation Snapshot

Snapshot 1: Installing Oracle VirtualBox Screenshot 2025-05-03 182046

Snapshot 2: Kali Running in VirtualBox Screenshot 2025-05-03 182258

Result:
Thus, Kali Linux guest OS was installed and configured successfully.

3.c) Execution of Linux Commands in Kali
About Linux:
Open-source operating system.
Kernel manages communication between hardware and software.
Commands are case-sensitive.
Linux Commands:
ls Command

The ls command is used to display a list of content of a directory.

Syntax:
```
ls
```


pwd Command

The pwd command is used to display the location of the current working directory.

### Syntax:
```
pwd
```


mkdir Command

The mkdir command is used to create a new directory under any directory.

### Syntax:
```
mkdir <directory_name>
```


rmdir Command

The rmdir command is used to delete a directory.

### Syntax:
```
rmdir <directory_name>
```
![image](https://github.com/user-attachments/assets/c8a1fee5-a6f1-4fd8-a586-2a49ae0e96cd)


cd Command The cd command is used to change the current directory
### Syntax:
```
cd <directory_name>
```
![image](https://github.com/user-attachments/assets/01f6ec82-b590-47aa-b8b3-62e47c17f85d)


cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content ofthe file, copy the content of one file to another file, and more.

### Syntax:

cat [options] [file_name]


cp Command

The cp command is used to copy a file or directory.

Syntax:
cp [source] [destination]



mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax:
```
mv [source] [destination]
```
![image](https://github.com/user-attachments/assets/17061dfc-2891-4874-b03b-c04c7738899b)


touch Command

Create empty file.

### Syntax:
```
touch [filename]
```
![image](https://github.com/user-attachments/assets/139a1f94-610d-4709-b9eb-a6ccb9265bad)


## vi Command

Edit file contents using editor.

Syntax:
```
vi [filename]
```


![image](https://github.com/user-attachments/assets/cd3e911a-d7bc-422e-b50d-aca3869e7769)


Result:
Thus, various Linux commands were executed successfully in Kali Linux virtual machine.
