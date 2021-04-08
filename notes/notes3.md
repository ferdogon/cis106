# Notes 3 | Learning The Bash Shell
## Exploring Desktop Environments
During the 1980s and 1990s, the introduction of the Apple Macintosh and of Microsoft Windows on PCs saw the **command line interface** as the primary user interface replaced by the **Graphical User Interface**(The desktop environment is a GUI which is an implementation of the desktop metaphor)

There are many Graphical Desktops you can choose from.
**Most popular Graphical Desktops are**
* GNOME
* KDE
Windows and macOS users are limited to single Graphical User Interface and Desktop Environment while a Linux user has almost unlimited number of GUI choices.

To discuss the most common Desktop Environments
### Example of a GNOME DE
![](https://i2.wp.com/itsfoss.com/wp-content/uploads/2014/09/Gnome_Ubuntu_1404.jpeg?w=700&ssl=1)
### Example of KDE 
![](https://www.fossmint.com/wp-content/uploads/2018/07/Install-KDE-Plasma-in-Ubuntu.png)

## What is a Shell? :boom:
* CLI : A command-line interface is where the user commands to interact with the computer.
* The shell is a program that takes commands from the keyboard and gives them to the operating system to process and perform. 
* On most Linux systems a program called **bash**:+1: acts as the shell program.

### What is a Terminal? :dart:
It is a program which brings a new window in order to interact wih th shell and it is called  **terminal emulator**.
The terminal requires practice and is easy to learn but hard to master.
*Terminal Picture*
![Terminal Picture](https://media.geeksforgeeks.org/wp-content/uploads/20200618195649/kali-terminal-basic-comamnds.png)


## Managing Software
Basic Terminology about using software in Linux.
Package|Library|Dependency|Repository
-------|-------|----------|---------
Packages are like boxes that contain software, config files etc.|Reusable code that can be used by other programs|Software needed as a foundation for other software|A large collection of Software.
* **APT** is a set of tools for managing Debian Packages
* **SNAPCRAFT** snaps are app packages for desktop, cloud and and IoT that are easy to instal, secure, cross-platform and dependency free.
* **Flatpak** is a next generation technology for packaging distributing and managing software in Linux.
![APT,SNAP,FLATPAK PHOTO](Linux%20Workshop%20_%20Ubuntu%20Software%20installation%20cheat%20sheet.png)
## The Linux Filesystem
**File System:** The way files are stored and organized.
Directory and folder mean the same thing.
Unlike windows Linux always have a single file system tree, regardless of how many drives or storage devices are attached to the computer.
Commonly used File Managers :computer:
* **Nemo** 
  
  ![Nemo](https://linuxhint.com/wp-content/uploads/2020/07/1-70.png)

* **Gnome**

  ![Gnome](https://lh4.googleusercontent.com/zEofHtq0ZvGw9Jy8YuEEQIoNidPsl9h7QuhM5ommrJP5GHx9nCpMypaG21RT5Ckj72bGAtOFM7ZBGp3e5bVWw38CuwPYBMNGVi9jAPLK4y8Vrw2ppwR3Ka9kPiLMBfESwxAL)
  
* **Thunar**
  
  ![Thunar](https://lh3.googleusercontent.com/UdEXUQAamoieoIIXqRDQ0R8DE7JJGoH9u-y7n5Cah7SpeICBbaoxWYEz2yv2DUFAI0YbS9Sxxw1SUm_VGuaqGwUYgV3BzFEaiyJ8tZPucsKumuY-v7dX9zJ3zc5OcxPE96Tr)


Think of the filesystem as a tree where every branch represents a directory(folder).
Where you exactly are currently called the **working directory**. The directory backwards is called the **parent directory** and inwards is called **subdirectory.**
![Filesystem Picture](https://lh6.googleusercontent.com/UCchx0Bc0cifI4QLgR-cGnJVmOHxBezCNTkikqoaQgMBY6K6SFkjQqslV-n3HlQ9_KcsdiK0QCfL-wzcJiz4D-c21sgFVzfpusIt8qcXtiDWylpL47XP02QKL-iC3nf18L_D)

* A path is either relative or absolute. An **absolute path** always contains the root element and the complete directory list required to locate the file.
* A **relative path** needs to be combined with another path in order to access a file. 
![Absolute and Relative Cheat Sheet](absolute%20relative.png)

Some basic commands that are very useful to navigate the filesystem 

![Linux Commands](https://image.slidesharecdn.com/basiccommandsoflinux-161223121032/95/basic-commands-of-linux-4-638.jpg?cb=1482495093)
