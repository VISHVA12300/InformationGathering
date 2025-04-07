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

### Pen Test Tools Categories:
Following Categories of pen test tools are identified for information gathering:

Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network.

http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.

## OUTPUT:
![serverside](/Ex02/InformationGathering/img/Whois.png)

### Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of saveetha.ac.in.

ping saveetha.ac.in

## Output:
![serverside](/Ex02/InformationGathering/img/Screenshot%20at%202025-03-21%2005-50-36.png)

### Finding Hosting Company
get further detail by using ip2location.com website.

## Output:
![serverside](/Ex02/InformationGathering/img/ip2.png)

### History of the website:
## Output:
https://web.archive.org/
![serverside](/Ex02/InformationGathering/img/webarchive.png)

### Webserver Fingerprinting:
Netcat:
nc 172.17.52.118 80
## Output:
![serverside](/Ex02/InformationGathering/img/nc.png)

### nmap:
nmap -p 21 -sV --script=banner ftp.gnu.org
## Output:
![serverside](/Ex02/InformationGathering/img/gnu.png)

### Whatweb:
whatweb infosys.com
whatweb zoho.com
whatweb -v -a 3 172.17.52.201
## Output:
![serverside](/Ex02/InformationGathering/img/webzoho.png)

### httprint:
httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more

## Output:

### Tracing the Location

TCP Traceroute:
sudo traceroute -T www.saveetha.ac.in

## Output:
![serverside](/Ex02/InformationGathering/img/racerou.png)

### UDP Traceroute:

sudo traceroute -U www.saveetha.ac.in
## Output:
![serverside](/Ex02/InformationGathering/img/racerou.png)

### ICMP Traceroute:
sudo traceroute  www.saveetha.ac.in
## Output:
![serverside](/Ex02/InformationGathering/img/sudo.png)





## RESULT:
The information gathering techniques tools/procedure were  identified successfully
