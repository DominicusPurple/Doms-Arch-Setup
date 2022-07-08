# The script is still under development, it will be released in a couple of days!
# Dom's **Arch** Setup
**Bash** script that recreates my ArchLinux setup in minutes.

# Before Running Please Keep In Mind That...
* This script was written with archlinux in mind, it might not work on manjaro or other arch-based distros"
* It is recomended to use a fresh archlinux installation (minimal installation if used archinstall)
* An internet connection is mandatory while running the script.
* Please dont move/delete any files or folders or the script will break. If files have been deleted, repeat the process of cloning the repo.
* If you are on root or used sudo to execute this script do not proceed with installation, instead execute this script without sudo on a user account with sudo privileges!
* You might need to type your password sometimes.
* All pacman and pacaur operations will use --noconfirm so make sure you want everything here (pacaur operations also use --noedit)
* Applications like firefox and neofetch are not installed by the script. you will have to install them yourself (if you want them)

# How To Use:
Enter the following commands.

* `git clone https://github.com/DominicusPurple/Doms-Arch-Setup.git`
* `cd Doms-Arch-Setup`
* `./install.sh`

For my convenience, i added an option to install almost all the applications i use, If you want to install them use `./install.sh extra_apps` instead of `./install.sh`

After install.sh finished and your computer has restarted, enter the following commands.
* ``cd Doms-Arch-Setup``
* ``./after-install.sh``

Follow the steps given there and your setup will look like mine.

# Screenshots
COMING SOON
