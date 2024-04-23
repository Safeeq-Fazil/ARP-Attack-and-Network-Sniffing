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
![image](https://github.com/Safeeq-Fazil/ARP-Attack-and-Network-Sniffing/assets/118680361/8586f946-928c-43ca-ac75-8a2574ec2fe5)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![image](https://github.com/Safeeq-Fazil/ARP-Attack-and-Network-Sniffing/assets/118680361/bb4291ad-a5f2-4714-be26-0964d4bf143c)


 dsniff:

In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org

## OUTPUT:
![image](https://github.com/Safeeq-Fazil/ARP-Attack-and-Network-Sniffing/assets/118680361/9e42f7c2-1a6c-40a3-a77e-28fb39e7ddb8)




In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![image](https://github.com/Safeeq-Fazil/ARP-Attack-and-Network-Sniffing/assets/118680361/e9db6aaa-9182-4ebe-bedb-3aed04a8761d)



Invoke the wireshark and examine the various menus  and controls of the tool:
![image](https://github.com/Safeeq-Fazil/ARP-Attack-and-Network-Sniffing/assets/118680361/880acf59-f6e8-4116-bd48-a753e4f7ec18)


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
