# We define "good faith" as "having honest or sincere intentions".

# A good faith vulnerability researcher is someone who:

1. Examines application and system vulnerabilities, conducts research on emerging threats and vulnerabilities, provides mitigation recommendations, and reports their findings to an organization or to the public
   a. A vulnerability security researcher "stays informed on the current, new and emerging technology, proposed standards, and threat actors that could be used to exploit application and system vulnerabilities," and "often creating proof of concept exploits as well" (source: https://cybersn.com/role/security-researcher/ and https://infosec-jobs.com/insights/security-engineer-vs-security-researcher/) 
    
2. Does not intentionally damage property in the pursuit of vulnerabilities (viewing, copying, or disseminating data is not damage)
    
3. Designs and carries out their pursuit of vulnerabilities in such a manner as to avoid, as best as possible, any intentional harm to individuals or the public
   
4. Follows local laws to the best of their ability and knowledge
    
5. Uses the common best practice of waiting at least:
   
   a. 30 days to publicly disclose a vulnerability that is in a software supply chain* or found in              critical infrastructure* (question -- should this be 45 days to include time that is initially            disclosed to government?)

   b. 60 days to publicly disclose a vulnerability if a company has been non responsive

   c. 180 days to publicly disclose a physical vulnerability (e.g. one found in a physical lock or the          firmware/hardware of an electronic access control system)

7. In the event of non response or contact from a company during the waiting period, the good faith vulnerability researcher:

    a. should disclose immediately to government if it is a critical infrastructure or supply chain               vulnerability, and disclosure should be close in time of notification to the                              organization/company; public disclosure is ____ days after government disclosure (question tied           to earlier point on whether should this be 30 or 45 days?)

     b. could disclose an IT/OT or physcial vulnerability to government before public disclosure, as part         of good faith security research practice
   
7. In the event of a response from a company or government, the good faith vulnerability researcher:

     a. Does not disclose a company-reported vulnerability before the agreed-upon deadline established in         prior communications 
   
9. (When the situation arises) Prioritizes the safety and health of others over financial gain and immediately reports to a relevant government agency, if an ICS/SCADA vulnerability found that is actively harming people physically (does it have to be active? can it be a potential risk and an opportunity to mitigate before public harm occurs or a disaster strikes?)
    
10. Does not withhold the details of a vulnerability in demand for payment from a company.  If a company refuses to pay or does not wish disclosure to them, makes one of two choices:
    
    a. publicly disclosing the vulnerability without intention of profit
    
    b. or disclosing to a relevant government agency for assistance in disclosure without intention of           profit

11. If a good faith vulnerability security researcher is interested in
   
12. Instances where good faith vulnerability research disclosures have advanced public safety and security:

    a. "Will Your Airliner Get Hacked? Meet the people who are making sure it won’t." Source:                    https://www.smithsonianmag.com/air-space-magazine/will-your-airliner-get-hacked-180976752/

    b. (add a few more)

* The purpose of this document is: How does a policymaker recognize a researcher as opposed to a criminal? It’s someone who abides by the international code of conduct. It must work at an international level.
  
* Critical infrastructure definition:
"System and assets, whether physical or virtual, so vital to the U.S. that the incapacity or destruction of such systems and assets would have a debilitating impact on security, national economic security, national public health or safety, or any combination of those matters." Source: https://csrc.nist.gov/glossary/term/critical_infrastructure#:~:text=Definitions%3A,any%20combination%20of%20those%20matters
- impacts to physical and digital infrastructures that society relies on; e.g. water and wastewater / electric / oil and gas / telecommunications / finance / health / government, sectors that rely on Industrial Control Systems (ICS) and SCADA systems, common third party / supply chain software and applications
- Case studies: 
  
* The number of days to wait before disclosure is based on two things; an average of the lengths of time published by organizations such as Google’s Project Zero, US CISA, and vulnerability reporting mechanisms for such companies as Splunk, Symantec, Master Lock, and more - and second, what would be commonly seen as a reasonable waiting time amongst cybersecurity researchers and vulnerability owners (at least according to their documentation).

* TODO: fixes on max length, cadence, options for responsive/nonresponsive - demands def of company not acting in good faith as well which is already in doc
* For lines 11/12, switch. Depending on severity, should release to relevant government agency first before public
* Concerned about Line 10 overall. There should be a push for vendors to compensate good faith researchers regardless of outcome.
* 
