# UbuntuChallenge-InstallSteamTerminalOnly
A journey of me installing steam on ubuntu not using traditional method but with terminal only 

![IMG_1308](https://github.com/user-attachments/assets/ad00ca2a-6a60-4981-b96e-c3e4cc46e141)
As obvious, I installed the latest .deb for steam on my ubuntu pc, I don't plan on installing it manual like the usual person would however as the title of this project says. 

![IMG_1309](https://github.com/user-attachments/assets/7f142184-e754-4021-bfe7-056b216856f8)
I started off with this prompt ChatGPT Suggested: sudo dpkg -i steam.deb
Let's break this down piece by piece:

sudo: This command stands for "SuperUser DO". It allows a regular user to execute commands with the security privileges of the superuser or root.  In essence, it elevates the user's permissions to administrator level for that specific command. It's used when you need to make system-wide changes, install software, or perform tasks that require higher privileges.

dpkg: This is the Debian Package Manager.  It's a command-line tool used to install, remove, and manage .deb packages on Debian-based Linux distributions like Ubuntu.  These .deb packages are the standard software distribution format for these systems.

-i: This is an option (or flag) passed to the dpkg command. It stands for "install".  It instructs dpkg to install the package specified.

steam.deb: This is the name of the package file that dpkg is being asked to install. The .deb extension indicates it's a Debian package.  "steam" suggests this is likely the installation file for the Steam gaming platform.

In summary, the entire prompt sudo dpkg -i steam.deb translates to:

"Install the steam.deb package using the Debian Package Manager with administrator privileges."

![IMG_1311](https://github.com/user-attachments/assets/d450ee27-1845-4d0e-a06f-bcd8cbc9c407)

The above command did not work for me. I later did the work as pictured above and I found out I was installing the deb files in the home directory but not from the downloads directory as intended. 
The download did fail again but it was because it was missing a dependancy known as curl. 

![IMG_1312](https://github.com/user-attachments/assets/d7ba5e20-d08c-44f4-8fcc-17b520d746cd)
In this photo I installed curl and installed the latest verson of the steam .deb file as well

![IMG_1310](https://github.com/user-attachments/assets/51a84e3b-08a9-46ff-9d01-db9d79e49347)
It was a success! From there I was able to update the software and install steam using the wizard.
