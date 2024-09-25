## Understand File Structure
| Command | Friendly Description |
| ------- | -------------------- |
| `/root` | parent directory. |
| `/bin` | Users Commands |
| `/usr/bin` | Users Commands|
| `/sbin` | Admins Commands |
| `/usr/sbin` | Admins Commands |
| `/etc` | System And Network Configuration Files |
| `/usr` | Man Pages and Documents |
| `/lib` | Modules |
| `/var` | System Logs Files |
| `/opt` | 3rd Party Packages |
| `/tmp` | Temporary Files|
| `/devices` | Physical Devices (Kernel References |
| `/dev` | Logical Volume Human/user references |
| `/home` | User Home Directory |

## Linux Boot Process 
### How does the Linux Boot Process work? 

When you turn on the computer: 
| Process Name | What it does |
| ------- | -------------------- |
| BIOS/PROM |  It will check for bootable devies on the machine |
| MASTER BOOT RECORD(MBR) |  Main Boot Code |
| PARTITION TABLE(PT) | Disk partions information
| BOOT LOADER | It holds all the bootable files (GRUB) |
| KERNEL | It contains all the core operating system files |
| `/`  `/USER` |
| `/ETC/INITTAB` | Default run level information |
| `/ETC/FSTAB` | Gets all the mount Detail |

## Run Levels in Linux
| Run Level | What it is? |
| ------- | -------------------- |
| Run Level 0 | Power Off |
| Run Level 1 | Single User Mode with text mode |
| Run Level 2 | Multiuser Mode With Text Mode (supports all services except NFS & NIS |
| Run Level 3 | Multiuser Text Mode ( Support all services- Default) |
| Run Level 4 | Unused |
| Run Level 5| Multiuser With Graphical Mode|

## Basic Commands
### What are the basic Linux commands I should know?
| Command | Friendly Description |
| ------- | -------------------- |
| `ls` | Think of this as a way to see what’s inside a folder. It shows you a list of files and folders. |
| `cd` | This command lets you move around between folders. It’s like opening different drawers in a cabinet. |
| `cp` | This is for copying files. Imagine you have a piece of paper, and you want to make a copy of it. |
| `mv` | This moves files from one place to another. It’s like taking a book from one shelf and putting it on another. |
| `rm` | This deletes files. It’s like throwing away a piece of paper you don’t need anymore. |


## File Permissions
### What are file permissions in Linux?
File permissions are like rules that say who can read, write, or run a file. Think of it as a library where some books can only be read by certain people.
### How do I change file permissions and ownership?
| Command | Friendly Description |
| ------- | -------------------- |
| `chmod` | This command changes the permissions of a file. It’s like giving someone permission to read or write a book. |
| `chown` | This changes the owner of a file. It’s like saying, “This book now belongs to you.” |


## Package Management
### How do I install and remove software packages?
| Command | Friendly Description |
| ------- | -------------------- |
| `apt` | for Debian/Ubuntu |
| `yum or dnf` | for CentOS/RHEL |

These are like app stores for Linux. You can install new programs or remove ones you don’t need.
### What is the difference between apt, yum, and dnf?
They are just different tools for different versions of Linux. It’s like how some people use Google Play and others use the Apple App Store.


## System Monitoring
### How do I check system resource usage (CPU, memory, disk)?
| Command | Friendly Description |
| ------- | -------------------- |
| `top` | This command shows you what’s happening inside your computer, like how much memory and CPU are being used. It’s like looking at a dashboard in a car. |
### How do I monitor running processes?
| `ps` | This shows you a list of all the programs running on your computer. It’s like seeing a list of all the apps open on your phone. |


## Networking
### How do I configure network settings in Linux?
You can use commands like ifconfig or ip to set up your network. It’s like setting up Wi-Fi on your phone.
### How do I check network connectivity?
| Command | Friendly Description |
| ------- | -------------------- |
| `ping` | This command checks if your computer can talk to another computer. It’s like sending a message and waiting for a reply. |


## Shell Scripting
### What is a shell script and how do I write one?
A shell script is like a recipe that tells your computer what to do step by step. You write it in a text file and then run it.
### How do I automate tasks using shell scripts?
You can write a script to do things automatically, like making your bed every morning without you having to do it.


## User Management
### How do I create and manage user accounts?
| Command | Friendly Description |
| ------- | -------------------- |
| `adduser` | This command creates a new user. It’s like adding a new player to a game. |
| `usermod` | This modifies a user account. It’s like changing the settings for a player. |
### How do I switch between users?
| Command | Friendly Description |
| ------- | -------------------- |
| `su` | This command lets you switch to another user. It’s like logging into a different account on your computer. |


## Text Editors
### What are the common text editors in Linux (e.g., vi, nano)?
| Command | Friendly Description |
| ------- | -------------------- |
| `vi` | Program that let you edit text files. |
| `nano` | Program that let you edit text files. |

It’s like using Notepad or Word.
### How do I use vi or nano to edit files?
| Command | Friendly Description |
| ------- | -------------------- |
| `nano` | Open a file with nano filename. It’s simple and easy to use. |
| `vi` | Open a file with vi filename. It’s more powerful but a bit harder to learn. |


## System Updates
### How do I update my Linux system?
| Command | Friendly Description |
| ------- | -------------------- |
| `apt-get update` | For Debian/Ubuntu |
| `apt-get upgrade` | For Debian/Ubuntu |
| `yum update` | For CentOS/RHEL |

These are commands to update your system. 
It’s like updating apps on your phone.
### How do I manage system updates and upgrades?
You can schedule updates or do them manually. It’s like deciding when to update your phone’s software.


## Troubleshooting
### How do I troubleshoot common Linux issues?
Look at log files in /var/log to see what’s going wrong. It’s like checking a diary to find out what happened.
### Where can I find log files for diagnosing problems?
Log files are usually in the /var/log directory. It’s like a folder where all the important notes are kept.
