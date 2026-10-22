# Threats vs. Vulnerabilities 

A simple comparison between "Threats" and "Vulnerabilities" in cybersecurity.

## 1. Core Definitions & Analogies

1) **Threats**
  - **Definition:** Anything (person, event, or condition) that can potentially cause harm by exploiting a weakness in a system.
  - **Simple Analogy:** It’s the danger which is the external thing that could happen to cause damage.
2) **Vulnerabilities**
  - **Definition:** A weakness or flaw in a system that can be exploited by a threat to cause harm.
  - **Simple Analogy:** It’s the weak spot that makes an attack possible.


## 2. Scenario Example

1) **Threats**
  - **Zero-Day Exploit:** An attack by a cybercriminal group using a previously unknown vulnerability to software application before the vendor has a chance to create a patch. (Reasoning: An active, highly sophisticated external attack by malicious actors.)
  - **Credential Stuffing:** Brute-forcing a login page using millions of username and password pairs leaked from previous data breaches on other websites. (Reasoning: An automated cyberattack campaign aimed at unauthorized account access.)

2) **Vulnerabilities**
  - **Hardcoded Credentials:** A developer leaves a database password directly in the application source code instead of using environment variables. (Reasoning: A serious coding design flaw that exposes internal access if the code is accessed.)
  - **Missing Multi-Factor Authentication (MFA):** An enterprise admin portal allows employees to access sensitive internal systems using only a single password. (Reasoning: A structural weakness in access controls that makes accounts easy to compromise if credentials are stolen.)


## 3. How They Work Together
In cybersecurity, a risk only materializes when a **threat** successfully targets and exploits a **vulnerability**. Identifying vulnerabilities (through vulnerability assessments) helps organizations patch their weak spots before a threat actor can take advantage of them.
