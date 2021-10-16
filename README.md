# E-Commerce Course

## Persiapan (Windows OS)

Buka program Powershell dan Run as Administrator

1. Install Chocolatey 
```ps
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```
2. Install VSCode
```ps
choco install vscode -y
```
3. Install XAMPP
```ps
choco install xampp -y
```