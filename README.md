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

## Pen Test Tools Categories:  

Following Categories of pen test tools are identified for information gathering:

Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network.
http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.

## OUTPUT:
![Screenshot 2024-03-27 082227](https://github.com/kanagavel7/InformationGathering/assets/162578954/5ae8f3d1-3018-407b-826d-2b96e2fa1e28)

## Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of facebook.com.

## OUTPUT:
![Screenshot 2024-03-27 082530](https://github.com/kanagavel7/InformationGathering/assets/162578954/4e5264a8-6d7c-41ca-90c4-eeecee81a4e0)

## Finding Hosting Company
get further detail by using ip2location.com website.

## OUTPUT:
![Screenshot 2024-03-27 082739](https://github.com/kanagavel7/InformationGathering/assets/162578954/01b9c278-cae0-4c92-a745-fe8ed6463950)

## History of the website:
## OUTPUT:

https://web.archive.org/

![Screenshot 2024-03-27 083236](https://github.com/kanagavel7/InformationGathering/assets/162578954/172adc5e-39ca-4640-8464-ebd3149954e6)

# Webserver Fingerprinting:

## Netcat:
sudo nc example.com 80
GET / HTTP/1.1
Host: example.com

## OUTPUT:
![Screenshot 2024-03-27 083718](https://github.com/kanagavel7/InformationGathering/assets/162578954/08c293bf-0a80-48fd-9d76-a8763551f337)

## nmap:
## OUTPUT:
![Screenshot 2024-03-27 084257](https://github.com/kanagavel7/InformationGathering/assets/162578954/1565ceb6-b9fa-434e-8793-75a98d568ca2)

## whatweb:
## OUTPUT:
![Screenshot 2024-03-27 084431](https://github.com/kanagavel7/InformationGathering/assets/162578954/ce3a7520-d87a-4796-bd96-2f9fa15b52fd)
![Screenshot 2024-03-27 084646](https://github.com/kanagavel7/InformationGathering/assets/162578954/56877cc9-0f12-4cff-a31c-bef1644a6bb3)
![Screenshot 2024-03-27 085247](https://github.com/kanagavel7/InformationGathering/assets/162578954/85496a96-7979-43e7-8dc1-6372f4e8ca85)

## httprint;
## OUTPUT:
![Screenshot 2024-03-27 090117](https://github.com/kanagavel7/InformationGathering/assets/162578954/a5cb8b06-319e-43ef-a63a-9c55bedbc7c1)

# Tracing the Location
# TCP Traceroute:
sudo traceroute -T www.google.com
## OUTPUT:
![Screenshot 2024-03-27 090213](https://github.com/kanagavel7/InformationGathering/assets/162578954/4f0c36e5-c1a0-41d2-880a-f341670b8e1f)

# UDP Traceroute:
sudo traceroute -U www.google.com
## OUTPUT:
![Screenshot 2024-03-27 090317](https://github.com/kanagavel7/InformationGathering/assets/162578954/88108d16-99d8-4b9d-9ee4-75007ee77bda)

# ICMP Traceroute:
sudo traceroute  www.google.com
## OUTPUT:
![Screenshot 2024-03-27 090541](https://github.com/kanagavel7/InformationGathering/assets/162578954/a56d530b-732b-4de2-801d-201a8c519521)


## RESULT:
The information gathering techniques tools/procedure were  identified successfully
