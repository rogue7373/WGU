Task 1 
## A. Success of the Attack
1. Vulnerability 1 -
    - Specific Example: Incorrectly configured email security 
    - Exploited / Attack Success: John from Azumer was phished by watersupp1y.int, The phish was successful due to lack of email security including SPF, DMARC, and DKIM. The Azumer email domain could be easily spoofed. In this situation however, spoofing the email domain was not necessary, due to a lack of warnings, flags, and security scanning by a correctly configured email security client or spam filters the attackers were able to redirect John to a credential harvesting site, giving them domain credentials. 
2. Vulnerability 2 
    - Specific Example: Database security controls 
    - Exploited / Attack Success: On Monday's return to the office John proceeded to his desk and was unable to locate the volunteer database. The case study does not specify whether the database was digitally missing or physically missing. In this disussion we will speak to digitially missing. The exploit here is quite likely the pivot from email compromise to data theft. The same credentials from the phishing attack were likely used to attempt logging into the database at Johns desk. Upon successful login attempt the database was likely exfiltrated by the hacktavists. 
    
## B. CIA and PII 
Explain how the confidentiality integrity, and availability of Azumers operations and PII data have been compromised, using NIST, ISO 27002, or another industry standard framework to support your claims 
-   Explain how each was compromised
    - When the Azumer database was compromised by the hacktivist, operational and PII data held Azumer was breached, this immediately negated the confidentiality of the both Operational and PII data. ISO IEC 27002, section 10.5 "Back-up", provides governance for Data Back-up. These measures are designed to address integrity and availability of information processing facilities. Upon breach of the Azumer database PII such as basic contact information, last 4 digits of social security numbers, and basic contact information, was immediately compromised. Further reaching the hacktivist deleted the Azumer database, thus preventing any restoration from back-up. This significantly impacts the availability. Lastly we compound the issue with there not being a physical copy of the database, while some Azumer employees may have copys taken at various stages, they do not guarantee a full replacement of the database, removing the integrity from Azumer. 

## C. Federal Regulation
Task Requirement: Identify a federal regulation this NGO violated, providing a specific example from the case study as evidence of Azumer Water's noncompliance 
## D. Immediate Steps 
1. Recommendation 1 
    - Immediate step to take using specific example from the case study
2. Recommendation 2
    - Immediate step to take using specific example from the case study
## E. Incident Response Plan
Task Requirement: Explain how having an incident response plan in place will benefit Azumer Water, using details from the case study to support your explanation. 
- Tie in two or more elements of an incident response plan: 
    1. Mission
    2. Strategies and goals
    3. Senior Management approvals
    4. Organizational approach to incident response
        - Incident handling approach/incident reponse lifecycle
    5. How the incident response team will communicate with the rest of the organization and with other organizations 
    6. Metrics for measuring the incident response capability and its effectiveness
    7. Roadmap for maturing the incident response capability
    8. How the program fits into the overall organization
1. Benefit 1:
-    Specific applicable aspect of an incident response plan and how it would address a specific instance from the case study
2. Benefit 2: 
-    Specific applicable aspect of an incident response plan and how it would address a specific instance from the case study
## F. Processes 
Task Requirements: Discuss two processes to increase information asssurance levels within the organization and bring Azumer Water into compliance with the violated federal regulation identified in part C
## G. Technical Solutions
Task Requirements: Recommend technical solutions to counter the remaining effects of the attack in the case study and to prevent future attacks
- Understand what contitutes "technical" vs "administrative"
- Address remaining effects (i.e two other effects you have not previously addressed in other sections of the task)
1. Technical Solutions #1: List a specific technical solution here: 
    - Discuss how the specific technical solution addresses a specific instance from the case study
2. Technical Solutions #2: List a specific technical solution here: 
    - Discuss how the specific technical solution addresses a specific instance from the case study
## H. Organization Structure
Task Requirements: Recommend an organizational structure for IT and security management, including a logical delineation of roles and adequate coverage of responsibilities, to support the efficient discovery and mitigation of future incidents.
- Key Function:
- Coverage: 
## I. Risk Management
Task Requirements: Describe your risk management approach for Azumer Water based on the likelihood, severity, and impact of the risks in the case study.
- Risk selection
- Risk categorization
- Risk management approach formulation
1. Risk #1: List the specific risk here. Discuss why the risk exists in the org.
- Likelihood: Provide your likelihood of occurrence categorization here
- Severity: Provide your severity categorization here
- Impact: Provide your severity categorization here
2. Risk #2: List the specific risk here. Discuss why the risk exists in the org.
- Likelihood: Provide your likelihood of occurrence categorization here
- Severity: Provide your severity categorization here
- Impact: Provide your severity categorization here
Provide your risk management approach here.  Be sure to discuss how categorization in terms of likelihood, severity and impact are considered. Discuss how the approach would help the company address future risks.
