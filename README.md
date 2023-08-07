# Creating-A-Security-Audit
A detailed walkthrough on how to create a security audit for a fake company 
<p align="center">
<h2> Scenario </h2> 
<p align="left">
Botium Toys is a small U.S. business that develops and sells toys. The business has a single physical location. However, its online presence has grown, attracting customers in the U.S. and abroad. Their information technology (IT) department is under increasing pressure to support their online market worldwide.

The manager of the IT department has decided that an internal IT audit needs to be conducted. She expresses concerns about not having a solidified plan of action to ensure business continuity and compliance, as the business grows. She believes an internal audit can help better secure the company’s infrastructure and help them identify and mitigate potential risks, threats, or vulnerabilities to critical assets. The manager is also interested in ensuring that they comply with regulations related to accepting online payments and conducting business in the European Union (E.U.).   

The IT manager starts by implementing the National Institute of Standards and Technology Cybersecurity Framework (NIST CSF), establishing an audit scope and goals, and completing a risk assessment. The goal of the audit is to provide an overview of the risks the company might experience due to the current state of its security posture. The IT manager wants to use the audit findings as evidence to obtain approval to expand his department. 

Your task is to review the IT manager’s scope, goals, and risk assessment. Then, perform an internal audit to complete a controls assessment and compliance checklist.

<h2>Step 1: Reviewing Audit Scope and Goals / Reviewing Risk Assessment </h2>

<b>Botium Toys: Risk assessment</b>

Current assets
Assets managed by the IT Department include:
<br>● On-premises equipment for in-office business needs</br>
<br>● Employee equipment: end-user devices (desktops/laptops, smartphones),
remote workstations, headsets, cables, keyboards, mice, docking stations,
surveillance cameras, etc.</br>
<br>● Management of systems, software, and services: accounting,
telecommunication, database, security, e-commerce, and inventory
management</br>
<br>● Internet access</br>
<br>● Internal network</br>
<br>● Vendor access management</br>
<br>● Data center hosting services</br>
<br>● Data retention and storage</br>
<br>● Badge readers</br>
<br>● Legacy system maintenance: end-of-life systems that require human
monitoring</br>
<b><br>Risk description</br></b>
<br>Currently, there is inadequate management of assets. Additionally, Botium Toys does
not have the proper controls in place and may not be compliant with the U.S. and
international regulations and standards.</br>
<b><br>Control best practices</br></b>
<br>The first of the five functions of the NIST CSF is Identify. Botium Toys will need to
dedicate resources to managing assets. Additionally, they will need to determine the
impact of the loss of existing assets, including systems, on business continuity.</br>

<b><br>Risk score</br></b>
<br>On a scale of 1 to 10, the risk score is 8, which is fairly high. This is due to a lack of
controls and adherence to necessary compliance regulations and standards.
<b><br>Additional comments</br></b>
<br>The potential impact from the loss of an asset is rated as a medium because the IT
department does not know which assets would be lost. The likelihood of a lost asset or
fines from governing bodies is high because Botium Toys does not have all of the
necessary controls in place and is not adhering to the required regulations and standards
related to keeping customer data private.</br>

<b>Botium Toys: Audit scope and goals</b>

<br>Summary: Perform an audit of Botium Toys’ cybersecurity program. The audit needs
to align current business practices with industry standards and best practices. The
audit is meant to provide mitigation recommendations for vulnerabilities found that are
classified as “high risk,” and present an overall strategy for improving the security
posture of the organization. The audit team needs to document their findings, provide
remediation plans and efforts, and communicate with stakeholders.</br>

<br>Scope: (To understand the audit scope, review the security audit reading. Note that
the scope is not constant from audit to audit. However, once the scope of the audit is
clearly defined, only items within the scope should be audited. In this scenario, the scope is
defined as the entire security program at Botium Toys. This means all assets need to be
assessed alongside internal processes and procedures).</br>
<br>Botium Toys' internal IT audit will assess the following:</br>
<br>● Current user permissions set in the following systems: accounting, endpoint
detection, firewalls, intrusion detection system, security information, and event
management (SIEM) tool.</br>
<br>● Current implemented controls in the following systems: accounting, endpoint
detection, firewalls, intrusion detection system, Security Information, and Event
Management (SIEM) tool.</br>
<br>● Current procedures and protocols set for the following systems: accounting,
endpoint detection, firewall, intrusion detection system, Security Information, and Event Management (SIEM) tool.</br>
<br>● Ensure current user permissions, controls, procedures, and protocols in place
align with necessary compliance requirements.</br>
<br>● Ensure current technology is accounted for. Both hardware and system access.</br>

<br>Goals: (The goal of an audit is the desired deliverables or outcomes. The goal of an
audit can be to achieve compliance, to identify weaknesses or vulnerabilities within an
organization, and/or to understand failures in processes and procedures and correct
them. In this scenario, the IT manager set the goals. He is expecting a report of the
the current security posture of the organization and recommendations for improving the
the security posture of the organization, as well as the justification to hire additional
cybersecurity personnel.)</br>
<br>The goals for Botium Toys’ internal IT audit are:</br>
<br>● To adhere to the National Institute of Standards and Technology Cybersecurity
Framework (NIST CSF)</br>
<br>● Establish a better process for their systems to ensure they are compliant
<br>● Fortify system controls</br>
<br>● Implement the concept of least permissions when it comes to user credential
management</br>
<br>● Establish their policies and procedures, which include their playbooks</br>
<br>● Ensure they are meeting compliance requirements</br>
<h2>Step 2: Analyze the audit scope, goals, and risk assessments </h2>
<br>You receive the following email from your IT manager:</br>

<br>Hello!</br>

<br>I have completed the audit scope and goals, as well as a risk assessment. At a high level, the main goals and risks are as follows:</br>

<br>Goals:</br>

<br>● Improve Botium Toys’ current security posture by aligning to industry best practices (e.g., adhere to the NIST CSF, implement the concept of least permissions)</br>
<br>● Provide mitigation recommendations (i.e., controls, policies, documentation), based on current risks</br>
<br>● Identify compliance regulations Botium Toys must adhere to, primarily based on where we conduct business and how we accept payments</br>
<br>● To review the full report, read the Botium Toys: Audit Scope and Goals document</br>

<br>Risks:</br>

<br>● Inadequate management of assets</br>
<br>● Proper controls are not in place</br>
<br>● May not be compliant with U.S. and international regulations and guidelines</br>
<br>● The current risk score is 8/10 (high), due to a lack of controls and adherence to compliance regulations and standards</br>
<br>● To review the complete list of assets and risks, read the Botium Toys: Risk Assessment document </br>

<br>Thank you,</br>
<br>Botium Toys IT Manager</br>

<h3>Questions to review </h3></br>
<br><b>Question: </b> What are the biggest risks to the organization?</br>
<br><b>Response</b>-Currently, the biggest risk is the lack of controls and adherence to necessary compliance regulations and standards</br> 
<br><b>Question: </b>Which controls are most essential to implement immediately versus in the future?</br>
<br><b>Response</b>-Currently, controls are in place and are not adhering to required regulations and standards related to keeping customer data private need to be implemented immediately, or governing bodies will fine Botium Toys. The risk assessment ranks this as a high threat. To implement these controls, Implement the concept of least permissions when it comes to user credential management. In the future, establishing a better process for their systems to ensure they're compliant, and establish their policies and procedures, which includes their playbooks. The reason is the potential impact from the loss of an asset is currently only rated at a medium.</br>
<br><b>Question: </b>Which compliance regulations do Botium Toys need to adhere to, to ensure the company keeps customer and vendor data safe, avoids fines, etc.?</br>
<br><b>Response</b>-Currently, Botium Toys does not have the proper controls in place and may not be compliant with U.S. and international regulations and standards. Botium Toys need to adhere to the required regulations and standards related to keeping customer data private and this needs to be implemented immediately.</br>
<br><h2>Step 3: Conduct the audit: Controls assessment </h2></br>
<br><b> Goals </br> </b>
<br>● Fill out the Controls assessment sheet</br>
<br>● Review the list of Botium Toys’ assets</br>
<br>● Review each control name</br>
<br>● Review the control types and explanation </br>
<br>● Mark an X next to each control that needs to be implemented</br>
<br>● Note levels of priority (high, medium, and/or low; NA if not applicable)</br>
<br> (The following are the Controls Assessment template provided during this activity and a template that I've filled out using the context of the previous steps and personal knowledge)</br>
<br>[Controls assessment template.pdf](https://github.com/kalemriah/Creating-A-Security-Audit/files/12270085/Controls.assessment.templete.pdf) </br>
<br>[Controls assessment response.pdf](https://github.com/kalemriah/Creating-A-Security-Audit/files/12270087/Controls.assessment._.Filled.out.pdf) </br>
<br><h2>Step 4: Conduct the Audit: Compliance checklist </h2> </br>
<br>● Consider where the company conducts business and how they receive payments from customers.</br>
<br>● Click the boxes to select the compliance regulations and standards that Botium Toys needs to adhere to.</br>
<br>● Explain why the company needs to adhere to the selected compliance regulations and standards.</br>
<br> (The following are the Compliance checklist template provided during this activity and a template that I've filled out using the context of the previous steps and personal knowledge)</br>
<br>[Compliance checklist template.pdf](https://github.com/kalemriah/Creating-A-Security-Audit/files/12270105/Compliance.checklist.pdf)</br>
<br>[Compliance checklist Response.pdf](https://github.com/kalemriah/Creating-A-Security-Audit/files/12270106/Compliance.checklist._.Response.pdf)</br>
<br><h2>Step 5: Analyze audit results</h2></br>
<br>● What were the audit scope and goals? </br>
<br>● What were the critical findings of the audit that need to be addressed immediately (i.e., What controls and/or policies need to be implemented immediately)?</br>
<br>● What were the findings (i.e., What controls and/or policies need to be addressed in the future)?</br>
<br>● How can you summarize your recommendations clearly and concisely to stakeholders?</br>
<br><h2>Step 6: Communicate results and recommendations </br></h2>
<br>● A high-level summary of the audit goals is provided (4-6 sentences or bullet points)</br>
<br>● Critical findings are listed and explained</br>
<br>● Other findings are listed and explained</br>
<br>● The summary/recommendations clearly and concisely synthesize the most important information from the audit scope, goals, critical and other findings (5-10 sentences)</br>
<br> (The following are the Stakeholder memoradum template provided during this activity and a template that I've filled out using the context of the previous steps and personal knowledge)</br>
<br>[Stakeholder memorandum template.pdf](https://github.com/kalemriah/Creating-A-Security-Audit/files/12270143/Stakeholder.memorandum.pdf)</br>
<br>[Stakeholder memorandum response.pdf](https://github.com/kalemriah/Creating-A-Security-Audit/files/12270144/Stakeholder.memorandum._.Response.incomplete.pdf)</br>
