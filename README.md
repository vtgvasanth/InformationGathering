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
## Pen Test Tools Categories:
Following Categories of pen test tools are identified for information gathering:

Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network. http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.
## OUTPUT:
![Screenshot 2025-03-09 194851](https://github.com/user-attachments/assets/c1eb9e69-2455-44cc-9d2c-1ea7211797eb)
## Finding IP Address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of facebook.com.

## OUTPUT
![image](https://github.com/user-attachments/assets/7ad8dade-8ddc-4089-be2c-4710dd79474f)
## Finding Hosting Company
get further detail by using ip2location.com website.

## OUTPUT
![image](https://github.com/user-attachments/assets/0abf08d0-2143-425c-95a4-1e2dd9c5ae11)
## History of the website:

## OUTPUT
![image](https://github.com/user-attachments/assets/7704b631-bc17-4da1-afd1-5298303757b1)

## Webserver Fingerprinting:
## Netcat:
sudo nc example.com 80 GET / HTTP/1.1 Host: example.com

## OUTPUT 
![image](https://github.com/user-attachments/assets/81943885-52db-4108-93bd-6400f5ef161b)
## nmap

## OUTPUT
![Screenshot 2025-03-09 202416](https://github.com/user-attachments/assets/50ec68ab-4860-4374-8b7c-9715456a5258)
## Whatweb

## OUTPUT 
![Screenshot 2025-03-09 202639](https://github.com/user-attachments/assets/4308a703-2ada-4b2a-9c90-2d46706ef131)
## httprint

## OUTPUT
![image](https://github.com/user-attachments/assets/3667bce5-6978-480f-b442-e23e7b5fdc05)
## Tracing the Location
***TCP Traceroute: sudo traceroute -T www.facebook.com***

![Screenshot 2025-03-09 203333](https://github.com/user-attachments/assets/cc027c8e-e720-40f3-9dd6-0ec28d29ef3a)
***TCP Traceroute: sudo traceroute -U www.facebook.com***
![Screenshot 2025-03-09 203500](https://github.com/user-attachments/assets/bce9d7cb-2d8f-4647-bf94-1a8a83053c12)
***TCP Traceroute: sudo traceroute www.facebook.com***

![Screenshot 2025-03-09 203706](https://github.com/user-attachments/assets/b9c38718-7975-4908-bb5a-f1a40e9b2576)

## RESULT:
The information gathering techniques tools/procedure were  identified successfully
