# Powerful powershell  
**Prerequisites**  
[Windows Terminal](https://github.com/microsoft/terminal)  
[PowerShell](https://github.com/PowerShell/PowerShell/releases/tag/v7.2.7)  
  
**How to use**  
```
winget install -h --id Git.Git
mkdir ~/.config
cd ~/.config
git clone https://github.com/lobanov4real/pwsh-user-profile.git
cd ~/powershell
./run-install.ps1 in powershell
```
## Manual deploy custom powershell user profile  
**Add path for custom powershell user profile**  
```
echo $env:USERPROFILE\.config\powershell\user_profile.ps1 > $PROFILE    
```
**Create specific directory for powershell user profile**  
```
mkdir ~/.config  
```
**Move to folder**   
```
cd ~/.config
```
**Pull prepared profile**
```
git clone https://github.com/lobanov4real/pwsh-user-profile.git  
```
## List of powershell modules  
- Name Terminal-Icons
- 7Zip4Powershell
- PSWindowsUpdate
- VPNCredentialsHelper
## List of scoop software  
- neovim 
- curl 
- sudo 
- git 
- webtorrent
## list of winget software  
- OhMyPosh
- Google Chrome
- Telegram Desktop
- Bitwarden
- Obsidian
- Speccy
- Slack
- Zoom
- Lightshot
- ProtonVPN
- 7zip
