# Threat Modeling for Privacy

Threat modeling is a structured approach to identifying, evaluating, and addressing potential privacy and security risks. This systematic process helps you understand what you're protecting, who might want it, and how to defend it effectively.

## What is a Privacy Threat Model?

A privacy threat model is a systematic analysis of:

1. What data you have that needs protection
2. Who might want that data (threat actors)
3. How they might try to access it (attack vectors)
4. What harm could result if they succeed
5. What measures can mitigate these risks

Unlike security threat models that focus primarily on system integrity, privacy threat models center on data confidentiality, user autonomy, and contextual integrity.

## Key Threat Modeling Frameworks

### LINDDUN Framework

Privacy specialists frequently turn to LINDDUN, which stands for:

- **L**inkability: Can separate data actions be linked to the same person?
- **I**dentifiability: Can a person's identity be determined from the data?
- **N**on-repudiation: Can a user deny having performed an action?
- **D**etectability: Can an attacker determine that data exists or is being transmitted?
- **D**isclosure of information: Can an attacker access confidential data?
- **U**nawareness: Are users fully aware of what data is collected and how it's used?
- **N**on-compliance: Does the system violate regulations or privacy policies?

This framework helps identify privacy threats that might be overlooked in traditional security analyses.

## Practical Threat Modeling Process

### 1. Define Your Assets

Start by cataloging what you're protecting:

- Personal identifiers (name, email, address)
- Authentication credentials
- Financial information
- Communications content
- Metadata (location, connection times, device info)
- Behavioral data (browsing habits, app usage)
- Professional information
- Network of contacts

### 2. Map Your Data Flows

Document how data moves through systems:
- Where data is stored
- Who has access
- How it's transmitted
- How long it's retained
- What processing occurs
- Where it might be exposed

Creating data flow diagrams (DFDs) provides visual clarity on potential vulnerability points.

### 3. Identify Threat Actors

Consider who might want your data:

| Threat Actor | Motivation | Capabilities | Examples |
|--------------|------------|--------------|----------|
| Commercial entities | Revenue, competitive advantage | Legal access methods, advanced analytics | Ad networks, data brokers, competitors |
| Governments | Intelligence, law enforcement | Legal powers, sophisticated capabilities | National security agencies, law enforcement |
| Malicious individuals | Financial gain, revenge, stalking | Varies widely, social engineering | Scammers, ex-partners, stalkers |
| Employer | Monitoring, productivity assessment | Administrative access, legal authority | IT departments, managers |
| Hackers | Financial gain, challenge, activism | Technical exploits, social engineering | Criminal groups, hacktivists |

### 4. Assess Attack Vectors

For each threat actor, consider how they might access your data:

- Data breaches
- Legal processes (subpoenas, warrants)
- Social engineering
- Network surveillance
- Device compromise
- Insider access
- Data inference from multiple sources
- Purchasing from data brokers

### 5. Determine Potential Harm

Assess what's at stake if your privacy is compromised:

- Financial loss
- Reputation damage
- Loss of opportunity
- Harassment or discrimination
- Physical safety risks
- Identity theft
- Manipulation or exploitation
- Loss of autonomy

### 6. Evaluate Risk Levels

For each identified threat, assess:
- Likelihood of occurrence
- Potential impact severity
- Existing mitigations

Use a simple matrix to prioritize:

```
High Impact/High Likelihood → Address immediately
High Impact/Low Likelihood → Plan mitigations
Low Impact/High Likelihood → Implement quick fixes
Low Impact/Low Likelihood → Monitor
```

## Real-World Example: Journalist's Threat Model

### Assets
- Source identities and communications
- Unpublished story materials
- Contact networks
- Location data
- Communication metadata

### Threat Actors
- Government agencies
- Subject of investigation
- Competitors
- Hackers targeting sensitive information

### Attack Vectors
- Legal demands for records
- Device seizure
- Network surveillance
- Spear-phishing
- Malware

### Potential Harms
- Source exposure
- Investigation compromise
- Physical danger to sources
- Self-censorship due to surveillance concerns

### Mitigations
- End-to-end encrypted communications
- Anonymous tip channels
- Compartmentalized information
- Secure device handling
- Regular security audits

## Practical Application: Creating Your Threat Model

1. Create a table with these columns:
   - Data asset
   - Who wants it
   - How they might get it
   - What harm could result
   - Current protections
   - Needed improvements

2. Prioritize based on risk level
3. Implement appropriate controls
4. Periodically review and update

## From Threat Model to Action

A good threat model leads to concrete actions:

1. **Technical controls**: Encryption, access controls, etc.
2. **Policy changes**: Data minimization, retention limits
3. **Training needs**: Awareness of specific threats
4. **Process improvements**: Regular audits, incident response
5. **Design modifications**: Privacy by design implementations

## Common Pitfalls in Privacy Threat Modeling

- **Over-focusing on exotic threats** while missing common risks
- **Analysis paralysis** from overly complex models
- **Security-onl