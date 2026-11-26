# Linux Boot Recovery -- openSUSE LEAP
### Project Overview
#### This project documents the troubleshooting and recovery of a 2010/2011 laptop running openSUSE Leap that had been unable to boot successfully.
####
#### I investigated the boot failure, identified an incorrect filesystem UUID reference in /etc/fstab. and restored the existing installation.
####
## Problem
#### The laptop failed to boot successfully after several years of inactivity
####
## Troubleshooting Approach
- Booted into a root shell using the init=/bin/bash kernal parameter.
- Used lsblk to identify the parition containing the root filesystem
- Used blkid to examine filesystem UUIDs
- /Comapred the partition information against the root filesystem entry in /etc/fstab.
- Identified an incorrect UUID reference.
####
## Skills Demonstated
- Linux boot troubelshooting
- Emergency root-shell recovery
- Block device and filesystem identification
- lblk and blkid
- Filesystem UUID management
- /etc/fstab configuaration
- Linux troubelshooting and problem solving
####
## Techinal Documentation
#### For the detailed troubleshooting process, commands, and explanations, see:
#### [Open the Jupyter Notebook](https://github.com/mckrause2/Linux-Administration-Portfolio/blob/22678b90ca957a3f6fff381245ab63bfab04e1e2/01-openSUSE-Boot-Recover/openSUSE-troubleshooting-walkthrough.ipynb))
####
## Environment
- Operating System: openSUSE Leap
- Hardware: Dell Inspiron 1545
- Tools: lsblk, blkid, /etc/fstab
- Recovery method: init=/bin/bash
