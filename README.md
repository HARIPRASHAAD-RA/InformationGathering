# Ex-02 InformationGathering
Information Gathering Techiques

## HARIPRASHAAD RA 
## 212223040060
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

## Architecture Diagram
```
                      +-------------------------+
                      |     Attacker System     |
                      |     (Kali Linux)        |
                      +-----------+-------------+
                                  |
                                  | Terminal / Browser
                                  | Executes Recon Tools
                                  v
      +------------------- Passive Recon --------------------+
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   WHOIS Query  | --> |    Domain Registrars    |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   DNS Enum     | --> |     Public DNS Servers  |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      +-----------------------------------------------------+

                                  |
                                  v

      +------------------ Active Recon ----------------------+
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   Nmap Scan    | --> |  Target Host/Network    |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  | WhatWeb, Wapp | --> |   Target Web Application |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  | theHarvester   | --> |     Search Engines      |  |
      |  +----------------+     +------------------------+  |
      +-----------------------------------------------------+

                                  |
                                  v
                    +-----------------------------+
                    |     Collected Information   |
                    | - IPs, Subdomains           |
                    | - Open Ports & Services     |
                    | - Technology Stack          |
                    | - Emails, Metadata          |
                    +-----------------------------+
```

## OUTPUT:
### Whois
<img width="1920" height="1080" alt="Screenshot (306)" src="https://github.com/user-attachments/assets/c38ea2a5-02f1-4164-8bb9-649449e958b4" />

### Finding Hosting Company :
<img width="1920" height="1080" alt="Screenshot (307)" src="https://github.com/user-attachments/assets/37a0f0df-c279-472b-9b8b-bf9d3192b278" />

### History of the website :
<img width="1920" height="1080" alt="Screenshot (308)" src="https://github.com/user-attachments/assets/144b9a21-60d1-46d8-a055-eb3d391ff665" />

### ping command :
<img width="1920" height="936" alt="ping" src="https://github.com/user-attachments/assets/bec93a64-863d-476f-92bb-7eb8b0064f44" />


### whois :
<img width="1920" height="936" alt="who is" src="https://github.com/user-attachments/assets/810c6deb-89d2-4b34-9ec6-141348ee4c7e" />

### netcat :
<img width="1920" height="936" alt="netcat" src="https://github.com/user-attachments/assets/563501f4-ebbb-4a19-8f20-732d0744b36a" />


### nmap :
<img width="1920" height="936" alt="nmap" src="https://github.com/user-attachments/assets/f7b49e6c-185c-4255-9ff7-fd44a6b17f04" />

### whatweb :
<img width="1920" height="936" alt="whatweb" src="https://github.com/user-attachments/assets/a7c01a58-7ec0-47ee-884c-4e1c7250ef4e" />



### TCP traceroute :
<img width="1920" height="936" alt="tcp" src="https://github.com/user-attachments/assets/93a7fe50-8880-452f-bc0e-9fcb4d19ed1c" />


### UDP traceroute :
<img width="1920" height="936" alt="udp" src="https://github.com/user-attachments/assets/bbd04f4c-0801-41f4-8162-7c5a9b8fd3fa" />




## RESULT:
The information gathering techniques tools/procedure were  identified successfully
