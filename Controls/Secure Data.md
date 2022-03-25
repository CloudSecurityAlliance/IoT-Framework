Control Domain	Control Sub-Domain	Control ID	"CCM v4
Domain
"	Control	Confidentiality	Integrity	Availability	Additional Direction	References	"Control 
Type"	"Man
Auto
Semi"	Freq	Device	Network	Gateway	Cloud Service
Secure Data	Data Classification & Taxonomy	DAT-01	DSP	Document data collected, processed and stored within IoT systems. Classify that data based on data type, value (criticality to the organization), and sensitivity. Label the data with tags (metadata) that can be used to identify types of data flowing within the system.	Low	Low	Low	Effective control requires an understanding of the data's value and the impact to the organization if security of that data is compromised. The level of control should correspond with that value.	"Coalfire: Information Governance: Get Data Classification Right First
https://www.coalfire.com/news-and-events/newsletter/march-2013/information-governance-get-data-classification-rig

PWC: A new equation to managing cyber, risk and regulation
https://www.pwc.com/us/en/services/consulting/cybersecurity/library/broader-perspectives/data-use-governance.html"	P	M	C	TRUE		TRUE	TRUE
Secure Data	Data Classification & Taxonomy	DAT-02	DSP	Implement data security controls based on the classification of each data type.	Medium	Medium	Medium	The level of control should be based on the value of the data at risk. Strong controls over data with little value is a waste of resources. Weak or absent controls over valuable data exposes the organization to unacceptable risk.	"Coalfire: Information Governance: Get Data Classification Right First
https://www.coalfire.com/news-and-events/newsletter/march-2013/information-governance-get-data-classification-rig 

PWC: A new equation to managing cyber, risk and regulation
https://www.pwc.com/us/en/services/consulting/cybersecurity/library/broader-perspectives/data-use-governance.html"	P	M	C	TRUE	TRUE	TRUE	TRUE
Secure Data	Data Classification & Taxonomy	DAT-03	DSP	"Catalogue data sources (both internal and 3rd party) and enforce authentication on all data relied upon by the IoT system. Track the lineage of data throughout the system as data is cleaned, reduced, modified, and aggregated, and demonstrate the ability to pinpoint the source of data and any users or processes that have acted upon any data used within an automated IoT decision process. 

"	Medium	High	Medium	"Automated activities occur within IoT systems. These activities can take place based on relationships between devices and data. Investigation of actions that occurs within an IoT system is aided by understanding the causal relationships between events occurring across multiple IoT devices.

"	"NISTIR 8259 Foundational Cybersecurity Activities for IoT Device Manufacturers: https://nvlpubs.nist.gov/nistpubs/ir/2020/NIST.IR.8259.pdf

NISTIR 8228 Considerations for Managing Internet of Things (IoT) Cybersecurity and Privacy Risks : https://nvlpubs.nist.gov/nistpubs/ir/2019/NIST.IR.8228.pdf
"	P	A	C	TRUE	TRUE	TRUE	TRUE
Secure Data	Encrypted Data at Rest	DAT-04	"DSP
EKM"	After cataloguing data within an IoT system, identify any locations and systems which store that data and apply Data-at-Rest encryption controls to those locations and systems. Monitor to ensure that new systems and components are not implemented without evaluating their storage of sensitive information.	Medium	Medium	Medium	NIST has two approved block ciphers: AES and TDEA (or TDES). Either of these would be recommended. However, because computational resources are limited on IoT devices, Lightweight Cryptography is being researched as an option.	"""NIST is researching and evaluating """"Lightweight Cryptography.""
https://nvlpubs.nist.gov/nistpubs/ir/2017/NIST.IR.8114.pdf"""	P	A	C	TRUE	TRUE	TRUE	TRUE
![image](https://user-images.githubusercontent.com/10893218/160197460-66ccd86f-b5d0-4c50-9f00-3c4a9402c951.png)
