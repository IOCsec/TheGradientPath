# From Linkedin post, by owner + My notes

<br>
<br>

**💡 My Notes:**

### ℹ️ Offensive RedTeam project (Agentic Based):
* https://github.com/IOCsec/TheGradientPath/tree/master/RealWorldProjects/RedAmon  [PATH]
* Docker (Portainer Stacks Recommended)

<br>
<br>

---

## Owner description ➜ Linkedin:
What if an AI could hack into a system faster than a human pentester for standard CVEs?

A research paper from Portland State University changed how I think about standard offensive security.
An AI that performs complete penetration tests  reconnaissance, exploitation, post-exploitation all autonomously.

I had to build it.
And now I'm giving it away for free.

🎬 Video Tutorial: https://lnkd.in/ddQW3wev
📦 GitHub (100% Free): https://lnkd.in/dqXHpCsa
📄 Research Paper (Inspiration): https://lnkd.in/dc8Apu5w

Discover RedAmon, an open-source AI-powered red team framework that automates the entire offensive security lifecycle.

⚡ What RedAmon Actually Does:
Give it a domain. Walk away. Come back to a complete attack surface map, discovered vulnerabilities, and if you approve exploited systems with active shells.
The AI agent:
→ Discovers subdomains, scans ports, fingerprints technologies
→ Maps everything into a Neo4j knowledge graph
→ Reasons about what to attack next (ReAct pattern)
→ Executes exploits via Metasploit
→ Performs post-exploitation autonomously
→ Asks for human approval only when it's about to do something dangerous

The Tech Stack (Yes, All Open Source):

🛡️ Security Tools via MCP & Recon Pipeline:

Reconnaissance & OSINT:
• Naabu - Lightning-fast port scanning
• Httpx - HTTP probing with tech detection
• Nuclei - 9,000+ vulnerability templates
• Katana - Advanced web crawling
• GAU - Wayback Machine URL discovery
• Knockpy - Active subdomain bruteforce
• Kiterunner - API endpoint discovery
• Wappalyzer - Technology fingerprinting
• python-whois - WHOIS lookups
• dnspython - DNS resolution

Exploitation & Vuln Management:
• Metasploit Framework - Stateful exploitation console
• GVM/OpenVAS - 170,000+ Network Vulnerability Tests
• NVD & Vulners API - CVE intelligence

Data Sources & APIs:
• Shodan InternetDB - Passive reconnaissance
• GitHub API - Secret hunting
• crt.sh - Certificate transparency
• HackerTarget API - Subdomain enumeration
• MITRE ATT&CK/CWE/CAPEC - Threat framework mapping
• Tor + proxychains4 - Anonymous scanning
• LangGraph - Agentic graph orchestration
• LangChain - LLM framework integration
• FastMCP - Model Context Protocol servers
• GPT-4.1 / Claude - LLM backbone
• Text-to-Cypher - Natural language to graph queries
• ReAct Pattern - Reasoning + Acting loops
• MemorySaver - Session persistence

🏗️ Infrastructure:
• Next.js 16 + React 19 + TypeScript 5.7
• FastAPI + Uvicorn + WebSocket streaming
• Neo4j Graph Database + APOC
• Docker + Docker Compose + Kali Linux
• Python 3.11 + Go 1.21.5 + Node.js 22
