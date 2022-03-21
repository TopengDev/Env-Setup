# My JavaScript Development Environtment.

This setup is for Windows OS

## Required Programs List

### Atom (IDE) 
- Download from the official link for newest version https://atom.io/ 
- the IDE setup files & configurations can be found in this GitHub repository "https://github.com/TopengDev/ATOM-SETUP.git".
### NodeJS (Javascript runtime environtment)
- download from the official link https://nodejs.org/en/ for newest version.
### Windows Terminal (Terminal for windows OS)
- download from microsoft store https://www.microsoft.com/en-us/p/windows-terminal/9n0dx20hk701,
- install these modules:  
"posh-git"  
"oh-my-posh"
- Type this commands to install:  
```  
Install-Module posh-git -Scope CurrentUser  
Install-Module oh-my-posh -Scope CurrentUser  
```
- Add these lines to $PROFILE (open with notepad)  
>Import-Module posh-git  
>Import-Module oh-my-posh  
>Set-Theme Paradox
- Download and install this font https://github.com/microsoft/cascadia-code/releases  
"Cascadia Code PL"  
"Cascadia Mono PL"  
- Add this line to settings.json(access it from the sttings GUI) in the profiles-default section  
>"fontFace": "Cascadia Code PL"  
### Git (Version control system) 
download from the official link https://git-scm.com/ for newest version.
### PostMan (API testing tool) 
download from the official link https://www.postman.com/
### PuTTY (SSH client for windows) 
download from the official link https://www.putty.org/


### NOTE
some of the files that are available to be provided to this repository will be added in the folder "setup-files", *Note* that some files might be outdated/obsolete, *downloading from the official links is highly recommended.*
