a# ARP-Attack-and-Network-Sniffing
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
![etex41](https://github.com/MDINESH220305/ARP-Attack-and-Network-Sniffing/assets/162429215/62fc5773-7486-4d09-9ca4-513e4d6c4715)



From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![etex42](https://github.com/MDINESH220305/ARP-Attack-and-Network-Sniffing/assets/162429215/5456861e-0afe-4b7e-896c-a4a4f51c8d13)



 dsniff:






In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:

![etex43](https://github.com/MDINESH220305/ARP-Attack-and-Network-Sniffing/assets/162429215/ece05c6e-90d9-4cb7-bca3-4a537b1c65ba)




In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![etex45](https://github.com/MDINESH220305/ARP-Attack-and-Network-Sniffing/assets/162429215/01d7d7f9-0c08-4373-b75a-eafbec3cbfbe)



Invoke the wireshark and examine the various menus  and controls of the tool:
![etex44](https://github.com/MDINESH220305/ARP-Attack-and-Network-Sniffing/assets/162429215/93b7116f-01f2-4cc2-8d12-42b9a6dd4806)


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
