# Emerging Technologies In Cyber Security C844

# Notes 
## Competency 4042.5.1 Cellular and Mobile Technologies
### Lession 1 Focus on Cellular Network Design, Frequency, Security Issues, and Business uses for Mobile and Smart Devices 
- PTSN Public Switched Telephone Network 
   - Wired communication channels brought phones into our homes, ran on it's own power network, worked during standard power outages. 
- Mobile phones use all the principles of two-way radio communications that have been around since the early 20th century. 
   - Making mobile phones subject to issues with range, power, signal-to-noise ratio, and interference. 
- Cellular design 
    Hexagonal (Six-sided) cells, leaving no gaps in coverage
- BTS Base Transceiver Station
    Communicates directly with the phone within its coverage aread
- BCS Base Controller Station 
   - Connects to the core network
   - Multiple Towers will connect to a BCS 
   - The core network connects all the BCS's together and to the PTSN and Internet
- Macrocells
   - Largest of cells used for rural areas 
- Microcells 
   -   used for smaller coverage areas, urban areas
- Picocells 
   - small hotspots that offer wi-fi connectivity via a mobile carrier, dense urban areas
- Limitation of frequency channels
    - First cellular system rolled out in the US had 830 usable channels 
    - 280 channels per cell 
- FDMA Frequency Division Multiple Access
    - FOundation of cellular coveage maps. each channel split further so multiple users can chare without interference 
- TDMA Time Division Multiple Access
    - Allows multiple users on the same frequency with it's own sliver of time. Works well in a voice converstaiton between two people, because "mostly silent"
- CDMA Code Division Multiple Access 
    - Possible for several users to share multiple frequency bands at the same time. Spreads out the signal over the frequencies uses code to distinguish the connections 
    - 3G technology 
- Cellular handoff 
    - passes the signal back and forth between two cells at thier lowest strength 
- AMPS 1G 
    - Advance Mobile Phone system
    - deployed in 1993 for North America
    - Used analog signals to connect to cell towers
- GSM 
    - Global System for Mobile 
    - Responsible for SIM (Subscriber Idntity Module) card 
- CDMA 2G
    - Repsonsible for SMS (Short Message Service)
- GPRS / EDGE x
    - General Packet Radio Service 
    - Packet-switching technology
    - Brought websites to mobile devices
- 3G / HSDPA (High Speed Downlink Packet Access)
- 4G / LTE (Long Term Evolution)
- 5G 
    - Designed to meet the needs of the explosion of data traffic per user
### The BlackBerry Effect and the BYOD Revolution 
- RIM (Reseach in Motion)
- BES (Blackberry Enterprise Server) 
    - Brought about Push Email with MicroSoft Exchange allowing mobile users to send/receive email on the go as long as they had cellular coverage

### Lession 2 Identifies smartphone and tablet operating system security issues and architecture 
- Focus on potential vulnerabilities of different mobile operating systems and the tools and techniques in use to target exploits. 
- Malware exploits for Android OS are exceedingly rare due to the islotion of application runtimes in their own virtual sandbox.
    - Even if malware was downloaded the application would run in comoplete isolation from other apps or system resources
- Today most security issues are user based 
- It is believed that most important vulnerabilities are in:
    - Data Leakage
    - Outdated devices 
    - Social Engineering
- Mobile OS's are inherently secure by design; the security issues that arise come from user activity such as rooting Android and jailbreaking iOS. 
- In addition to OS and Application vulnerabilities, the logon and authentication of the end user is at risk to compromise. 
- Mobile users are more susceptible to phishing attacks to due URL trunking 
- While mobile devices are thought to be inherently secure, penetration percentage rates have reached the high 90's and above in some countries. 

## Exploits, Tools, and Techniques
- Categories of Attack Vulnerability 
    - Surveillance vulnerabilities 
        - Audio Attack
            - This involves switching on the microphone to listen in on conversations 
        - Camera Attack
            - This involves hijacking the camera to monito the user or the user's surroundings 
        - Location Snooping
            - This involves the activation of Internet Protocol(IP)/ browser tracking to monitor location. This is a common malware trick to gain advertising revenue
        - Call Logs
            - This invloves recording recent calls and messaages, which can be read and/or stolen 
        - Global Positioning System (GPS) tracking
            - This involves the activation of another location and tracking port to monitor location. This can be very accurate
    - Financial vulnerabilities 
        - Stealing transaction codes 
            - This technique is commonly used for man-in-middle attacks against online banking sites
        - Stealing account numbers
            - This is possible when the phone is used as a data repository or a mobile wallet with an unsecure data store
        - Making expensive calls
            - This involves bypassing security measures to make calls, which are then charged to the user's account  
        - Sending premium-rate SMS messages
            - This involves using a mobile handset ot pay for services and products. This is a common way for cybercriminals to monetize their attacks
        - Extortion via ransomware
            - This is a method of extortion where malware is placed on a phone that prevents the phone from being used until a ransom is received. This is another popular method for turning nefarious cyberskills into cash. 
    - Botnet Activity 
        - Participating in distributed denial of service (DDoS) attacks 
            - This involves hijacking the phone to participate in mass attacks on a third-party network for example, by sending out Domain Name System (DNS) or Network Time Protocol(NTP) requests. 
        - Sending premium-rate SMS messages
            - Again this is a way to make money at the owner's expense 
    - Data Theft 
        - Communications 
            - Emails and SMS messages are all open to theft
        - International Mobile Station Equipment Identity (IMEI) number theft 
            - The IMEI number uniquely identifies the mobile phone and can be used for a number of purposes, such as blocking the phone on an operator's network
        - Banking Data
            - Unecrypted or poorly protected banking data can be captured and used to fraudulently acces a user's online account 
        - Credit card data
            - Credit Card details can be extracted from the phone, especially if it has no encryption or is using unsecure NFC
        - Contacts and phone book
            - This is another popluar target for cybercriminals, which furthers their reach for potential victimes
        - Photographs and video
            - The attacker can invade the user's privacy by stealing their pictures and videos 
        - Call logs 
            - Tracking call activity is another way a cyberattacker can invade a user's privacy
    - Impersonation
        - Sending SMS messages 
            - This involves sending false messages to collect information from contacts or to engage in illegal or illicit activits (including harrassment of the user)
        - Posting to social media
            - This is typically done to harass or embarrass the user 
        - SMS redirection
            - This is used for eavesdropping and potential extortion
    - Potentially Unwanted Applications (PAUs)
        - Developers create a PAU in an attempt to montize their applications throug connections to aggressive third-party advertising networks. 
## Google Android Security Challenges
- If you believe the research conducted by antivirus companies, security threats on Android devices were growing at an exponential rate. 
- Smartphones were more susceptible to this type of eavesdropping due to a lack of enforced Secure Sockets Layer (SSL)/Transport Security Layer (TLS) controls combined with a high-level of personal usage data. 

### Lession 3 Explore specific tops related to sandboxing, application provenance, emerging trends  
### Lession 4 Mobile Malware delivery techniques, major categories of mobile applications exploits, security implications for excessive application permissions requests, and the role the MDM plays in protecting compainies
## Competency 4042.5.2 Wireless Technologies
## Competency 4042.5.3 Mapping and Monitoring 

# Paper Task 1 
## Describe Network Technology
## Summarize vulnerabilities on the network
## Describe the anomalies found with Wireshark
## Summarize the potential implications for each anomaly
## Recommend Solutions 
## Citations 
