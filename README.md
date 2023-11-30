Repair - TODO:

Modify documentation.
Refine main features.
Transition backend to FastAPI, frontend to Vue3 ElementUI.
GUI utilizes web technologies.
Features:

Define interfaces through custom 'api.json'.
Support keyword replacement (e.g., [timestamp], [phone]).
Multi-threaded/asynchronous requests.
Webpage testing/addition of interfaces using Flask.
User-friendly command-line parameter support.
Managed with pipenv package management.
Proxy support for SMS interface calls (HTTP, SOCKS4, SOCKS5).
Uses random User-Agent.
Specify bombing frequency and interval.
Quick Start:

The project can be run as an EXE executable, eliminating the need for a Python environment.
Download the EXE executable from the project's release page.
Create a folder on any disk (excluding C:), move the program there.
Open CMD and navigate to the folder.
Run the command smsboom_pyinstall.exe.
Command Examples:

Bomb one phone number 60 times with 64 threads:

Single
smsboom_pyinstall.exe run -t 64 -p 198xxxxxxxxx -f 60
Bomb multiple phone numbers 60 times with 30 seconds interval and proxies:

Mutli
smsboom_pyinstall.exe run -t 64 -p 138xxxxxxxx -p 139xxxxxxxx -f 60 -i 30 -e
Development:

Download the project with Git.
Configure a virtual environment.
Use pipenv for virtual environment management.
Run the project using pipenv shell and python smsboom.py.
Docker:

Run the program in Docker with provided commands.
