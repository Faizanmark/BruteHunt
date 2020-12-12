# About BruteHunt 1.0
BruteHunt is a SSH, FTP, Telnet, PostgreSQL, RDP, VNC brute forcing tool with Hydra, Medusa and Ncrack. BruteHunt can work with any Linux distros if they support Python 3.

# Features of BruteHunt
* SSH, FTP, Telnet, PostgreSQL, RDP, VNC with Hydra (recommended)
* SSH, FTP, Telnet, PostgreSQL, RDP, VNC with Medusa
* SSH, FTP, Telnet, PostgreSQL, RDP, VNC with Ncrack
* Scan victim's ports with Nmap

# Install and run on Linux
You have to install Python 3 first:
* Install Python 3 on Arch Linux and its distros: <code>sudo pacman -S python3</code>
* Install Python 3 on Debian and its distros: <code>sudo apt install python3</code>

You have to install Hydra, Medusa, Nmap and Ncrack too:
* On Arch Linux and its distros: <code>sudo pacman -S nmap hydra medusa ncrack</code>
* On Debian and its distros: <code>sudo apt install nmap hydra medusa ncrack</code>

      git clone https://github.com/Faizanmark/BruteHunt
      cd BruteHunt
      python3 BruteHunt.py

# To-do list
* Create wordlist with crunch
