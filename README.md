# windows10debloater

Using command as administrator:  
´´´shell
@"%SystemRoot%\System32\WindowsPowerShell\v1.0\powershell.exe" -NoProfile -InputFormat None -ExecutionPolicy Bypass -Command "[System.Net.ServicePointManager]::SecurityProtocol = 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://raw.githubusercontent.com/Sycnex/Windows10Debloater/master/Windows10Debloater.ps1'))"
´´´  
If you want to execute script as powershell directly, you may need to allow it to be ran  
´´´shell
set-executionpolicy unrestricted
´´´


