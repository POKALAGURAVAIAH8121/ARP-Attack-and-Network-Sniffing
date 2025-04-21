# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks

# AIM:

To explore network sniffing and ARP Attacks

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:


### Step 3:
Open terminal and try execute some kali linux commands

## ARP Attacks:  
ARP spoofing: A hacker sends fake ARP packets that link an attacker's MAC address with an IP of a computer already on the LAN. 
Boot kali and Windows7 virtual machines.
In windows 7 give the command arp -a
## OUTPUT:

<img width="411" alt="image" src=https://github.com/user-attachments/assets/3fecf253-6acc-40e6-9907-33b24b008a3e>


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:

<img width="411" alt="image" src=https://github.com/user-attachments/assets/8190a8d0-0c00-4c60-b887-8cf37157119d>


 dsniff:
 





In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:

<img width="411" alt="image" src= https://github.com/user-attachments/assets/1fed5eb7-b2d6-47b5-acd9-fbf2fcc47e0d>




In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

<img width="411" alt="image" src=https://github.com/user-attachments/assets/3dec17d0-1b1b-4b23-a8ce-b8f3a7b63135>




Invoke the wireshark and examine the various menus  and controls of the tool:

<img width="411" alt="image" src=https://github.com/user-attachments/assets/1f957f10-53bf-4fb2-8181-7dd58f6fa6a7>

## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
