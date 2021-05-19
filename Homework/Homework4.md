# Homework 4 | The Linux File Sysytem

1. Explain the difference between absolute path and relative path:
Absolute path: States the full pathname starting from (/) Always starts from the root
Relative Path: Specifies the pathname starting from the current directory. Always starts from a subdirectory

2. Why Linux uses / instead of \ for its directory paths?
   - It is different because is a unix system and differente from windows it uses (/)
   
3. In Windows, these files are all the same: File FILE file and FiLE. But in Linux this is not the case, Why?
 - Because is case sensitive and different from windows every character is different.
 
4. What is the Filesystem Hierarchy Standard (FHS) and who maintains it?
- It is defined as the directory structure and directory contents in Linux distributions. It is maintained by the Linux Foundation.

5. Directories and what it is used for?
- **/bin**: Contains binary commands that can be used by system administrator, users and scripts.
- **/dev**: contains device files, such as CD/DVD-ROOM drive
- **/etc**: Contains static configuration files
- **/home**: An optional direcotry that might no being included in all linux distributions
- **/lib**: contains shred libraries
- **/opt**: contains shrable add-ons spftware packages
- **/tmp**: Contains Temporary file system
- **/var**: Contains variable data such as long files
- **/proc**: 
- **/usr**: Contains sharable, read-only applications and files

6. How does a period at the beginning of a file name means (example .bashrc)?
- It hides the file in common file managers and for common shell programs.

7. Which command would you use to list all the files inside the /usr/share/ directory?
- The `ls` command

8. If you are working in the /usr/share/icons directory and want to move to your home directory, which command would you use?
- the `cd` command

9. 
