---
Name: Shamir R. Rozier
Semester: Fall 22
Course: CIS-106 - Linux Fund.
---

# Week Report 4

## Practice
![p1](../wr4/LetsPractice1.png)
![p2](../wr4/LetsPractice2.png)

## The Filesystem (Some important Directories)

| **Directory** | **Data Stored In Directory**                                                                                                                |
| ------------- | ------------------------------------------------------------------------------------------------------------------------------------------- |
| bin           | Essential Commands                                                                                                                          |
| dev           | Device Files                                                                                                                                |
| etc           | System configuration files                                                                                                                  |
| home          | User home directories                                                                                                                       |
| media         | Mount point for removable media, such as Dvd's and floppy disks                                                                             |
| opt           | Add-on software packages                                                                                                                    |
| proc          | Kernel Information, process control, system hardware information                                                                            |
| srv           | Information relating to services that run on the system                                                                                     |
| usr           | Software not essential for system operation, such as applications                                                                           |
| var           | Dedicated to variable data, such as logs, databases, websites and temporary spool(e-mail etc.) files that persist from one boot to the next |

## Commands to navigate the filesystem

| **Command** | **What it does**                              | **Syntax** | **Example**                    |
| ----------- | --------------------------------------------- | ---------- | ------------------------------ |
| pwd         | prints current working  directory             | `pwd`      | `pwd`                          |
| cd          | changes current working directory             | `cd`       | `cd` + `Insert directory here` |
| ls          | displays information inside a specific folder | `ls`       | `ls` + `Insert Directory here` |

## Key Terms

**Definitions of the following terms** 

* File system : A feature on a computer that orders files in a parent/child system
* Current directory : The folder you are currently accessing
* parent directory : The folder that your current directory is inside of
* the difference between your home directory and the home directory : THE Home directory holds YOUR home directory as well as every other user's 
* pathname : the path from `root` to a certain directory
* relative path : a simplified path that excludes the directories you are already inside of
* absolute path : a path that includes the entire pathway from `root`
* The commands are used for navigating the filesystem
    * pwd
    * ls
    * cd
    * ls
