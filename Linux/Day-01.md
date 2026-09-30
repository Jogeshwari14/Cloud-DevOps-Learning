# Day 01 - Linux Fundamental

## 1. What is Linux?
   - Linux is the Kernel not O.S.
   - Linux is not a UNIX derivative, It was written from scratch.
   - A Linux distribution is the linux kernel and a collection of software that together, create an O.S.

## 2. Linux Features/Advantages
   - Open Source,
   - Secure,
   - Simplified updates for all installed packages.,
   - Light Weight.

## 3. Linux Architecture                 Windows Architecture  
      User                                      User
       |                                         |
     Shell                                     Shell
       |                                         |
     Kernel                               Operating System
       |                                         |
    Hardware                                  Hardware

    - User Interact with Shell
    - Kernel Interact with Hardware
## 4. Linux File System Hierarchy
                                     /- Top Level Root Directory
            _________________________ |________________________         
           |       |       |     |     |      |     |     |      |
         /root   /home   /boot  /etc  /usr   /bin /sbin  /opt  /dev
  
- /root - It is home directory for Root user.
- /home - It is home directory for other user.
- /boot - It contains the bootable files.
- /etc  - It contains all configuration files.
- /usr  - By default software are installed in this directory.
- /bin  - It contains commands used by all users including root user.
- /sbin - It contains commands used by only root user.
- /opt  - Optional application software installed in this directory.
- /dev  - It contains essential device files. This Include Terminal, Dences, USB or any dence attached to the system.
