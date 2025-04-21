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

![324250921-23e1040d-0d30-47d2-a9d1-73b1988ca8a3](https://github.com/user-attachments/assets/b1c302a2-60aa-4a95-ad6b-cde30f207040)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:

![324251000-fe31b4ad-3f7c-420c-98b2-a744753543b3](https://github.com/user-attachments/assets/411c3af3-f690-49dc-a6b9-ef6e82c5414b)


 dsniff:

In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:

![324251080-0bc59714-d2a5-459c-9e7d-517c82037ae1](https://github.com/user-attachments/assets/8bb347ae-c0c2-4a78-8e3c-e027542b97ba)



In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

![324251192-d8000a29-e6c6-4ea3-ae36-9c66f9d139a6](https://github.com/user-attachments/assets/ec13b40c-fb06-4124-bce8-54c1ed1f5854)


Invoke the wireshark and examine the various menus  and controls of the tool:

![324251213-19ba4623-276d-43d9-8105-7395b509f9ae](https://github.com/user-attachments/assets/72a78a53-296d-4e7a-bb92-4808b1dd335f)

## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
