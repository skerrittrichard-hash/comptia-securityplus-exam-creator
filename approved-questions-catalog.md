# CompTIA Security+ (SY0-701) - Approved Practice Questions Catalog

## 📋 Quality Standards
All questions in this catalog have been evaluated and rated **9.0/10 or higher** for CompTIA exam authenticity.

**Evaluation Criteria:**
- ✅ Contains qualifier word (BEST/MOST/FIRST/LEAST)
- ✅ Clear scenario structure (when applicable)
- ✅ Plausible distractors
- ✅ Single unambiguous correct answer
- ✅ Authentic CompTIA tone and voice
- ✅ Tests application, not just memorization
- ✅ Real-world job relevance

---

## QUESTION 001 - Threat Hunting

**Rating:** 9.5/10  
**Domain:** Security Operations (Domain 4.0)  
**Topic:** Threat Hunting vs Incident Response  
**Difficulty:** Medium  
**Question Type:** Scenario-based, Single Answer

### Question:
A cyber operations team informs a security analyst about a new tactic malicious actors are using to compromise networks. SIEM alerts have not yet been configured. Which of the following best describes what the security analyst should do to identify this behavior?

A. Digital forensics  
B. E-discovery  
C. Incident response  
D. Threat hunting

### Correct Answer: D

### Explanation:
**Threat hunting** is the correct answer because the scenario requires proactive searching for threats that are not yet detected by automated systems. The key phrase "SIEM alerts have not yet been configured" indicates there is no automated detection in place, requiring manual, proactive investigation.

**Why other options are incorrect:**
- **A. Digital forensics** - This is a reactive process used after an incident has occurred to analyze evidence and determine what happened. The scenario describes proactive searching, not post-incident analysis.
- **B. E-discovery** - This is a legal/compliance process for collecting and producing electronically stored information for litigation. Not relevant to identifying malicious behavior.
- **C. Incident response** - This is a reactive process that occurs after a security incident has been detected. The scenario requires proactive identification before detection occurs.

### Key Learning Points:
- Threat hunting is **proactive** (searching for unknown threats)
- Incident response is **reactive** (responding to detected incidents)
- The absence of automated detection (SIEM alerts) is a key indicator that proactive hunting is needed

### CompTIA Exam Objective:
4.8 Explain appropriate incident response activities

---

## QUESTION 002 - Security Control Types (AUP)

**Rating:** 9.0/10  
**Domain:** Security Program Management and Oversight (Domain 5.0)  
**Topic:** Security Control Classifications  
**Difficulty:** Easy-Medium  
**Question Type:** Conceptual, Single Answer

### Question:
Which of the following security control types does an acceptable use policy best represent?

A. Detective  
B. Compensating  
C. Corrective  
D. Preventive

### Correct Answer: D

### Explanation:
**Preventive** is the correct answer because acceptable use policies (AUPs) are designed to prevent security incidents by establishing rules and expected behaviors before violations occur. The policy sets boundaries and creates awareness to prevent inappropriate use of systems.

**Why other options are incorrect:**
- **A. Detective** - Detective controls identify incidents after they occur. While AUP violations may be detected, the policy itself is not a detective control.
- **B. Compensating** - Compensating controls provide alternative protection when primary controls cannot be implemented. An AUP is not compensating for another control.
- **C. Corrective** - Corrective controls remediate incidents after they occur. While policies may guide corrective actions, the AUP itself is preventive in nature.

### Key Learning Points:
- Preventive controls aim to stop incidents before they happen
- AUPs prevent violations through user awareness and accountability
- Policies establish expectations and boundaries proactively

### CompTIA Exam Objective:
5.1 Summarize elements of effective security governance

---

## QUESTION 003 - Risk Management Strategy (Insurance)

**Rating:** 9.5/10  
**Domain:** Security Program Management and Oversight (Domain 5.0)  
**Topic:** Risk Management Strategies  
**Difficulty:** Medium  
**Question Type:** Conceptual, Single Answer

### Question:
A company purchased cyber insurance to address items listed on the risk register. Which of the following risk management strategies does this BEST represent?

A. Accept  
B. Transfer  
C. Mitigate  
D. Avoid

### Correct Answer: B

### Explanation:
**Transfer** is the correct answer because purchasing cyber insurance transfers the financial risk to the insurance company. While the company retains operational risks, the monetary impact of potential incidents is shifted to the insurer.

**Why other options are incorrect:**
- **A. Accept** - Risk acceptance means acknowledging risk and taking no action. Purchasing insurance is an active risk management strategy, not acceptance. (Note: The deductible represents accepted risk, but the overall strategy is transfer)
- **C. Mitigate** - Mitigation reduces the likelihood or impact of risk through controls. Insurance doesn't reduce risk occurrence; it transfers financial impact.
- **D. Avoid** - Risk avoidance eliminates the risk by not performing the activity. The company continues operations, so risk isn't avoided.

### Key Learning Points:
- Risk transfer shifts financial consequences to another party
- Insurance is the most common form of risk transfer
- Companies often combine strategies (transfer + accept deductible + mitigate with controls)

### CompTIA Exam Objective:
5.4 Explain the importance of applicable regulations, standards, or frameworks that impact organizational security posture

---

## QUESTION 004 - Least Privilege Principle

**Rating:** 9.5/10  
**Domain:** Security Architecture (Domain 2.0)  
**Topic:** Security Principles - Least Privilege  
**Difficulty:** Easy-Medium  
**Question Type:** Scenario-based, Single Answer

### Question:
An IT manager informs the entire help desk staff that only the IT manager and the help desk lead will have access to the administrator console of the help desk software.

Which of the following security principles does this scenario BEST demonstrate?

A. Hardening  
B. Employee monitoring  
C. Configuration enforcement  
D. Least privilege

### Correct Answer: D

### Explanation:
**Least privilege** is the correct answer because the scenario demonstrates restricting access to only those individuals who need it to perform their job functions. Only two people (IT manager and help desk lead) receive administrative access, while other staff receive only what they need for their roles.

**Why other options are incorrect:**
- **A. Hardening** - System hardening involves reducing attack surface by removing unnecessary services, not managing user access levels.
- **B. Employee monitoring** - This involves tracking user activities, not restricting access based on job requirements.
- **C. Configuration enforcement** - While access control is part of configuration, the principle being demonstrated is specifically least privilege, not general configuration management.

### Key Learning Points:
- Least privilege grants minimum access necessary for job functions
- Administrative access should be limited to those who require it
- This reduces risk by limiting potential for accidental or malicious misuse

### CompTIA Exam Objective:
2.1 Compare and contrast security implications of different architecture models

---

## QUESTION 005 - Cloud Shared Responsibility Model

**Rating:** 9.5/10  
**Domain:** Security Architecture (Domain 2.0)  
**Topic:** Cloud Security - Shared Responsibility Model  
**Difficulty:** Medium  
**Question Type:** Scenario-based, Single Answer

### Question:
A company is using an IaaS cloud model to host its customer database. According to the shared responsibility model, which of the following is PRIMARILY responsible for securing the database and its contents?

A. Client  
B. Third-party vendor  
C. Cloud provider  
D. Database administrator

### Correct Answer: A

### Explanation:
**Client** is the correct answer because in the IaaS (Infrastructure as a Service) model, the cloud provider secures the infrastructure layer (compute, storage, network), while the client organization is responsible for securing everything above that, including operating systems, applications, data, and access controls. The client owns responsibility for database security and data protection.

**Why other options are incorrect:**
- **B. Third-party vendor** - Unless specifically contracted, third-party vendors are not part of the standard shared responsibility model for IaaS.
- **C. Cloud provider** - In IaaS, the cloud provider secures the infrastructure (physical servers, hypervisor, network) but not the database layer or data.
- **D. Database administrator** - While the DBA performs security tasks, they are part of the client organization. Organizational responsibility lies with the client, not an individual role.

### Key Learning Points:
- IaaS: Cloud provider = infrastructure; Client = OS, apps, data
- PaaS: Cloud provider = infrastructure + platform; Client = apps, data
- SaaS: Cloud provider = infrastructure + platform + apps; Client = data + access
- Understanding who secures what is critical for cloud security

### CompTIA Exam Objective:
2.1 Compare and contrast security implications of different architecture models

---

## QUESTION 006 - Business Documentation (SOW)

**Rating:** 9.5/10  
**Domain:** Security Program Management and Oversight (Domain 5.0)  
**Topic:** Governance Documentation  
**Difficulty:** Medium  
**Question Type:** Scenario-based, Single Answer

### Question:
A client asked a security company to provide a document outlining the project scope, the cost, and the completion time frame.

Which of the following documents would be MOST appropriate for the company to provide?

A. MSA  
B. SLA  
C. BPA  
D. SOW

### Correct Answer: D

### Explanation:
**SOW (Statement of Work)** is the correct answer because it is the document that specifically outlines project details including scope, deliverables, costs, timeline, and milestones for a specific engagement or project.

**Why other options are incorrect:**
- **A. MSA (Master Service Agreement)** - This establishes general terms and conditions for an ongoing business relationship, not specific project details. It's the framework under which multiple SOWs may be executed.
- **B. SLA (Service Level Agreement)** - This defines performance metrics, uptime guarantees, and service quality expectations, not project scope and costs.
- **C. BPA (Business Partnership Agreement)** - This establishes terms for a business partnership between organizations, not project-specific deliverables and timelines.

### Key Learning Points:
- SOW = Specific project scope, deliverables, costs, timeline
- MSA = General framework for ongoing relationship
- SLA = Performance and service level commitments
- BPA = Partnership terms between organizations

### CompTIA Exam Objective:
5.1 Summarize elements of effective security governance

---

## QUESTION 007 - Data Source Investigation (Endpoint Logs)

**Rating:** 9.5/10  
**Domain:** Security Operations (Domain 4.0)  
**Topic:** Log Analysis and Investigation  
**Difficulty:** Medium  
**Question Type:** Scenario-based, Single Answer

### Question:
A security analyst is reviewing alerts in the SIEM related to potential malicious network traffic coming from an employee's corporate laptop. The security analyst has determined that additional data about the executable running on the machine is necessary to continue the investigation.

Which of the following would provide the MOST detailed information about the executable?

A. Application  
B. IPS/IDS  
C. Network  
D. Endpoint

### Correct Answer: D

### Explanation:
**Endpoint** logs are the correct answer because they provide the most comprehensive information about processes, executables, and system-level activity occurring on the specific device. Endpoint logs capture detailed data including process names, file hashes, command-line arguments, parent-child process relationships, and execution timestamps.

**Why other options are incorrect:**
- **A. Application** - Application logs track application-specific events (errors, transactions) but typically don't provide detailed executable information like file hashes or process behavior.
- **B. IPS/IDS** - These logs capture network-based signatures and traffic patterns but don't provide host-level details about specific executables running on the machine.
- **C. Network** - Network logs show traffic patterns, connections, and protocols but lack information about the actual processes and executables generating that traffic on the endpoint.

### Key Learning Points:
- Endpoint logs = detailed host-level data (processes, executables, system events)
- Network logs = traffic patterns and connections
- Application logs = application-specific events
- Use endpoint logs for investigating suspicious processes and executables

### CompTIA Exam Objective:
4.8 Explain appropriate incident response activities

---

## QUESTION 008 - Laptop Data Protection (Full Disk Encryption)

**Rating:** 9.0/10  
**Domain:** Security Architecture (Domain 2.0)  
**Topic:** Encryption Technologies  
**Difficulty:** Easy-Medium  
**Question Type:** Scenario-based, Single Answer

### Question:
A company requires that all data on employee laptops, including the operating system and temporary files, be encrypted to protect against data theft if a device is lost or stolen.

Which of the following would BEST meet this requirement?

A. File-level encryption  
B. Partition encryption  
C. Full disk encryption  
D. Database encryption

### Correct Answer: C

### Explanation:
**Full disk encryption** is the correct answer because it encrypts the entire disk, including the operating system, system files, temporary files, and all user data. This provides comprehensive protection against unauthorized access if the device is lost or stolen.

**Why other options are incorrect:**
- **A. File-level encryption** - This encrypts individual files or folders but does not protect the operating system, system files, or temporary files created during normal operations.
- **B. Partition encryption** - This encrypts specific partitions but may not cover all partitions on the device, potentially leaving the OS partition or recovery partitions unencrypted.
- **D. Database encryption** - This is specific to protecting database contents and is not applicable to general laptop data protection including OS and temporary files.

### Key Learning Points:
- Full disk encryption (FDE) = entire disk including OS and all files
- File-level encryption = selected files/folders only
- FDE protects against physical theft scenarios
- Common FDE solutions: BitLocker (Windows), FileVault (macOS), LUKS (Linux)

### CompTIA Exam Objective:
2.4 Summarize authentication and authorization design concepts

---

## QUESTION 009 - [Next Question]

[Template ready for next approved question]

---

**Total Questions in Catalog:** 8  
**Last Updated:** February 16, 2026  
**Catalog Version:** 1.2
