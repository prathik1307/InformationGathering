# InformationGathering
Information Gathering Techiques

# To perform information gathering techniques

# AIM:

To perform information gathering techniques using kali linux 

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:
Open terminal/browser and try execute necessary commands/use url to perform information gathering


## OUTPUT:

<img width="1261" height="792" alt="image" src="https://github.com/user-attachments/assets/f6446669-57b1-4cf7-bc5a-6d0bcce3ab1f" />

##Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of saveetha.ac.in.
ping saveetha.ac.in

## output:
<img width="1051" height="321" alt="image" src="https://github.com/user-attachments/assets/6cdc5a3e-7e61-4eb4-9222-92e3b5483b35" />

## Finding Hosting Company:
get further detail by using ip2location.com website.
## output:
<img width="1230" height="569" alt="image" src="https://github.com/user-attachments/assets/43011139-d24c-4449-976e-904890cde32d" />

## History of the website:
## Output:
<img width="1131" height="742" alt="image" src="https://github.com/user-attachments/assets/f1a17f58-c5ab-4f2c-bee3-c38e15a5b517" />

## Webserver Fingerprinting:
## Netcat: nc 172.17.52.118 80:
## output:
<img width="1089" height="742" alt="image" src="https://github.com/user-attachments/assets/625b6912-63e5-4c1d-9719-e69a9e5e0cc9" />

## nmap:
## nmap -p 21 -sV --script=banner ftp.vim.org:

## output:
<img width="1063" height="424" alt="image" src="https://github.com/user-attachments/assets/b576bac1-062c-4b5d-b862-14a5596faaaf" />

## Whatweb:
## whatweb infosys.com
## whatweb zoho.com
## whatweb -v -a 3 172.17.52.201
## OUTPUT:

<img width="1129" height="212" alt="image" src="https://github.com/user-attachments/assets/8e31c7b1-f33e-4449-acac-abd1a34cf3b6" />

## httprint:
## httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more
## OUTPUT:
<img width="937" height="833" alt="image" src="https://github.com/user-attachments/assets/76239150-1797-4045-ba24-3cb584eb1db9" />

## Tracing the Location
## TCP Traceroute:
## sudo traceroute -T www.saveetha.ac.in
## OUTPUT:

<img width="1015" height="169" alt="image" src="https://github.com/user-attachments/assets/0a458283-6664-48b3-bac1-d90618630105" />

## UDP Traceroute:
## sudo traceroute -U www.saveetha.ac.in
## OUTPUT:

<img width="1021" height="241" alt="image" src="https://github.com/user-attachments/assets/583d16b7-af41-4a07-a30c-1a6db12a2cc1" />

## ICMP Traceroute:
## sudo traceroute www.saveetha.ac.in
## OUTPUT:

<img width="1009" height="166" alt="image" src="https://github.com/user-attachments/assets/6b428932-c865-4d79-a1cf-3d0e3d5a4693" />


## RESULT:
The information gathering techniques tools/procedure were  identified successfully
