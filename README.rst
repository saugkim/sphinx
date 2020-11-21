.. role:: raw-html(raw)
    :format: html
    
*************************
Set up GUI in Ubuntu LTS
*************************

How to set up GUI in Ubuntu LTS
####################################

This is for setup graphic user interface in Ubuntu LTS(ubuntu lts already installed).

Current version: Ubuntu 20.04 

Installing WSL with GUI using VcXsrv
*****************************************
Windows Subsystem for Linux is a feature in Windows 10 where you can install and run Linux applications on Windows 10. Though keep in mind ...
Dhanar Santika blog, https://medium.com/@dhanar.santika/installing-wsl-with-gui-using-vcxsrv-6f307e96fac0

Download VcXsrv  
**********************
VcXsrv is a Windows X-server based on the xorg git sources.  
https://sourceforge.net/projects/vcxsrv/

XLaunch and setup
**************************
 - choose window option, One Large Window or Fullscreen option?
 - choose Start no client. 
 - check Disable access control.  
blank screen will appear. close or keep open.

Install Desktop Environment for WSL 
******************************************
 - XFCE4, KDE, GNOME, LXDE, Cinnamon, MATE, etc.

In ubuntu WSL 
    * $ sudo apt-get install xfce4  
    * $ echo 'export DISPLAY=:0.0' >> ~/.bashrc 


Exit and re-run ubuntu and start!
    * $ startxfce4


In Bash, open Windows File Explorer:
    * explorer.exe .
