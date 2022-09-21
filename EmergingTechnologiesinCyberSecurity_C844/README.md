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
- Smartphones were more susceptible to this type of eavesdropping due to a lack of enforced Secure Sockets Layer (SSL)/Transport Layer Security (TLS) controls combined with a high-level of personal usage data. 
## Android Exploitation Tools 
Android is an open source form of a widely used version of Linux. Because of this, there are many tools available that developers and programmers can use to decompile, analyze, and study Android OS code and applications. The people who use these tools may be good guys who seek to identify malicious or otherwise problematic code. Or, these same tools may be used by criminals to exploit known vulnerabilities and create their own malware. 
- AndroRAT 
    - This tool can be bound to other applications, can read messages and contacts, steal data, view video, reecord calls, and more. This full framework of open source tools is freely available and is constantly updated.
- Android SDK 
    - The Android Software Development Kit (SDK) is the official Android development tool. It enables developers to compile and decompile applications for Android. This is an essential development or research toolkit.
- DroidBox 
    - Another application for analyzing Android applications, DroidBox can check for password hashes, check files for read/write data, and record incoming and outgoing communications (SMS messages and phone calls), among other things. 
- Android Framework for Exploitation 
    - This tool can scan the network, looking for security issues and vulnerabilities on Android Devices.
- RiskInDroid
    - This is handy tool for calculating the inherent risk of Android apps based on their required/requested permissions. 
## Android Security Architecture 
- Security at the OS Linux kernel 
    - This ensures that native code is constrained by the application sandbox
- Mandatory sandboxing of applications 
    - This prevents applications from interacting with each other and liits access to the operating system
- Secure interprocess communication
    - This provides standard and secure mechanisms for accessing file systems and other resources
- Digital signing of applications 
    - This identifies application authors and deters or prevents malware
- User-granted application permissions 
    - These require applications to obtain express permission from users before accessing resources such as camera funtions, contact lists, or GPS
## Android Application Architecture 
- Acitivity 
    - This is a user interface whereby a user canenter data or interact with the application in some other way
- Service 
    - A service performs operations in the backgroudn -- for example, playing music
- Content providers 
    - These provide information to third-party applications. A content provider can be seen as a n inerface the processes data in one process and feeds it to another independent process 
- Broadcast receivers 
    - These respond to systemwide notifications such as "battery low" or "microphone unplugged". Thos OS normally initiates these notifications or broadcasts, but trusted applications can slo issue broadcasts
## Apple iOS Security Challenges 
- System Architecture 
    - This involves the OS platform and hardware used to protect the iOS device. It also relates to sandbox testing and application isolation. It includes a secure boot-chain, system software authorization, a secure enclave, and tough ID
- Encryption and data protection
    - These are the techniques used to safeguard against theft. They include file data protection, passcodes, keychain data protection, and more 
- Network Security 
    - These are the techniques used to protect data when it is transmitted across the open internet. They include SSL and TLS 
- Applicaiton Security 
    - This includes digital authentication and verification, runtime process security, data protection within applications, sandboxes, and service isolation
- Internet Services 
    - These include iMessage, FaceTime, Siri, and iCloud
- Device Access 
    - These are the basic security tools suchs as passwords, PINs, remote wipe, mobile device management (MDM), and even remote access tools
## Apple iOS Architecture 
- Cocoa Touch Layer
    - This higher level layer provides a level of abstraction from lower levels. it is where application development occurs. This make it much easier to write code, as it reduces the amount and complexity of the code.
- Media Layer
    - This layer contains the graphics, audio, and video technologeis used to implement multimedia features in applications. 
- Core Service Layer
    - This layer underpins the system services that applications require. It also supports technolgies such as iCloud, social media, and networking
- Core OS Layer
    - This layer contains the low-level features that are the foundations of all the higher layers and thier features 


### Lession 3 Explore specific tops related to sandboxing, application provenance, emerging trends
## The Android Security Model
- Android is build on Linux
- Android applications use process sandboxing for security
- Dalvik virtual machine 
- Does not rely on Java VM to enforce security, instead looks to the kernel
- Linux Kernal makes the foundation of Android, including user permissions, multiuser environments 
## Apple iOS Security
- Walled Garden approach 
- Restricted access limited to own app store 
- Allows for trusted authenticity 
- Developers must register with Apple 
### Lession 4 Mobile Malware delivery techniques, major categories of mobile applications exploits, security implications for excessive application permissions requests, and the role the MDM plays in protecting compainies
### Malware on Android Devices 
- Focused efforts on the market leader: Android
- Apple barely registers on the scale 
- Focus on Android is due to the huge market share, open source, not a walled garden
- Software fragmentation 
### Criminal and Developer Collaboration
- Remote Acccess Tools (RATs) 
    - These offer a means of backdoor access to infected victim devices and are often used for intelligence collection
- Bank Trojans
    - This type of malware aims to steal the user's logon credentials for predetermined mobile apps. 
- Ransomware 
    - This is used to lock out a user from their device often by encrypting the data, making it useless. The attackers will tehn demand a "ransom" payment. Access will only be granted to the device once a ransom is paid. 
- Cryptomining malware
    - This is specifically designed to allow attackers to covertly mine cryptocurrency on the victime's mobile device, allowing them to generate cryptocurrency. 
- Advertising Click Fraud
    - This is a hugely popular type of malware that is desinged to let an attacker gain access to a device in order to generate income through click fraud. 
- Stalkerware 
    - There are two types; trackers nad fully fledged stalkers. The former generally focus on stealing the victims' GPS coordinates and perhaps intercepting text messages. 
### Madware 
Madware is a form of very agressive adware that is prevalent on mobile devices. Due ot the way the "free application" business model works on the internet, developers consider madware to be no only harmless but a legitimate aspect of application behavior. Although some free applications that use advertisements as a revenue source are legitimate and benign, others run background processes that access GPS information, scan address books, and send out stolen dat via HTTP to third-party API'. Some also track and share location details, browsing histories, and contact lists, often with the phones owner's unknowing permission. 
### Excessive Application Permissions 
- Retrieve list of running apps 
    - For a flashlight application, this is a dubious requirement
- Modify or delete contents of your USB Storage
    - Why would a flashlight application want to delte files on a USB device? Other applications, such as a camera interface or music system software, may have a legitimate reason to delete uploaded or downloaded files, but flashlight... no way! 
- Test access to protected storage 
    - This is dubious. Why would a flashlight application need to read or write to protected memory outside its container? 
- Take pictures and videos
    - This is a rather frightening ability for a flashlight if it's done without user notification. 
- View Wi-Fi Connections 
    - This is anotehr unnecessary permission for a flashlight 
- Read phone status and identity
    - A request to read the phone status is a yellow flag, but this one does have a genuine use. Develpers need to retrieve this information for analytics, to identify the phone model, and to identify the OS on the phone 
- Control Flashlight 
    - This permission seems legit
- Change System display settings
    - Thsi seems acceptable, because the flashlight application needs to change screen display parameters
- Prevent device from sleeping
    - This may be a necessary function for a flashlight to prevent it from shutting off while in use. 
- View network connections
    - This is yet another unnecessary request for permission
- Gain full network access
    - ya fucking right!! 
- Approvimate location (network based)
    - This is an obvious requirement for adware 
- Precise location(GPS)
    - This is totally unnecessary 
### Malware on Apple iOS Devices 

## Competency 4042.5.2 Wireless Technologies
## Competency 4042.5.3 Mapping and Monitoring 

# Paper Task 1 
## Describe Network Technology
## Summarize vulnerabilities on the network
## Describe the anomalies found with Wireshark
## Summarize the potential implications for each anomaly
## Recommend Solutions 
## Citations 

# Paper Task 2
## Describe two WLAN vulnerabilities that present risks for Alliah, based on the details in the scenario

1. Evil Twin - "An evil twin attack is a spoofing cyberattack that tricks users into connecting to a fake Wi-Fi acess point that mimics a legitimate network". (Panda Security, Many Evil Twin attacks involve a captive portal, designed to mimic the captive portal login page of the original WLAN. This allows malicious attackers to harvest credentials. When an Evil Twin attack is used on a corporate WLAN the attacker is able to harvest domain credentials, they are also able to monitor traffic that is being passed through the Evil Twin. 

2. Denial Of Service - 

## Describe two mobile vulnerabilities that present risks for Alliah, based on the details in the scenario

1. Malicious Applications (Malware) 
2. Browser Exploits  

## Summarize the steps for mitigating each identified WLAN and mobile vulnerability, including the specific tools or documentaiton that will be needed for mitigation. 

To Summarize.... 

1. Evil Twin mitigation
2. Denial of Service mitigation 
3. Malicious Applications (Malware) 
4. Browser Exploits 


## Recommend preventive measures to maintain the security posture of WLAN and mobile environments in a small business, such as Alliah. Reference federal, state, or industry regulations that justify these measures.


## Recommend a solution for the company's BYOD approach, including research to justify your recommendation.


## Resources 

Citations 
1. Panda Security - Evil Twin - https://www.pandasecurity.com/en/mediacenter/security/what-is-an-evil-twin-attack/
