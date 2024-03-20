 ![flush.bat][1] 


{
executes the following commands :
--------------------
ipconfig /flushdns
--------------------
ipconfig /release
--------------------
ipconfig /renew
--------------------
}

systemcheck.bat

{
executes the following commands :
--------------------
sfc /scannow
--------------------
DISM /Online /Cleanup-Image /CheckHealth
--------------------
DISM /Online /Cleanup-Image /ScanHealth
--------------------
DISM /Online /Cleanup-Image /RestoreHealth
--------------------
}

timedshutdown.bat

{
executes the following commands :
--------------------
shutdown -s -t %Sec%
--------------------
}

  [1]: https://i.stack.imgur.com/xK0Tz.png
  [2]: https://i.stack.imgur.com/vKfnI.png
  [3]: https://i.stack.imgur.com/Hzk29.png
