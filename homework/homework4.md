# Homework 4 | PART 1

**Explain the difference between absolute path and relative path**


In simple words, an absolute path refers to the same location in a file system relative to the root directory, whereas a relative path points to a specific location in a file system relative to the current directory you are working on.


**Why Linux uses / instead of \ for its directory paths?**

The web is based on the UNIX way of delimiting directories in a path with a slash /. Windows separates directories with backslashes \
The right way depends on it's use. For a path to a local file on a windows machine, use backslash. For a path to a web resource or file located on a UNIX based machine (includes Macs, Linux), use a slash.
The reason .NET's URI uses forward slashes is because it's formatting for use in a web browser.
The server will do all the necessary work to link web resources to files on a hard drive.


**In Windows, these files are all the same: File FILE file and FiLE. But in Linux this is not the case, Why?**

On Windows, we cannot have a file names file and another FILE in the same folder because the windows file system is not case sensitive whereas linux is. That means in linux we can have a file File and FILE in the same folder. Linux treats capital and lower-case letters as different characters.


**What is the Filesystem Hierarchy Standard (FHS) and who maintains it?**
The filesystem standard has been designed to be used by Unix distribution developers, package developers, and system implementors. However, it is primarily intended to be a reference and is not a tutorial on how to manage a Unix filesystem or directory hierarchy. It is maintained by the Linux Foundation.The Filesystem Hierarchy Standard (FHS) defines the directory structure and directory contents in Linux distributions.


**Explain what type of files are stored in the following directories:**


Directory|What is it used for
--|--|
/bin|Contains binary commands that can be used by system admins,users and scripts.
/dev|Contains device files, such as cd/dvd
/etc|Contains static config files which are local.
/home|Optional directory that might not exists in all linux distros
/lib|Contains shared libraries that are loaded when a program is run.
/opt|Contains static shareable add-on software packages.
/tmp|Contains temporary files.
/var|Contains variable data files.
/proc|Contains all the details about Linux system including configuration parameters,processes
/usr|Contains shareable, read-only applications and files.


**How does a period at the beginning of a file name means (example .bashrc)?**

That means that the certain file is hidden and cannot be seen in the file explorer.


**Which command would you use to list all the files inside the /usr/share/ directory?**
ls -a /usr/share/


**If you are working in the /usr/share/icons directory and want to move to your home directory, which command would you use?**
cd


**Explain what these commands do:**
cd .config/.htop; cd ../; ls -lX

*cd../* (means going back 1 parent directory)

*ls -lX* (long lists and sorts alphabetically by entry extension )

*cd .config/ .htop*(To go inside a config file and to the htop of a program which htop works for instant system monitoring software in Linux and Unix systems. You can easily track cpu and similar service / user resource activities simultaneously. )

**John has a lot of files in the directory /var/www/html/webapp. He wants to long list all the files, including hidden files, by modification time (newest first), and with human-readable file sizes. Which command should he use conjuring that his current working directory is:**

*ls -lath /var/www/html/webapp*
