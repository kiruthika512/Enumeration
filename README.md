![ex2](https://github.com/kiruthika512/Enumeration/assets/135616605/5bd904fe-7993-4a07-ad5d-c71a14852214)# Enumeration
Enumeration Techniques

# Explore Google hacking and enumeration 

# AIM:

To use Google for gathering information and perform enumeration of targets

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various Google hacking keywords and enumeration tools as follows:


### Step 3:
Open terminal and try execute some kali linux commands

## Pen Test Tools Categories:  

Following Categories of pen test tools are identified:
Information Gathering.

Google Hacking:

Google hacking, also known as Google dorking, is a technique that involves using advanced operators to perform targeted searches on Google. These operators can be used to search for specific types of information, such as sensitive data that may have been inadvertently exposed on the web. Here are some advanced operators that can be used for Google hacking:

site: This operator allows you to search for pages that are within a specific website or domain. For example, "site:example.com" would search for pages that are on the example.com domain.
Following searches for all the sites that is in the domain yahoo.com
![ex2](https://github.com/kiruthika512/Enumeration/assets/135616605/fcda9cf9-0af8-4c1a-94b6-5ba54b2c9d29)


filetype: This operator allows you to search for files of a specific type. For example, "filetype:pdf" would search for all PDF files.
Following searches for pdf file in the domain yahoo.com
![ex2 file](https://github.com/kiruthika512/Enumeration/assets/135616605/06ece20d-def9-484e-8fb6-cd4f0f05f3b4)



intext: This operator allows you to search for pages that contain specific text within the body of the page. For example, "intext:password" would search for pages that contain the word "password" within the body of the page.
![ex2 password](https://github.com/kiruthika512/Enumeration/assets/135616605/1be3edbe-76eb-42ad-99a7-7cf8bf2a903a)



inurl: This operator allows you to search for pages that contain specific text within the URL. For example, "inurl:admin" would search for pages that contain the word "admin" within the URL.
![ex2 admin](https://github.com/kiruthika512/Enumeration/assets/135616605/ae92b971-83da-4074-99ad-27c3c6875785)



intitle: This operator allows you to search for pages that contain specific text within the title tag. For example, "intitle:index of" would search for pages that contain "index of" within the title tag.
![ex2 index](https://github.com/kiruthika512/Enumeration/assets/135616605/be7dab20-bb56-4ecc-825a-462495681d7f)


link: This operator allows you to search for pages that link to a specific URL. For example, "link:example.com" would search for pages that link to the example.com domain.
![ex2 example](https://github.com/kiruthika512/Enumeration/assets/135616605/5d20462a-b6c7-4ffd-be1e-46068b35ae89)



cache: This operator allows you to view the cached version of a page. For example, "cache:example.com" would show the cached version of the example.com website.
![ex2 cache](https://github.com/kiruthika512/Enumeration/assets/135616605/01fcd628-208e-4c76-9456-6babe424dfef)


 
#DNS Enumeration


##DNS Recon
provides the ability to perform:
Check all NS records for zone transfers
Enumerate general DNS records for a given domain (MX, SOA, NS, A, AAAA, SPF , TXT)
Perform common SRV Record Enumeration
Top level domain expansion
## OUTPUT:






![output 1](https://github.com/kiruthika512/Enumeration/assets/135616605/5864141d-d2a4-4ba7-bc30-84d355c6ccbe)

##dnsenum
Dnsenum is a multithreaded perl script to enumerate DNS information of a domain and to discover non-contiguous ip blocks. The main purpose of Dnsenum is to gather as much information as possible about a domain. The program currently performs the following operations:

Get the host’s addresses (A record).
Get the namservers (threaded).
Get the MX record (threaded).
Perform axfr queries on nameservers and get BIND versions(threaded).
Get extra names and subdomains via google scraping (google query = “allinurl: -www site:domain”).
Brute force subdomains from file, can also perform recursion on subdomain that have NS records (all threaded).
Calculate C class domain network ranges and perform whois queries on them (threaded).
Perform reverse lookups on netranges (C class or/and whois netranges) (threaded).
Write to domain_ips.txt file ip-blocks.
This program is useful for pentesters, ethical hackers and forensics experts. It also can be used for security tests.


##smtp-user-enum
Username guessing tool primarily for use against the default Solaris SMTP service. Can use either EXPN, VRFY or RCPT TO.


In metasploit list all the usernames using head /etc/passwd or cat /etc/passwd:

select any username in the first column of the above file and check the same
![output 2](https://github.com/kiruthika512/Enumeration/assets/135616605/f4d58b60-81b9-4cc9-adb1-b34b74ab78db)
![output 3](https://github.com/kiruthika512/Enumeration/assets/135616605/494c3d3b-0fc8-45ad-be45-62d73a503ee6)




#Telnet for smtp enumeration
Telnet allows to connect to remote host based on the port no. For smtp port no is 25
telnet <host address> 25 to connect
and issue appropriate commands
  
 ##Output
 ![tel](https://github.com/kiruthika512/Enumeration/assets/135616605/d8c4f655-963e-430f-8a64-67b7b85dfbba)

  
  

## nmap –script smtp-enum-users.nse <hostname>

The smtp-enum-users.nse script attempts to enumerate the users on a SMTP server by issuing the VRFY, EXPN or RCPT TO commands. The goal of this script is to discover all the user accounts in the remote system.


## OUTPUT:
![output 4](https://github.com/kiruthika512/Enumeration/assets/135616605/f186e4f5-520a-4271-bb0a-6078e4a7adf9)



## RESULT:
The Google hacking keywords and enumeration tools were identified and executed successfully

