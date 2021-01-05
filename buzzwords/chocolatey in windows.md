# CHOCOLATEY IN WINDOWS? // use this because it super handly and install and uninstallation is super easy and good....
search for powershell and open it as administator. </br>
and get excution policy </br>
unrestrited </br>
if then set executation policy ALLSigned


now you are done


visit: !()https://chocolatey.org/install

then



Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))


paste in powershell



now you are all set ....

