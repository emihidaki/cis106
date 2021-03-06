# Ubuntu Installation Handbook 


## Table of Content
- [Ubuntu Installation Handbook Dor Dummies](#ubuntu-installation-handbook-dor-dummies)
  - [Table of Content](#table-of-content)
  - [Introduction](#introduction)
  - [Hardware Requirements](#hardware-requirements)
  - [Software Specifications "Ubuntu 20.04"](#software-specifications-ubuntu-2004)
  - [Set up of the VM Environment](#set-up-of-the-vm-environment)
    - [Installing Virtual Box](#installing-virtual-box)
    - [Downloading Ubuntu 20.04](#downloading-ubuntu-2004)
  - [Setting Virtual Box](#setting-virtual-box)
    - [Step By Step](#step-by-step)
      - [Step 1](#step-1)
      - [Step 2](#step-2)
      - [Step 3](#step-3)
      - [Step 4](#step-4)
      - [Step 5](#step-5)
      - [Step 6](#step-6)
      - [Step 9](#step-9)
      - [Step 10](#step-10)
      - [Step 11](#step-11)
  - [Basic Commands](#basic-commands)
  - [Installing Google Chrome](#installing-google-chrome)
      - [Downloading Google Chrome](#downloading-google-chrome)
      - [Installing Google Chrome](#installing-google-chrome-1)
      - [Starting Chrome](#starting-chrome)
  - [Install Team Viewer](#install-team-viewer)
    - [Download TeamViewer on Ubuntu](#download-teamviewer-on-ubuntu)
    - [Install TeamViewer](#install-teamviewer)
    - [Starting TeamViewer](#starting-teamviewer)
  - [Installing Libre Office](#installing-libre-office)
  - [Installing Discord](#installing-discord)
      - [Download Discord](#download-discord)
      - [Installing Discord on the Command Line](#installing-discord-on-the-command-line)
  - [Installing Zoom](#installing-zoom)
      - [Download Zoom](#download-zoom)
      - [Installing Zoom on the Command Line](#installing-zoom-on-the-command-line)
  - [Ubuntu TroubleShooting](#ubuntu-troubleshooting)
  - [Work Cited](#work-cited)



## Introduction

This manual will be installation and configuation of a Virtual machine. The objective in this project is to guide the user step by step to install the virtual machine and install ubuntu. Also the manual has installation advice for some applications that might be useful for a day to day use of the linux computer. I hope this will be helpful for people that are beginner in this field.
The applications that are include in the manual are; Zoom, Discord, Google Chrome, etc

## Hardware Requirements
 * PC with 8GB of Ram or more
 * PC with 500GB of memory or more
 * Monitor for setup
 * Keyboard and mouse
 Is reccomendable to meet all the specifications in order to a smooth installation and running of the OS.

## Software Specifications "Ubuntu 20.04"
Ubuntu 20.04 is an open source Operating System designed for desktops. It is freely available with both community and professional support. It is also a software that are freely customable and the user can make any change. It is also highly know for it improves in boot speed, app appearance and bundled software. 
   

## Set up of the VM Environment
  ### Installing Virtual Box

  We will download Virtual Box in our computer. In this case we will download it for MAC OS.You can go to the following link to download the latest version [VirtualbBox](https://www.virtualbox.org/)
  * In this case we will be installing the version (6.1)

  ![step 1](Final%20Project%20img/step1.png)

  ### Downloading Ubuntu 20.04

  Before setting up our Virtual Envontment we will download the OS. we can download it drom the following website https://ubuntu.com/download/desktop and save the file in somewhere you could remember.

  ![step2](Final%20Project%20img/step%208.png)

## Setting Virtual Box
  ### Step By Step
   #### Step 1
   Follow the instructions on the screen and drag the installer into the applications folder
   ![step 3](Final%20Project%20img/step2.png)
   
   #### Step 2
   Click on add to add a new machine
   ![step 4](Final%20Project%20img/step3.png)

   #### Step 3
   Select the size of the memory. Those are the recommendations to set up our virtual machine:
   - OS: Ubuntu 20.04 64Bits ISO URL
   - HDD: 50 GB
   - RAM: 2GB
   - Video: 64 MB or Higher
   - Audio Controller: Disabled (audio won't be needed)
   - CPU: 2 Cores
   ![Step 5](Final%20Project%20img/step%204.png)
   
 
   #### Step 4
   In this case we will set up the memory to 2000MB but you can choose the size of your preference
   ![step 6](Final%20Project%20img/step5.png)

   #### Step 5
   Now we are going to create a new virtual hard disk (select that option) and click `create`
      ![step 7](Final%20Project%20img/step6.png)

   #### Step 6
   Now we are going to add the ISO; in our case **Ubuntu 20.04** and click `continue`
   ![step 10](Final%20Project%20img/step12.png)

   #### Step 9
   Now we are going to set up our machine with the specifications mentioned above
   ![step 11](Final%20Project%20img/step13.png)

   #### Step 10
   NOw select where do you want to store the files onf the Virtual Mmachine and select the size of the Hard Disk in this case we choose `40GB` but if your computer can support more than that then feel free to add more GB. and click Create
   ![Step 12](Final%20Project%20img/step14.png)

   #### Step 11
   Now we can customize the specificationson the following screen
   ![step 13](Final%20Project%20img/step15.png)

  - For more tips you can watch the video on **Youtube** [How to Install Ubuntu in a Virtual Machine](https://www.youtube.com/watch?v=2MEN_IX8gJ8)


## Basic Commands

| Managing Files and Directories | Functions | Hadling Files | Functions |
|--------------------------------|-----------|---------------|-----------|
| ls | list files and directories | cat | You can display a content of a file with this command |
| mkdir | create directories | tac | Display the content of a file in reverse order |
| touch | create files | cut | Extract specific section of each line of a file |
| rm | delete files and directories | head | Display first 5 lines of a file
| cp | copy files and directories | tail | Display last 5 lines of a file |

For more examples go to [Linux Commands Examples](https://robertalberto.com/linuxcommands/home.html)



## Installing Google Chrome
Chrome is not an open source software however the installation process is very easy.
   #### Downloading Google Chrome
   First we have to open our command lineby clicking in applications and then Terminal. Once we have our command line open we will insert the following command to download the package.
Command: 
`wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb`

   #### Installing Google Chrome
   We will run the following command to install Chrome and the `.deb` package to our system.
Command: 
`sudo apt install ./google-chrome-stable_current_amd64.deb`

![Installing Chrome](Final%20Project%20img/install_google.png)

   #### Starting Chrome
   Now we can find the application going to **Applications** in the left corner of the screen and clicking in **Internet**

   
   
## Install Team Viewer
To install Team Viewer in our Ubuntu make sure that you are logged in with sudo privileges (This means that you are the main user(The one we create at the beginning))
   ### Download TeamViewer on Ubuntu
   The Version we are about to install is 14.0.12762

1. Open the terminal by clicking the terminal in applications. and insert the following command
   
   `wget https://download.teamviewer.com/download/linux/teamviewer_amd64.deb`

   ![Teamviewer](Final%20Project%20img/install_teamviewer.png)

  ### Install TeamViewer
2. Install the TeamViewer `.deb` package by issuing the following command
   `sudo apt install ./teamviewer_amd64.deb`

   ### Starting TeamViewer
   You can start TeamViewer by going into applications in the left corner of the screen or by inserting in the command line: `teamviewer`

   

## Installing Libre Office
Libre Office is an open source version of Microsoft Office, with this we can create text documents, presentations and calculation sheets just like Word, powerpoint and excel.

To begin with the installation of LIbre Office we will have to update the apt cache. In order to do this we have to type the following command
* command: `sudo apt update`

After dating the cache we will install libre office for that we will insert the following command
command: `sudo apt install libreoffcie`

![libreoffice](Final%20Project%20img/libreofficeversion.png)

Press `'Y'` to continue with LibreOffice

Once LibreoOffice s installed, check the installed version with the command: 
command: `libreoffice --version`

## Installing Discord 
  #### Download Discord
  First we will go to  https://discord.com/download to download the package
  ![download zoom](Final%20Project%20img/discord-download.png)

  #### Installing Discord on the Command Line
  Now that we downloaded the package we will open the command line and enter to the `Downloads` directory using the `cd` command
  Them we will type the following command:
  `sudo apt install ./discord-0.0.14.deb`
  and it will ask the password, insert the password and press `y` to install

  ![discord](Final%20Project%20img/install-discord.png)

## Installing Zoom
   #### Download Zoom
   First we will go to https://zoom.us/download to download the installation package **You have to select Ubuntu** package and press download
   ![download zoom](Final%20Project%20img/download_zoom.png)
   #### Installing Zoom on the Command Line
   Now that we downloaded the package we will open the command line and enter to the `Downloads` directory using the `cd` command
  Them we will type the following command:
  `sudo apt install ./zoom_amd64.deb`
  and it will ask the password, insert the password and press `y` to install
  ![zoom](Final%20Project%20img/install-zoom.png)


## Ubuntu TroubleShooting
1. Using online help: By clicking on the question mark icon in the main menu bar it will bring Ubuntu's extensive collection of formatted help.
2. Use the Man Command: On the command line you can insert `--help` after the command and it will appear all the functions of the command
3. Search on the web: There are a lot of resources in forums, youtube videos and documentation
4. Always ask for help: There are many ways to ask for help in the web.

## Work Cited
Awaisi, Kamran Sattar. “Install LibreOffice on Ubuntu 20.04 and Linux Mint 20.” Linux Hint, 1 Oct. 1969, linuxhint.com/install-libreoffice-ubuntu-linux-mint/. 

“CIS 106: Linux Commands.” Home, robertalberto.com/linuxcommands/home.html. 

“How to Install Ubuntu in a Virtual Machine.” YouTube, YouTube, 2 Feb. 2021, www.youtube.com/watch?v=2MEN_IX8gJ8. 

“How to Install Zoom and Discord in Ubuntu 18.04.” YouTube, YouTube, 1 Apr. 2020, www.youtube.com/watch?v=uk1aFIzj7YM. 

Linuxize. “How to Install Google Chrome Web Browser on Ubuntu 20.04.” Linuxize, Linuxize, 24 Apr. 2020, linuxize.com/post/how-to-install-google-chrome-web-browser-on-ubuntu-20-04/. 

Linuxize. “How to Install TeamViewer on Ubuntu 20.04.” Linuxize, Linuxize, 27 June 2020, linuxize.com/post/how-to-install-teamviewer-on-ubuntu-20-04/. 
