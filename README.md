<h1>Auto eject drive on startup</h1>

<p>If you have bootable pendrive which always there in the usb port and windows always shows annoying pop ups to erase or format the drive for use. You would know you have to eject the drive to stop the pop up from keep popping. Well, this is just for that... it ejects the drive when you start windows. Follow the instructions below to set this up.</p>


<h1>Instructions:</h1>

This steps works on every windows pc.

* removedrive.exe - <strong>Put this file in C:\windows\System32</strong>

* autoUnmount.cmd - <strong>Please edit this file and put the drive letter you want to eject instead of "E:" and Put this file in C:\Users\[User name]\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Startup</strong>

  or 

  <strong>just open run and enter "shell:startup" and paste it in that folder</strong>
  
One can also keep autoUnmount.cmd file on desktop if you want to do it manually incase computer went to sleep.

<i>Please note that I do not own RemoveDrive cli tool. I just found it over web.</i>



Btw this is my first post.
Thanks.
