# To perform information gathering techniques

## AIM:

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
![310213356-03c9de39-715f-4544-914f-a8dc81b7af08](https://github.com/vatsan143/InformationGathering/assets/147368204/ce755ea7-ff07-4e32-973c-55c45cd7d6fd)

## Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of saveetha.ac.in.

```
ping saveetha.ac.in
```
## Output:
![310213446-bf690154-8daf-4f61-b28b-c14d218fde32](https://github.com/vatsan143/InformationGathering/assets/147368204/582600ed-bf3d-4620-be7c-a56240bc1069)


## Finding Hosting Company
```
get further detail by using ip2location.com website.
```

## Output:


## History of the website:
## Output:
https://web.archive.org/
![310213528-9944d113-4c67-47ee-a07c-2d23d30c16b6](https://github.com/vatsan143/InformationGathering/assets/147368204/d93ca50e-d22f-4792-aafe-14ca1484608c)

## Webserver Fingerprinting:
### Netcat:
```
nc 172.17.52.118 80
```
## Output:

![310213565-ddb8f37a-c510-41d3-8e56-d06e1dfbdf03](https://github.com/vatsan143/InformationGathering/assets/147368204/ed74dbdd-74db-402c-bf78-7b25aa339e40)

## nmap:
```
nmap -p 21 -sV --script=banner ftp.vim.org
```
## Output:
![310213594-ae6c16e5-c427-42fc-aad4-d7a6b7139843](https://github.com/vatsan143/InformationGathering/assets/147368204/373fb1f2-5be9-4482-9531-29d562cd4123)


### Whatweb:
```
whatweb infosys.com
```
```
whatweb zoho.com
```
```
whatweb -v -a 3 172.17.52.201
```
### Output:
![310213635-c966fc93-52b2-4567-84d8-db493e80bd8e](https://github.com/vatsan143/InformationGathering/assets/147368204/62c3bf87-ec78-4461-a618-4a6a2bed98f6)
![310213674-bd11482a-c1f8-4e84-8aff-dbd63e2a048a](https://github.com/vatsan143/InformationGathering/assets/147368204/e180548d-0b60-4e80-9e97-d235f2e2c1ea)




## httprint:
```
httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more
```
### Output:

![310213707-b7e7f96c-b475-4868-8c6b-46303b8871b1](https://github.com/vatsan143/InformationGathering/assets/147368204/8da0c0e7-974f-4b2b-bbe3-e6e9efbce0d3)

## Tracing the Location
### TCP Traceroute:
```
sudo traceroute -T www.saveetha.ac.in
```
## Output:
![310213745-449f9bc4-1e0e-440d-8383-f4581e79874e](https://github.com/vatsan143/InformationGathering/assets/147368204/7bf5f242-0336-45d8-acb0-6687fa217c67)


## UDP Traceroute:
```
sudo traceroute -U www.saveetha.ac.in
```
## Output:
![310213779-9af636da-8d1c-41e3-be72-598e57a10e57](https://github.com/vatsan143/InformationGathering/assets/147368204/1e94d32e-f799-4e7b-9676-ae1d42978e52)


## ICMP Traceroute:
```
sudo traceroute  www.saveetha.ac.in
```
## Output:
![310213869-98f95c5e-46c9-4e03-a395-1d7901d03f74](https://github.com/vatsan143/InformationGathering/assets/147368204/4200088d-2ff3-4a67-9773-e8b08cea98d8)

## RESULT:
The information gathering techniques tools/procedure were identified successfully
