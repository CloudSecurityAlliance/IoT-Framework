<h1> Using the IoT Security Controls Framework </h1>

Figure 1 below details the flow that users of the CSA IoT Security Controls Framework should follow as they assess and then implement security controls for a unique environment. The letters in this illustration correspond to columns in the Framework (spreadsheet).

![FIPS199](https://user-images.githubusercontent.com/10893218/160192606-d7dca1a1-5083-432c-8377-f521c34c8984.png)

Figure 1 - Control Assessment 

Evaluation begins by understanding the system architectures’ security and data impact levels. These are characterized based on standard processes, such as Federal Information Processing Standard (FIPS) 199 “Standards for Security Categorization of Federal Information and Information Systems” Once impact-level determinations are made for system confidentiality, integrity, and availability, the Framework can be filtered to show only the controls applicable to those impact levels.

Review each of the resulting controls in Column F and review any additional guidance in Column J. Columns O, P, Q, and R include a tool for allocating controls to different architectural components. 

These columns allow users to filter controls based on whether they apply to the device, the network that hosts the device, a gateway, or cloud services. 
Users can also understand how to implement each control using columns L, M, and N. These columns offer control-type recommendations, whether controls should be manual, automated, or a combination of both, and how often controls should be exercised. 

The Framework provides insight into an idealized version of a secure baseline tailored to an IoT system architecture following this initial process. Some components within an IoT architecture may not meet a subset of the controls. In these cases, the security architect must understand the residual risk and identify compensating controls to mitigate that risk. 

<h1> Security Control Objectives (Columns A, B, C, D, E, F) </h1>

![control_objectives](https://user-images.githubusercontent.com/10893218/160192760-19d870dc-5c6d-42c7-993f-76f6686c31a2.png)

**Control Domain (Column A):** Organized by logical groupings of the individual security control measures (see table below) and detailed in column F (Control), the name of each corresponding control specification is italicized below the category of “Control Domain.”
 
**Control Domain (Column B):** Domains are categorized for filtering purposes.

**Control Sub-Domain (Column C):** Sub-domains provide granularity for filtering purposes.

**Control ID (Column D):** The control identification (ID) is the official identifier of a specific security control. The ID (e.g., “RSM-01”) allows controls to be referenced elsewhere by their position in the framework.
 	 	 	 	 
**CCM Domain (Column E):** Security controls in the framework are associated, or mapped, in this column to the domains of the CSA Cloud Controls Matrix (CCM). When the IoT security control is derived or linked to a CCM control, one or more entries are identified. The associated controls involve partial to complete coverage of the control specifications in each framework. 
 	 	 	 	 
**Control Specification (Column F):** Specifications are written as mitigations or countermeasures addressing specific risk areas for an IoT system. For usability, each control is separated into a simplified action to address unique IoT environments. 

<h1> IoT System Risk Impact Levels (Columns G, H, I) </h1>

**Columns G through I:** This information enables the initial tailoring of security controls to a user’s unique environment. Before beginning the process of tailoring individual security controls, users should review two U.S. Department of Commerce publications: “Standards for Security Categorization of Federal Information and Information Systems” (FIPS 199) and “Minimum Security Requirements for Federal Information and Information Systems” (FIPS 200)2.  Those publications categorize risk impact levels as “low,” “moderate,” or “high” in three areas: confidentiality, integrity, and availability.

![system_impact_levels](https://user-images.githubusercontent.com/10893218/160193136-dce2bbad-4489-447b-8980-1448e7746c9b.png)

**Confidentiality (Column G):** Some data in an IoT system, such as personal privacy and proprietary information, necessitates restricted access using various security controls to remain appropriately confidential. To evaluate components of an IoT system’s confidentiality risk, it is necessary to estimate the potential impact (low, moderate, or high) if system data were made public or compromised by an attacker.

**Integrity (Column H):** To protect data integrity, an enterprise must guard against improper data modification or destruction and ensure information authenticity. To evaluate integrity risks of an IoT system, assess the impact (low, moderate, or high) if system data were destroyed or inappropriately modified. 	 	 

**Availability (Column I):** To assess the degree to which system information must remain accessible in a timely and reliable manner, evaluate the potential system risks if it became inoperable for any duration.
 	 	 	 	 
To assess whether specific risks regarding confidentiality, integrity, and availability of system data is low, moderate, or high, consult the information in the FIPS 199 publication called “POTENTIAL IMPACT DEFINITIONS FOR SECURITY OBJECTIVES.”
 	 	 	 	 
After determining these risk impact levels, the IoT Security Controls Framework can identify all needed security controls for a specific environment.
Note that when an impact level is high, all available security controls should be applied—including those for low, moderate, and high-risk levels. When an impact level is moderate, apply all controls for moderate and low-risk levels.  
Below are examples of three impact ratings and the necessary corresponding controls.

![CIA_Examples](https://user-images.githubusercontent.com/10893218/160193275-0971d971-762a-4684-b252-e50a8b25f4c4.png)

<h1> Supplemental Control Guidance (Columns J, K) </h1>

**Additional Direction (Column J):** When assessing or implementing any of the individual security protocols in the IoT Security Controls Framework, be sure to view this supplementary information detailing special requirements, explanations of terms, helpful operating tips, and more.
 	 	 	 	 
**References (Column K):** Consult this section for professional source information, such as government publications, regulatory information, and other references necessary to understand and implement a control specification fully.

<h1> Implementation Guidance (Columns L, M, N) </h1>

When implementing an enterprise security plan, use the “Implementation Guidance” section to determine control types for unique environments (Column J). This insight will include how organizations can implement the controls (Column K) and the frequency with which each security control measure should be enacted (Column L). 	

![implementation_guidance](https://user-images.githubusercontent.com/10893218/160193418-a338b982-ab5e-4e6c-ae9d-8c1108c28a2e.png)

<h1> Types of Security Controls (Column L)</h1>

The IoT Framework security controls are classified into three types, based on when, where, and how the measures work to increase security.
 	 	 	 	 
**Preventive controls:** Stop something from happening (i.e., limiting physical access to a room through a locked door or require higher-level biometric identification protocols). 
 	 	 	 	 
**Detective controls:** Identify and then characterize incidents. Examples include researching an inventory discrepancy after a physical count, recording video, and using motion sensors to detect trespassing.
 	 	 	 	 
**Corrective controls:** Mitigate damage caused by security incidents. For example, use a fire extinguisher to limit fire damage or ensure the availability of a duplicate data center if a primary data center crashes.

<h1>Control Implementation Guidance (Column M)</h1>

Security controls are implemented in three ways, depending on the level of automation.
 	 	 	 	 
**Manual controls:** A human performs manual controls. For example, in a risk management process review, someone evaluates the process to confirm it has been executed in accordance with policy.
 	 	 	 	 
**Automatic controls:** A system performs automatic controls without human intervention. For example, in a user access check, a user logs in with a username and password. The system then verifies the combination before granting access.
 	 	 	 	 
**Semi-automatic controls:** Semi-automatic controls combine automated and manual efforts. For example, in a physical inventory, items are counted, and the results are compared to a system-generated list. Differences are then reconciled through an investigation, which may involve paper and electronic records.

<h1> Control Frequency (Column N) </h1>
 	 	 	 	 
Some organizations require more frequent controls based on internal risk priorities or regulatory compliance requirements. The following frequencies are recommended for different situations (depending on individual enterprise needs).

* Annually 	 	 
* Quarterly
* Monthly
* Weekly
* Daily
* Event: Control performed irregularly (e.g., a software update)
* Continuously: Control performed many times per day (e.g., user access)

<h1> Device, Network, Gateway, and Cloud Services (O, P, Q, R) </h1>
The IoT Framework guides the application of architectural element controls in an IoT system. These architectural elements represent standard layers within an IoT architecture, as shown in the below figure.

![architectural_allocations](https://user-images.githubusercontent.com/10893218/160193666-6165f527-db3d-4b5b-98b6-0a3bde45f00e.png)

Implementers should consult these document sections to determine if controls are applicable at each layer. Each column describes opportunities to create trust boundaries within IoT architecture. Discrete controls should be applied at each layer.

<h3> Device (Column O)</h3>
Controls applied directly at the device layer that focuses on the data processed, stored, and/or generated by the device. A generic IoT device will incorporate sensors, actuators, and potentially a minimal user interface. The device may also be capable of collecting and storing events or security logs, using configuration files that must be integrity-protected. 

<h3> Network (Column P) </h3>
At the network layer, components such as wireless access points (WAPs) support device Wi-Fi connectivity. Other network components may include key management servers that support protocols such as ZigBee. Additionally, network security controls may consist of zero trust designs, virtual local area network (VLAN) segmentation, firewalling, and intrusion detection. Consider data encryption and integrity protection as data traverses an IoT network.
 
<h3> Gateway (Column Q) </h3>
The gateway represents a high potential IoT network entry point for threat actors. The gateway may have additional security controls applied that exceed what devices typically implement. 
 
 <h3> Cloud Services (Column R)</h3>
Most IoT devices require cloud environments to operate. Devices may send data directly to the cloud or be managed through a cloud service. Data transmitted to the cloud must be protected during transit and persistently within cloud provider storage volumes. In some cases, anonymity protections must be applied within the cloud to ensure identities cannot be linked to IoT data. 

![data_flow](https://user-images.githubusercontent.com/10893218/160193877-4fc9b36c-77ad-4cdb-964f-e292d85f5ecc.png)
