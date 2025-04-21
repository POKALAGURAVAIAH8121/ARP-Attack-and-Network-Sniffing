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

<img width="411" alt="image" src=https://github.com/user-attachments/assets/a1979509-1919-46e1-a331-148c8ada6d2a>


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:

<img width="411" alt="image" src=https://github.com/user-attachments/assets/66912a72-21e2-419c-8e16-bc364d171063>


 dsniff:






In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:


<img width="411" alt="image" src=https://github.com/user-attachments/assets/3ceef506-e63d-4b18-b202-7467e34c55c8>


In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

<img width="411" alt="image" src=https://github.com/user-attachments/assets/3145ae51-1672-4868-ae05-49200e86835e>


Invoke the wireshark and examine the various menus  and controls of the tool:

<img width="411" alt="image" src=https://github.com/user-attachments/assets/314d7100-6cc8-424e-b95d-64fefdf77ed7>


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
