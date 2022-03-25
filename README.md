<h1> Introduction </h1>
The Internet of Things (IoT) market continues to expand with newly introduced advances in connectivity and autonomy across industry sectors. A reliance on IoT-generated data and features requires organizations that adopt these new technologies to plan for accessible, secure, and resilient deployments. Given the rapid evolution of connected technologies and the constant flow of new threats, these aspirations are challenging. Creating a safe IoT environment requires security engineering that addresses unique risks and employs appropriate mitigation measures. The Cloud Security Alliance (CSA) IoT Security Controls Framework provides a starting point for organizations that wish to better understand and implement security controls within their IoT architecture. This accompanying guide explains how enterprise organizations can use the Framework to securely evaluate and implement IoT systems. 
 
<h1> Tailoring the Framework </h1>
The IoT Security Controls Framework is relevant for enterprise IoT systems that deploy a diverse set of connected devices and associated cloud services, networking technologies, and application software. The Framework has utility across many IoT domains, ranging from systems processing only “low-value” data with limited impact potential, to sensitive systems that support critical services. System owners classify components based on the value of stored and processed data and the potential impact of various physical security threats.
 	 	 	 	 
The Framework helps users identify appropriate security controls and allocates them to specific architectural components, including:

* Devices
* Networks
* Gateways
* Cloud Services

Controls allocated to each layer in the architecture represent best-case security postures. In some cases, architectural components cannot implement specifically recommended controls in this Framework. In these cases, the system security architect should identify those shortcomings and develop plans to mitigate residual risk using alternative measures. 

The framework can be tailored to specific cybersecurity architecture goals. For example, although no specific controls are included for zero trust, a security engineer can use the Framework to identify controls that would enable a zero-trust architecture (ZTA). Framework controls that call for microsegmentation (SNT-04), limiting privileged service operations (IAM-04), bootstrapping devices onto the network (IAM-07), and authenticating devices through a software-defined perimeter (SNT-02) can be used as a starting point for building a device-based ZTA. 

<h1> Industry Profiles </h1>
Version 3 of this guide now includes industry profiles. These profiles represent starting points for securing industry-specific IoT devices such as medical devices, vehicles, and generic autonomous systems. Version 4 will see the addition of vehicle and generic autonomous systems controls, and ICS/IIoT controls. 

<h1> Goal </h1>
The IoT Security Controls Framework is a tool to guide and evaluate security implementations as they progress through the development lifecycle to ensure they meet industry-specified best practices.

<h1> Audience </h1>
The IoT Security Controls Framework is a resource for system architects, developers, and security engineers to design secure IoT ecosystems. IoT system evaluators such as auditors and penetration testers may leverage the Framework to validate controls and implementations.

<h1> Versioning </h1>

**Version 1** of the IoT Security Controls Framework introduces 160 base-level security controls required to mitigate many risks IoT systems face operating in various threat environments. 

**Version 2** of the IoT Security Controls Framework evolves the Version 1 Framework to categorize controls into a new set of domains, minimize control allocation to components within an IoT architecture, and reduce security controls to 155.

**Version 3** of the IoT Security Controls Framework evolves the Version 2 Framework increasing the number of controls to 198 while adding a new incident management domain and improving technical clarity and referencing. 

**Future Changes - Version 4** may include one or more of the following improvements:
  
* Supply Chain Domain
* Vehicle and generic autonomous systems controls, and ICS/IIoT controls
* IoT Framework Shared Responsibility Matrix
* Safety specific controls 
* Indicators of compromise 
* IoT Framework mapping to the European Union Agency for Network and Information Security (ENISA)    
            Guidelines for Securing the Internet of Things
* IoT Framework mapping to the  National Institute of Standards and Technology (NIST) Cyber Security      
            Framework (CSF) and 800-53 Mappings
* NIST Informative Reference Classification Application
