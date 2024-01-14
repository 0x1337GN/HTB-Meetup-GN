# Hack the Box Meetup Vancouver, WA
Information about and resources for our Hack the Box (HTB) Meetup group.

# Meetings
We meet online in our Discord server the second Saturday of every month at 12pm Pacific time.

# Getting Started
1. Join our meetup group and attend our next event: https://www.meetup.com/hack-the-box-meetup-vancouver-wa/
2. Join Hack the Box, if you haven't already: https://app.hackthebox.com/invite
3. Get your computer prepped (see below).
 
# Getting Your Computer Prepped
Though there are many ways to get your computer set up, we recommend using virtualization software, downloading a pre-built Kali Linux virtual machine and using that to connect to Hack the Box.
## Download and Install Virtualization Software
1. Download VMware Workstation Player: https://www.vmware.com/products/workstation-player/workstation-player-evaluation.html
2. Once downloaded, right-click the file and click **Run as Administrator**
3. Follow the on-screen instructions
4. Restart your computer

## Download Pre-built Virtual Machine (VM)
1. Download Kali Linux VM from: https://www.kali.org/get-kali/#kali-virtual-machines
2. Click on the **VMware** option
3. Once downloaded, unzip the file (download 7zip to unzip the file: https://www.7-zip.org/download.html)
4. Open VMware Workstation Player
5. Click **Open a Virtual Machine**
6. Navigate to the unzipped folder from above and select the file ending in .vmx
7. Make any needed changes to the assigned resources
8. Click the play button to start the VM
9. Default username/password: kali/kali

Source: https://www.kali.org/docs/virtualization/import-premade-vmware/

## Connecting to Hack the Box
From within your Kali Linux VM:
1. Log in to your Hack the Box account: https://app.hackthebox.com/
2. Click **CONNECT TO HTB**
3. Click **Machines**
4. Click **OpenVPN**
5. In **VPN ACCESS**, choose a the region you're in, or the closest region available
6. In **VPN SERVERS**, choose the server with the lowest latency (number on the right)
7. Click **DOWNLOAD VPN**
8. Open a terminal in Kali and run (replacing username with your username): sudo openvpn ~/Download/lab_username.ovpn

Source: https://help.hackthebox.com/en/articles/5185687-introduction-to-lab-access

# Getting Started
This is a great overview of how to begin your ethical hacking journey:
https://www.hackthebox.com/blog/learn-to-hack-beginners-bible
