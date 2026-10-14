## Overview

A national service provider may depend upon software, AI systems, mobile applications, and internet networks to offer its services to users. In each case — whether we're talking about securing software, AI systems, mobile apps or networking infrastructure there's an element of cybersecurity involved.
Security features within software ensure things like user passwords, cryptographic keys and app settings remain hidden. With AI security, it's important for companies to make sure they're preventing malicious actors from tampering with their models or corrupting their training data. Meanwhile, security measures implemented into mobile apps should verify that applications meet certain recognised security criteria. And cyber protections surrounding networked devices seek to minimise potential misrouting of internet traffic over unauthorised paths.
Other types of cybersecurity practice, meanwhile, might see teams seeking to proactively uncover vulnerabilities in their IT system, fixing them ahead of time to avoid exploitation by malevolent agents. Data security practices may include things like keeping track of what software components you need via a Software Bill Of Materials (SBOM).
By bringing together all these different aspects of cybersecurity — including those specific to artificial intelligence, mobile computing or networking  organisations can get a clearer picture of the threats they face, enabling them to more effectively safeguard their own operations and the public's trust.

## Software

Application configuration, such as database settings and API keys, should be stored separately from the source code. The Twelve-Factor App methodology recommends using environment variables for configuration. Keeping secrets out of the code reduces the risk of exposing sensitive information when code is shared or uploaded to a public repository. Access to secrets should also be controlled carefully.

Resource: The Twelve-Factor App — Config - https://12factor.net/config

## AI

Adversarial attacks on machine learning systems primarily fall into categories like poisoning and evasion, which differ mainly by when and how they occur. Poisoning attacks target the training phase by injecting malicious data or labels to corrupt the model's foundational behavior. In contrast, evasion attacks happen during the testing or deployment phase, where attackers subtly tweak inputs—like adding imperceptible noise to an image—to fool a fully trained model into misclassification.

Resource: NIST AI 100-2 E2025: Adversarial Machine Learning — https://csrc.nist.gov/pubs/ai/100/2/e2025/final

## Mobile 

The OWASP Mobile Application Security Verification Standard (MASVS) is an industry-standard framework that defines security and privacy requirements for mobile apps. It breaks down security controls into specific categories—such as secure data storage, cryptography, network communication, and platform interaction. Development and security teams use MASVS as a benchmark to design secure architectures, establish a baseline for code reviews, and verify compliance through structured penetration testing. 

Resource: OWASP Mobile Application Security Verification Standard (MASVS) — https://mas.owasp.org/MASVS/

## Networking

BGP route hijacking occurs when an unauthorized network falsely advertises ownership of an IP prefix, redirecting internet traffic away from its true destination. Resource Public Key Infrastructure (RPKI) prevents this via cryptographic Route Origin Authorizations (ROAs) that verify whether an Autonomous System is permitted to announce a prefix. However, standard RPKI only validates the origin and does not protect against path manipulation or malicious AS-path spoofing.  

Resource: NIST SP 1800-14: Protecting the Integrity of Internet Routing — https://csrc.nist.gov/pubs/sp/1800/14/finallookups by default.

## Cyber Security

Log4Shell (CVE-2021-44228) is a critical remote code execution vulnerability in Apache Log4j, a widely used Java logging library. It was rated a maximum 10.0 severity because attackers could easily exploit it by injecting a malicious string that forced the server to download and execute arbitrary code, granting full system control. It was fixed by updating Log4j to version 2.17.1 or newer to disable message lookups by default. 

Resource: CISA Advisory (AA21-356A): Mitigating Log4Shell and Other Log4j-Related Vulnerabilities — https://www.cisa.gov/news-events/cybersecurity-advisories/aa21-356a

## Data

A Software Bill of Materials (SBOM) is a formal, nested inventory detailing the components, libraries, and open-source dependencies used to build a software application. To be effective, an SBOM should include critical minimum data fields such as the supplier name, component name, software version, dependency relationships, unique identifiers like PURLs, and the author of the SBOM data to ensure complete supply-chain visibility.

Resource: CISA Software Bill of Materials (SBOM) — https://www.cisa.gov/sbom
