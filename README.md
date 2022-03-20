#############################
This setup is for Windows OS
#############################
List of my required programs
#############################
- Atom (IDE) || Download from the official link for newest version https://atom.io/ 
		the IDE setup files & configurations can be found in this GitHub repository "https://github.com/TopengDev/ATOM-SETUP.git".
- NodeJS (Javascript runtime environtment) || download from the official link https://nodejs.org/en/ for newest version.
- Windows Terminal (Terminal for windows OS) || download from microsoft store https://www.microsoft.com/en-us/p/windows-terminal/9n0dx20hk701,
						install these modules:
							posh-git
							oh-my-posh
						script to install:
							Install-Module posh-git -Scope CurrentUser
							Install-Module oh-my-posh -Scope CurrentUser
						add this to $PROFILE (open with notepad)
							""
							Import-Module posh-git
							Import-Module oh-my-posh
							Set-Theme Paradox
							""
						download and install this font https://github.com/microsoft/cascadia-code/releases
							Cascadia Code PL
							Cascadia Mono PL
						add this line to settings.json(access it from the sttings GUI) in the profiles-default section
							"fontFace": "Cascadia Code PL"
- Git (Version control system) || download from the official link https://git-scm.com/ for newest version.
- PostMan (API testing tool) || download from the official link https://www.postman.com/
- PuTTY (SSH client for windows) || download from the official link https://www.putty.org/


#####
NOTES
#####
direct download files will be provided in this repository in the folder "setup-files", but some files might be obsolete, downloading from the official links is highly recommended.
