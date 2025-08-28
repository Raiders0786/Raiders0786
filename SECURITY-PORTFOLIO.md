# Security Research Portfolio

## Vulnerability Research and Disclosure

### Research Summary
**2 Published CVEs** | **Synack Red Team Member** | **150+ Private Assessments** | **Multiple Bug Bounties**

I work as a professional security researcher focusing on web application security, API testing, and enterprise infrastructure assessments. My research spans both public bug bounty programs and private enterprise engagements through the Synack platform.

### Published CVEs

**CVE-2023-3067 - Stored XSS in Note-Taking Application**
- Found stored cross-site scripting vulnerability in a popular note-taking application with over 30,000 GitHub stars
- The vulnerability affected thick client applications through DOM manipulation and local storage poisoning
- **Technical details:** [Huntr disclosure](https://huntr.com/bounties/4772ceb7-1594-414d-9b20-5b82029da7b6)

**CVE-2022-4722 - Authentication Bypass via Username Collision**  
- Discovered primary key logic flaw in ikus060/rdiffweb backup management software
- Non-unique username constraints allowed account takeover through strategic username registration
- **Technical details:** [Huntr disclosure](https://huntr.com/bounties/c62126dc-d9a6-4d3e-988d-967031876c58)

## Professional Security Research

### Synack Red Team Researcher
Working as a vetted researcher on the [Synack Red Team platform](https://www.synack.com/red-team/), conducting security assessments for Fortune 500 companies and enterprise clients. I've reported over 150 vulnerabilities through private engagements, focusing on:

- Complex business logic flaws in enterprise applications
- API security testing and authentication bypass techniques  
- Cloud infrastructure misconfigurations and privilege escalation paths
- Advanced persistent threat simulation and lateral movement scenarios

### Public Bug Bounty Programs

**Monetary bounties received:**
- **E-bay** - Multiple account takeover vulnerabilities and business logic bypasses
- **Dba.dk** - SQL injection leading to database compromise and sensitive data exposure
- **Azena** - Authorization bypass allowing PII data access across user boundaries
- **Mobile.de** - Stored XSS with session hijacking capabilities and business logic manipulation
- **Tebex.io** - Mass assignment vulnerability leading to administrative privilege escalation
- **Site.pro** - Server-side request forgery with internal network enumeration
- **Athento.com** - Template injection vulnerability with potential RCE implications

**Hall of fame recognition:**
- **Post.nl** - Reflected XSS with CSRF token extraction
- **mmc.nl** - Authorization bypass and secret key exposure in API endpoints  
- **free.law** - Remote file inclusion with directory traversal capabilities
- **linkiti.com** - Account takeover through session fixation and business logic flaws
- **powerassist.nl** - Parameter pollution leading to sensitive file exposure

## Platform Security Discoveries

### Major Developer Platform Vulnerabilities
- **GitBook** - Stored XSS vulnerability in documentation rendering engine
- **HackerRank** - Account takeover in support ticketing system through session management flaws
- **HashNode** - Critical information disclosure with MongoDB connection strings and API keys exposed in client-side JavaScript bundles
- **CodeChef** - Sandbox escape vulnerability in code execution environment allowing arbitrary command execution

## Technical Expertise

### Vulnerability Categories
**Authentication and authorization flaws:**
- Horizontal and vertical privilege escalation techniques
- Account takeover through session management vulnerabilities
- OAuth implementation flaws and JWT token manipulation
- Multi-factor authentication bypass methods

**Injection vulnerabilities:**
- SQL injection (union-based, boolean blind, time-based, second-order)
- Cross-site scripting (DOM-based, stored, reflected with CSP bypass techniques)
- Template injection in various engines (Jinja2, Twig, Velocity)
- NoSQL injection in MongoDB and Elasticsearch implementations

**Information disclosure:**
- Database credential extraction from client-side code
- API key and environment variable leakage through source code analysis
- Internal network enumeration via SSRF and DNS rebinding
- Sensitive file exposure through directory traversal and LFI/RFI

**Advanced techniques:**
- Sandbox escape in containerized execution environments
- Server-side request forgery with protocol smuggling
- HTTP parameter pollution and request smuggling
- Race condition exploitation in concurrent processes

---

*Committed to responsible vulnerability disclosure and ethical security research practices*

### Security Contact
[For security-related collaboration or consultation inquiries](https://t.me/Raiders0786), please reach out through appropriate secure channels.

**Disclaimer:** All security research activities are conducted with proper authorization and follow established responsible disclosure guidelines.
