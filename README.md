# Metasploit-for-reconnaissance
# Metasploit
Metasploit for reconnaissance in pentesting

# AIM:

To get introduced to Metasploit Framework and to  perform reconnaissance  in pentesting .

## DESIGN STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:

Open terminal and try execute some kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:

Find out the IP address of the attackers system

![image](https://github.com/Pranav-AJ/Metasploit-for-reconnaissance/assets/118904526/319e3d1a-5523-4faa-9a8a-fcf55af1cb51)

invoke msfconsole

![image](https://github.com/Pranav-AJ/Metasploit-for-reconnaissance/assets/118904526/0e27fa0f-7743-4db8-bee6-409d58611ed7)

msf > nmap -sT 192.168.1810/24-p1-1000

![image](https://github.com/Pranav-AJ/Metasploit-for-reconnaissance/assets/118904526/dcbd023b-44ef-4689-968b-5d50f9dfa634)

msf > db_nmap 192.168.181.0/24

![image](https://github.com/Pranav-AJ/Metasploit-for-reconnaissance/assets/118904526/914b342d-ea4d-4e18-9ef7-c6a596830b28)

ls -l

![image](https://github.com/Pranav-AJ/Metasploit-for-reconnaissance/assets/118904526/2816964d-2c8c-47af-b54a-28bad15747f3)

## SEARCH

![image](https://github.com/Pranav-AJ/Metasploit-for-reconnaissance/assets/118904526/5cfe00ae-75c4-4ff4-a36d-662567a110ae)

## INFO

![image](https://github.com/Pranav-AJ/Metasploit-for-reconnaissance/assets/118904526/465e21ce-70c6-4248-a0d0-5e2db8bcacec)

## MYSQL ENUMERATION

db_nmap -sV -sC -p 3306 <metasploitable_ip_address>

![image](https://github.com/Pranav-AJ/Metasploit-for-reconnaissance/assets/118904526/69b5cda0-0f44-4d3e-bc3f-3d0ce0e37959)

SEARCH

![image](https://github.com/Pranav-AJ/Metasploit-for-reconnaissance/assets/118904526/2be2d4ab-2b79-4818-9cf8-f148b6999ca6)

Use the set rhosts command to set the parameter and run the module, as follows:

![image](https://github.com/Pranav-AJ/Metasploit-for-reconnaissance/assets/118904526/2f176c5e-e1ef-4039-8476-07249ba9b723)

![image](https://github.com/Pranav-AJ/Metasploit-for-reconnaissance/assets/118904526/ffb5b658-33e4-4ab0-ad48-e9ad791e3eed)

After scanning, you can also brute force MySQL root account via Metasploit's auxiliary(scanner/mysql/mysql_login) module

![image](https://github.com/Pranav-AJ/Metasploit-for-reconnaissance/assets/118904526/a52c48dd-e48e-4f1c-89ce-fe50899452e0)

/usr/share/wordlists: set PASS_FILE /usr/share/wordlistss/rockyou.txt

![image](https://github.com/Pranav-AJ/Metasploit-for-reconnaissance/assets/118904526/d318053c-100f-404f-9ae9-42b00c66b515)


## RESULT:
The Metasploit framework for reconnaissance is  examined successfully
