# Bash en Windows

# Cygwin (git-bash)
Is there a way to access %LocalAppData% with git bash?
Assuming git bash maps Windows environment variables to bash variables then you access them using $VARIABLENAME.

Cygwin bash example:

$ echo $LOCALAPPDATA
C:\Users\DavidPostill\AppData\Local
To list environment variables use env:

$ env
USERDOMAIN=Hal
OS=Windows_NT
COMMONPROGRAMFILES=C:\Program Files\Common Files
PROCESSOR_LEVEL=6
PSModulePath=C:\Program Files (x86)\PowerShell Community Extensions\Pscx3\;C:\Program Files\WindowsPowerShell\Modules;C:\Windows\system32\WindowsPowerShell\v1.0\Modules
CommonProgramW6432=C:\Program Files\Common Files
CommonProgramFiles(x86)=C:\Program Files (x86)\Common Files
FP_NO_HOST_CHECK=NO
LANG=en_US.UTF-8
TZ=Europe/London
HISTCONTROL=ignoredups,ignoredups
DISPLAY=:0.0
...
