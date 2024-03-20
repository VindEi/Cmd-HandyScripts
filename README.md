flush.bat 
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
