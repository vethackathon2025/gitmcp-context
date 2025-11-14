(# Curriculum Exercises)

This file lists practical, scaffolded exercises mapped to the topics contained in the module library (Security+, CEH, CISSP, OSCP). Each exercise includes: learning objective, steps, time estimate, assessment criteria, materials, and short notes on adaptation or accessibility.

---

## Security+ exercises

### 1) Network Security: Packet Analysis Lab
- Learning objective: Identify common network attacks (ARP spoofing, port scanning, malformed packets) using packet captures and basic IDS alerts.
- Time estimate: 90 minutes
- Steps:
	1. Provide a pcap file and a short network diagram.
	2. Use Wireshark to filter for suspicious patterns (e.g., repeated ARP replies, SYN scans).
	3. Correlate events with simple IDS alerts (provided log snippets).
	4. Produce a one-page SITREP describing the incident, likely impact, and recommended mitigation.
- Assessment criteria:
	- Correct identification of at least two suspicious indicators.
	- Reasonable mapping from indicators to likely cause and mitigations.
	- Clear, concise SITREP (<=1 page).
- Materials: pcap file, Wireshark (or cloud packet viewer), sample IDS logs, network diagram.
- Adaptation: For short-format learners, provide guided filters and highlighted timestamps; for advanced learners, include obfuscated traffic and require custom tcpdump filters.

### 2) Cryptography: Apply & Verify
- Learning objective: Use public-key and symmetric primitives appropriately and verify digital signatures.
- Time estimate: 60 minutes
- Steps:
	1. Given a short scenario (secure file transfer between two parties), choose symmetric/asymmetric components.
	2. Use OpenSSL or a browser-based tool to generate a keypair, sign a message, and verify.
	3. Explain why chosen algorithms and key sizes are appropriate.
- Assessment criteria:
	- Correct key generation and signature verification.
	- Reasoned justification for algorithm/key-size selection.
- Materials: OpenSSL installed or online crypto sandbox, short scenario prompt.
- Accessibility: Provide step-by-step commands and a transcript for screen-reader users.

---

## CEH exercises

### 3) Reconnaissance & Footprinting: Recon Challenge
- Learning objective: Gather open-source intelligence (OSINT) to build an initial target profile while following ethical and legal constraints.
- Time estimate: 90 minutes
- Steps:
	1. Given a fictional target domain, perform OSINT: DNS lookups, subdomain enumeration, public code search, and employee discovery (public profiles only).
	2. Document findings in a structured template: assets, exposed services, possible entry points, and risk level.
	3. Propose a prioritized next-step plan for a penetration test (non-destructive).
- Assessment criteria:
	- Completeness of the profile and appropriate use of OSINT tools.
	- Ethical adherence (no active scanning if disallowed in prompt).
	- Clear prioritization and rationale.
- Materials: Recon template, list of allowed tools, internet access or sandboxed datasets.
- Adaptation: Provide canned outputs for novices; require live tool use for advanced learners.

### 4) Web Application Vulnerability: Exploit & Patch
- Learning objective: Find a common web vulnerability (e.g., SQLi or XSS), create a safe proof-of-concept, and propose a patch.
- Time estimate: 2–3 hours
- Steps:
	1. Access a provided intentionally vulnerable web app (lab instance or DVWA-like environment).
	2. Enumerate inputs, test for SQLi/XSS, and capture evidence following safe-lab rules.
	3. Write a short remediation plan (input validation, parameterized queries, CSP headers, etc.).
	4. (Optional advanced) Implement a patch and re-test.
- Assessment criteria:
	- Correct identification of vulnerability and factual POC evidence.
	- Practical, prioritized remediation steps.
	- Safe conduct and lab rules followed.
- Materials: Lab web app, browsing tools, short lab rules doc.

### 5) Social Engineering Risk Assessment (Short)
- Learning objective: Identify human-targeted vulnerabilities and propose mitigations.
- Time estimate: 60 minutes
- Steps:
	1. Read a brief case study of an org's onboarding and communication flows.
	2. Identify 4–6 vectors where social engineering could succeed (phishing, vishing, tailgating).
	3. Propose low-cost mitigations and a 30/60/90 day rollout for awareness.
- Assessment criteria:
	- Practicality of mitigations and realistic rollout plan.
	- Clear articulation of the likely impact and cost/benefit.
- Materials: Case study, template for mitigation plan.

---

## CISSP exercises

### 6) Risk Management Tabletop
- Learning objective: Run a brief risk assessment using a small enterprise scenario and map controls to risk reduction.
- Time estimate: 90–120 minutes
- Steps:
	1. Present a scenario (e.g., cloud migration with PII data).
	2. Identify assets, threats, vulnerabilities, and potential impact.
	3. Use a simple risk matrix (likelihood × impact) to prioritize risks.
	4. Map controls (technical, administrative, physical) and produce a prioritized remediation list.
- Assessment criteria:
	- Logical asset-threat mapping and reasonable risk ratings.
	- Appropriate control selection and prioritization.
	- Clear owner assignment for top 3 risks.
- Materials: Scenario doc, risk matrix template.
- Adaptation: Short format: provide pre-filled asset list; longer format: expect independent asset discovery.

### 7) Policy Mapping: From Requirement to SOP
- Learning objective: Convert a high-level compliance requirement (e.g., NIST control) into a short SOP and operational checklist.
- Time estimate: 60 minutes
- Steps:
	1. Provide a single control requirement (audit logging, least privilege, etc.).
	2. Draft a one-page SOP that includes scope, roles, steps, and a short checklist for compliance.
	3. Annotate how the SOP supports the requirement and how success will be measured.
- Assessment criteria:
	- SOP clarity and testability.
	- Measurable success criteria.
- Materials: Example regulatory/control text; SOP template.

---

## OSCP / Advanced pentest exercises

### 8) Lab Box: Hypothetical Exploit (guided)
- Learning objective: Perform a full exploit chain in a controlled lab box: initial foothold, privilege escalation, and evidence capture.
- Time estimate: 4–8 hours (lab-paced)
- Steps:
	1. Use a provided isolated lab VM with seeded vulnerabilities.
	2. Perform reconnaissance, exploit a service to gain a shell, enumerate for privilege escalation vectors, and document steps.
	3. Capture proof (screenshots, command logs) and write a short technical report describing the chain and mitigations.
- Assessment criteria:
	- Evidence of successful exploitation and escalation.
	- Clear chain-of-evidence and mitigation recommendations.
	- Ethical, responsible lab behavior and no external scanning.
- Materials: Isolated lab VM, safe lab rules, reporting template.
- Accessibility/Notes: Provide time checkpoints and hints for learners who need scaffolding; advanced track removes hints.

### 9) Buffer Overflow Mini-Project
- Learning objective: Understand a basic stack buffer overflow and craft a minimal reproducible exploit or demonstrate mitigations.
- Time estimate: 3–6 hours
- Steps:
	1. Provide a small vulnerable C program and build instructions.
	2. Identify overflow point, create a controlled input to crash and then to hijack control flow (with ASLR/DEP guidance depending on difficulty).
	3. Document mitigation strategies (stack canaries, DEP, ASLR, safe functions) and show how they change exploitability.
- Assessment criteria:
	- Demonstrable reproduction of behavior (crash or exploit) and understanding of mitigations.
	- Clean write-up of steps and defensive guidance.
- Materials: Code repo, compiler toolchain, VM instructions.

---

## Cross-cutting exercise notes

- Group vs individual: Many labs can be run individually or as small teams (2–4) for red-team/blue-team rotations.
- Grading: Use rubrics tied to the assessment criteria above (evidence, reasoning, remediation quality, and safe conduct).
- Accessibility & low-bandwidth alternatives: Provide pre-captured outputs and guided walkthroughs; provide transcripts and text-only materials for screen readers.
