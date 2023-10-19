Juan Miguel Cano								October 12, 2023

## Class 8
## Readings: Virtualization of Windows OS

**Reading**
**What is an ISO file?: Only read sections 1.1 - 1.4 inclusively.**

**1.	What is an ISO File?**

•	An ISO file is a disk image file that contains an exact copy of the data, file structure, and content of a CD, DVD, or even a Blu-ray disc. These files are often used for distributing software, operating systems, or large sets of data, and they can be mounted or burned to physical discs for use. ISO stands for the International Organization for Standardization, which standardized this format.

**2.	How do you write an ISO file to a CD, DVD, or removable media (like a thumb drive)?**

•	To write an ISO file to a CD, DVD, or thumb drive, use disc burning software (e.g., Windows Disc Image Burner, Disk Utility, or third-party tools). Select the ISO file, configure settings, start the process, and wait for completion. Eject the media, and it's ready for use.

**3.	How do you create an ISO file?**

•	On Windows, use software like ImgBurn to create ISOs from discs or files.

•	On macOS, use Disk Utility for creating ISOs from files or folders.


•	On Linux, use commands like "dd" for disc-based ISOs and tools like "mkisofs" or "genisoimage" for files or folders.

**4.	How do you mount an ISO file?**

**•	On Windows:**

o	Right-click on the ISO file.

o	Choose "Mount" from the context menu.

o	The ISO file will be mounted as a virtual drive, and you can access its contents through File Explorer.

**•	On macOS:**

o	Locate the ISO file and double-click it.

o	The ISO file will be mounted as a virtual disk on your desktop, and its contents will be accessible.

**•	On Linux:**

o	Create a directory where you want to mount the ISO file, e.g., sudo mkdir /media/iso.

o	Mount the ISO file using a command like sudo mount -o loop /path/to/your/file.iso /media/iso.

o	The contents of the ISO will be accessible in the mount directory.

**Resources Used:** https://www.lifewire.com/iso-file-2625923

