This is a combination of some simple tools I found over the Internet.  

What is this?
If you have bootable pendrive which always there in the usb port and windows always shows annoying pop ups to erase or format the drive for use. You would know you have to eject the drive to stop the pop up from keep popping. Well, this just do that and eject the drive when you start windows. Follow the instructions below to set this up.

Instructions:

removedrive.exe - Put this file in C:\windows\System32

autoUnmount.cmd - Please edit this file and put the drive letter you want to eject instead of "E:" and Put this file in C:\Users\[User name]\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Startup

or 

just open run and enter "shell:startup" and paste it in that folder


Please note that I do not own RemoveDrive cli tool. I just found it over web. 

Thanks