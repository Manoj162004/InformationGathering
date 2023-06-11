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

<<<<<<< HEAD
### Pen Test Tools Categories:  

Following Categories of pen test tools are identified for information gathering:

Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network.
http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.

### output
![1](/im/whois.png)

#### Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of facebook.com.
![ping](im/kali.png)

#### ip2location.com :
Finding Hosting Company
get further detail by using ip2location.com website.
![2](/ip2location/2.png)


#### History of the website:
https://web.archive.org/

![3](/im/webarcive.png)

#### Webserver Fingerprinting:

#### Netcat:
![4](/im/netcat.png)

 
#### nmap:
![5](/im/nmap.png)

#### Whatweb:

![6](/im/whatweb.png)

#### httprint

![7](/im/httprint.png)

### Tracing the Location
#### TCP Traceroute:
![8](/im/tcptraceroute.png)

#### UDP Traceroute:

![9](/im/udptreceroute.png)

#### ICMP Traceroute:

![10](/im/icmptraceroute.png)


### RESULT:
The information gathering techniques tools/procedure were  identified successfully
=======
## Pen Test Tools Categories:
Following Categories of pen test tools are identified for information gathering:

Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network.

http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.


## OUTPUT:
![image](https://github.com/gokul-sureshkumar/InformationGathering/assets/121148715/a2b13e20-b504-4901-a35d-1d53247726af)
## Finding IP adress:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of saveetha.ac.in.
```
ping saveetha.ac.in
```
## Output:
![image](https://github.com/gokul-sureshkumar/InformationGathering/assets/121148715/0f9a3d5c-ae8c-4d1b-a4f5-2a025ed498a5)
## Finding Hosting Company:
get further detail by using ip2location.com website.

## Output:
![image](https://github.com/gokul-sureshkumar/InformationGathering/assets/121148715/bbf4095f-00d4-49b8-a950-ddd504d0d81e)
## History of the wbsite:
## Output:
https://web.archive.org/
![image](https://github.com/gokul-sureshkumar/InformationGathering/assets/121148715/f5166239-895a-4e51-924a-1771ccea3ec8)
## Web server Fingerprint:
## Netcat:
```
nc 172.17.52.118 80
```
## Output:
![image](https://github.com/gokul-sureshkumar/InformationGathering/assets/121148715/2f794aca-900f-4e44-b5e4-9eff031425ab)
## nmap:
```
nmap -p 21 -sV --script=banner ftp.vim.org
```
## Output:
![image](https://github.com/gokul-sureshkumar/InformationGathering/assets/121148715/f8eebdf9-67ff-42c0-ae3b-b126d20576bb)
## Whatweb:
```
whatweb infosys.com
```
```
whatweb zoho.com
```
```
whatweb -v -a 3 172.17.52.201
```
## Output:
![image](https://github.com/gokul-sureshkumar/InformationGathering/assets/121148715/13003241-f18f-4e84-b15d-86a327e9c68c)
## httprint:
```
httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more
```
## Output:
![image](https://github.com/gokul-sureshkumar/InformationGathering/assets/121148715/e1275ae0-7aef-43d9-a8bf-99be791d0070)
## Tracing the Location:
## TCP Traceroute:
```
sudo traceroute -T www.saveetha.ac.in
```
## Output:
![image](https://github.com/gokul-sureshkumar/InformationGathering/assets/121148715/67469d67-bba1-4fa1-925d-1bc35c4146ca)
## UDP Traceroute:
```
sudo traceroute -U www.saveetha.ac.in
```
## Output:
![image](https://github.com/gokul-sureshkumar/InformationGathering/assets/121148715/6f980827-c16f-4865-afff-1de0714937fd)
## ICMP Traceroute:
```
sudo traceroute  www.saveetha.ac.in
```
## Output:
![image](https://github.com/gokul-sureshkumar/InformationGathering/assets/121148715/5b0e049e-98ee-4849-ad1c-de8d8189927e)



>>>>>>> 96aca5ce3f4d803493b2d072aba85aee30a0e1a7


## RESULT:
The information gathering techniques tools/procedure were  identified successfully
