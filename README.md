 [flush.bat][1] 
 
--------------------

executes the following commands :

ipconfig /flushdns

ipconfig /release

ipconfig /renew

--------------------


 [systemcheck.bat][2] 

--------------------
executes the following commands :

sfc /scannow

DISM /Online /Cleanup-Image /CheckHealth

DISM /Online /Cleanup-Image /ScanHealth

DISM /Online /Cleanup-Image /RestoreHealth

--------------------

--------------------
 [timedshutdown.bat][3] 
executes the following commands :

shutdown -s -t %Sec%
--------------------

  [1]: https://github.com/VindEi/Cmd-HandyScripts/releases/download/1.0.0/SystemCheck.bat
  [2]: https://github.com/VindEi/Cmd-HandyScripts/releases/download/1.0.0/Network.bat
  [3]: https://github.com/VindEi/Cmd-HandyScripts/releases/download/1.0.0/TimedShutdown.bat
