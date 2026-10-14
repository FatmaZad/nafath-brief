Overview

A national service provider may depend upon software, AI systems, mobile applications, and internet networks to offer its services to users. In each case — whether we're talking about securing software, AI systems, mobile apps or networking infrastructure there's an element of cybersecurity involved.
Security features within software ensure things like user passwords, cryptographic keys and app settings remain hidden. With AI security, it's important for companies to make sure they're preventing malicious actors from tampering with their models or corrupting their training data. Meanwhile, security measures implemented into mobile apps should verify that applications meet certain recognised security criteria. And cyber protections surrounding networked devices seek to minimise potential misrouting of internet traffic over unauthorised paths.
Other types of cybersecurity practice, meanwhile, might see teams seeking to proactively uncover vulnerabilities in their IT system, fixing them ahead of time to avoid exploitation by malevolent agents. Data security practices may include things like keeping track of what software components you need via a Software Bill Of Materials (SBOM).
By bringing together all these different aspects of cybersecurity — including those specific to artificial intelligence, mobile computing or networking  organisations can get a clearer picture of the threats they face, enabling them to more effectively safeguard their own operations and the public's trust.

## Software

The Twelve-Factor App methodology recommends storing configuration in environment variables instead of hard-coding it in application code. This includes database connection details and credentials for external services. Keeping configuration separate makes it easier to run the same application in different environments without changing the code. Secrets should be protected with appropriate access controls and, where possible, a dedicated secrets manager. If credentials are included in code and uploaded to a public repository, they may be exposed to unauthorised people.

Resource: The Twelve-Factor App — Config - https://12factor.net/config

##AI 

Adversarial attacks on machine learning systems primarily fall into categories like poisoning and evasion, which differ mainly by when and how they occur. Poisoning attacks target the training phase by injecting malicious data or labels to corrupt the model's foundational behavior. In contrast, evasion attacks happen during the testing or deployment phase, where attackers subtly tweak inputs—like adding imperceptible noise to an image—to fool a fully trained model into misclassification.

Resource: NIST AI 100-2 E2025: Adversarial Machine Learning — https://csrc.nist.gov/pubs/ai/100/2/e2025/final

## Mobile

The OWASP Mobile Application Security Verification Standard (MASVS) is an industry-standard framework that defines security and privacy requirements for mobile apps. It breaks down security controls into specific categories—such as secure data storage, cryptography, network communication, and platform interaction. Development and security teams use MASVS as a benchmark to design secure architectures, establish a baseline for code reviews, and verify compliance through structured penetration testing.
Resource: OWASP Mobile Application Security Verification Standard (MASVS) — https://mas.owasp.org/MASVS/
