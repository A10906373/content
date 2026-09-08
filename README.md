
# https://github.com/nathanchenstudio/Marionfl
# https://github.com/nathanchenstudio/A58Spider
# https://github.com/nathanchenstudio/DnbSpider
# https://github.com/nathanchenstudio/ShoesCrawler
# https://github.com/B38834-24-0448/pea.go.th/blob/Electricity/131246/B38834-24-0448.yaml
# Guidelines for Legal Requests of User Data
# GitHub Terms of Service

# IP-HUNTER v2.1.0-ai | Advanced DDoS Toolkit & AI-Powered Security Suite

**© 2026 Nattapong Tapachoom. สิทธิในทรัพย์สินทางปัญญาและลิขสิทธิ์ทั้งหมดเป็นของ ณัฐพงศ์ ตะปะชุม**
**[PROPRIETARY SOFTWARE - RESTRICTED DISTRIBUTION]**

**🚀 AI Integration Release: Offensive Red Team Training & Strategy Generation**

---

### 🏛️ ประกาศทางกฎหมายและข้อตกลงการใช้งาน (Strict Legal Notice)

**ซอฟต์แวร์นี้เป็นทรัพย์สินทางปัญญาของ ณัฐพงศ์ ตะปะชุม (Nattapong Tapachoom)** 
ห้ามมิให้มีการเผยแพร่ ดัดแปลง ทำซ้ำ หรือแจกจ่ายส่วนใดส่วนหนึ่งของซอฟต์แวร์นี้ โดยไม่ได้รับอนุญาตเป็นลายลักษณ์อักษรจากเจ้าของลิขสิทธิ์โดยตรง

#### 1. การจำกัดความรับผิดชอบ (No Liability Claim)
ผู้พัฒนา **"จะไม่รับผิดชอบใดๆ ทั้งสิ้น"** ต่อเหตุการณ์ ความเสียหาย หรือผลกระทบทางกฎหมายที่เกิดขึ้นจากการนำซอฟต์แวร์นี้ไปใช้งานในทุกรูปแบบ ผู้ใช้เป็นผู้แบกรับความเสี่ยงและผลทางกฎหมายแต่เพียงผู้เดียว

#### 2. การดำเนินคดีทางกฎหมาย (Prosecution Warning)
หากพบเห็นการนำรหัสต้นฉบับ (Source Code) หรือไฟล์โปรแกรมไปดัดแปลงเพื่อจำหน่าย แจกจ่ายฟรี หรือนำไปใช้ในทางที่สร้างความเสื่อมเสีย **ผู้พัฒนาจะดำเนินคดีตามกฎหมายสูงสุดให้ถึงที่สุด (Maximum Prosecution)** ทั้งทางแพ่งและทางอาญา โดยไม่มีการเจรจาหรือยอมความใดๆ ทั้งสิ้น

---

A powerful, multi-vector DDoS (Distributed Denial of Service) tool and network security suite written in Python. This tool features a modern CLI interface, real-time monitoring, and a wide array of attack vectors for security research and educational purposes.

## 🚀 Quick Start Guide

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/JonusNattapong/IP-HUNTER.git
   cd IP-HUNTER
   ```

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the tool**:
   ```bash
   python main.py
   ```

### Basic Usage

1. **Select an attack** from the menu by entering the corresponding ID (e.g., `1` for HTTP Flood).
2. **Enter target details**:
   - Target: IP address or URL (e.g., `http://example.com` or `192.168.1.1`)
   - Port: Default ports are used if not specified
   - Threads: Number of concurrent threads (default: 100, max: 1000)
   - Duration: Attack duration in seconds (default: 60, max: 3600)
3. **Configure options** (optional):
   - Proxies: Provide a file path to a list of proxies
   - Stealth Mode: Enable randomized headers and delays
   - Tor Integration: Route traffic through Tor for anonymity
4. **Monitor progress**: Real-time statistics are displayed during execution.

### Configuration

- **Proxy File**: Create a `proxies.txt` file with one proxy per line (format: `ip:port` or `user:pass@ip:port`).
- **Environment Variables**: Set `TOR_ENABLED=1` to force Tor usage.
- **Advanced Settings**: Edit `src/config.py` for default values like thread limits and timeouts.

### Examples

- **HTTP Flood**: Select ID `1`, target `http://target.com`, threads `50`, duration `30`.
- **Port Scan**: Select ID `17`, target `192.168.1.1`, ports `1-65535`.
- **Vulnerability Scan**: Select ID `23`, target `http://target.com`.

**Note**: Always test in controlled environments. Unauthorized use is illegal.

## ⚠️ Disclaimer

**This tool is for educational purposes only!** Using this software to attack or disrupt any network or service without explicit permission is illegal and unethical. The author is not responsible for any misuse or damage caused by this tool. Always ensure you have proper authorization before testing any network security measures.

## ✨ Key Features

- **🤖 AI-Powered Offensive Intelligence**: Integrated AI assistant using fine-tuned models on red team datasets for attack strategy generation.
- **🧠 Smart Threat Intelligence**: AI-enhanced threat reports with context-aware attack recommendations and risk analysis.
- **🎯 Adaptive Attack Strategies**: AI analyzes target information and suggests optimal attack vectors based on service type and vulnerabilities.
- **📊 AI Training Pipeline**: Complete training infrastructure using Hugging Face datasets (WNT3D/Ultimate-Offensive-Red-Team).
- **🔄 Fallback AI Mode**: Works offline with pre-defined offensive techniques when full AI models aren't available.
- **Modern CLI Interface**: Beautiful Terminal UI using the `rich` library with panels, tables, and live progress.
- **Real-time Monitoring**: Live statistics including Packets/Bytes sent, success rate, and active threads.
- **System Resource Watchdog**: Integrated monitoring of CPU and Memory usage with safety warnings.
- **Identity Protection**: Built-in Tor integration for anonymous HTTP attacks.
- **Advanced Stealth Mode**: Randomized headers, timing delays, and anti-forensic cleanup for maximum traceless operation.
- **Layer 7 HTTP Floods**: Multiple methods including Basic, Asynchronous (aiohttp), and Cloudflare bypass.
- **Layer 4 Protocol Floods**: SYN and UDP flooding with IP spoofing capabilities.
- **Amplification Benchmarking**: Test NTP, Memcached, SSDP, and DNS amplification vectors.
- **Application Exploits**: HTTP/2 Rapid Reset, Apache/Nginx Range Header DoS.
- **Advanced Tools**: Built-in Botnet C2 Server and a multi-threaded Port Scanner with service identification.
- **Extensive Service Mapping**: Identifies over 50+ common services during port scanning (Web, DB, Games, etc.).

## 🚀 Attack Vectors

### Application Layer (Layer 7)
1. **HTTP Flood (Basic)**: Standard GET/POST flooding for web services.
2. **Async HTTP Flood**: High-performance async requests with proxy support.
5. **Slowloris Attack**: Low-bandwidth connection exhaustion using partial headers.
8. **Cloudflare Bypass**: Specialized logic to circumvent WAF and CDN protection.
12. **RUDY (R U Dead Yet?)**: Slow POST data submission to tie up threads.
13. **HOIC Mode**: High Orbit Ion Cannon style multi-vector headers/methods.
14. **HTTP/2 Rapid Reset**: Exploits stream cancellation in HTTP/2 (CVE-2023-44487).
15. **Apache Killer**: Range header exhaustion targeting Apache servers.
16. **Nginx Range DoS**: Overlapping range exploitation for Nginx.
22. **AI-Adaptive Flood**: Smart flood that adjusts intensity based on server latency with AI-enhanced targeting.
33. **Mixed Vector Flood**: Randomized combination of L7 techniques in a single attack.
34. **Slow Post Attack**: Advanced variant of RUDY with randomized drip-feeding.

### Network Layer (Layer 4)
3. **SYN Flood**: TCP protocol-level flooding with IP spoofing (requires root).
4. **UDP Flood**: High-velocity UDP packet bombardment (requires root).
19. **Hybrid ICMP Attack**: Combined ICMP Flood and Ping of Death exploit.
35. **QUIC Flood**: Targets the modern HTTP/3 (QUIC) protocol.

### Amplification & Reflection
6. **NTP Amplification**: Protocol-specific reflection (requires root).
9. **Memcached Amplification**: Massive UDP amplification factor (~50,000x).
10. **SSDP Amplification**: UPnP discovery protocol reflection (requires root).
11. **DNS Amplification**: Exploiting open resolvers for traffic multiplication.

### Infrastructure & Botnet
7. **Botnet C2 Server**: Command and Control system for managing remote bots.
18. **Local Bot Client**: Connects local machine to a C2 for distributed operation.
00. **Interactive C2 Shell**: Management console for connected botnet nodes.

### OSINT & Reconnaissance
0. **Target Library**: Save and manage targets for quick-access (ID 0).
17. **Advanced Port Scanner**: Multi-threaded auditor with service identification.
20. **Network Discovery**: Comprehensive subnet scanner for active hosts.
21. **IP Intel Tracker**: Deep geolocation and ASN intelligence gathering.
25. **Domain OSINT**: Automated subdomain and DNS record harvester.
31. **CVE Explorer**: Real-time vulnerability search via NVD/NIST databases.
32. **Web Exposure Sniper**: Deep scan for leaked configs and exposed directories.

### Cyber-Sec Toolkit
 23. **Vulnerability Scout**: Quick scans for misconfigured headers (XSS, CORS, CSP) and common sensitive paths.
 24. **Brute Force Suite**: Multi-protocol credential auditor for FTP, SSH, and HTTP Basic Auth.
 26. **Proxy Auto-Pilot**: Automated scraper that gathers, validates, and benchmarks public proxies for latency.
 27. **WiFi Ghost Recon**: Nearby wireless signal monitoring and BSSID tracking (Windows netsh optimized).
 28. **Live Packet Insight**: Real-time traffic sniffer using Scapy to analyze protocol distribution (TCP/UDP/ICMP).
 29. **Payload Laboratory**: Interactive reverse shell generator for Python, Bash, Netcat, and PowerShell.
 30. **Identity Cloak**: Operational Security auditor that checks for IP leaks, VPN status, and MAC address exposure.

## 🤖 AI Integration & Offensive Intelligence

IP-HUNTER v2.1.0-ai introduces cutting-edge AI capabilities for intelligent offensive security operations:

### AI-Powered Attack Strategy Generation
- **Context-Aware Analysis**: AI analyzes target information (ports, services, vulnerabilities) to suggest optimal attack vectors
- **Target-Specific Strategies**:
  - **Web Servers**: SQL Injection, XSS, Directory Traversal, CSRF analysis
  - **Databases**: Blind SQL Injection, Union-based attacks, Data exfiltration techniques
  - **Networks**: Port scanning, MITM attacks, ARP poisoning, Wireless exploitation
  - **Unknown Targets**: Reconnaissance and vulnerability assessment approaches

### Smart Threat Intelligence Reports
- **AI-Enhanced Reports**: Threat intelligence reports now include AI-generated attack strategies alongside defensive recommendations
- **Risk-Based Analysis**: AI evaluates target risk scores and suggests appropriate offensive techniques
- **Professional Output**: Combined defensive and offensive intelligence in unified reports

### Training Infrastructure
- **Hugging Face Integration**: Uses `WNT3D/Ultimate-Offensive-Red-Team` dataset for model training
- **Fine-Tuning Pipeline**: Complete training scripts for custom model development
- **Fallback Mode**: Pre-defined offensive techniques when full AI models aren't available

### AI Features in Action
```bash
# AI automatically activates during threat intelligence gathering
# Example: Scanning a web server triggers AI analysis

Target Analysis: Apache server on ports 80,443 with MySQL backend
AI Strategy Suggestions:
1. SQL Injection testing on login forms and search parameters
2. XSS vulnerability scanning on user input fields
3. Directory traversal attacks on file upload endpoints
4. CSRF token analysis and bypass attempts
5. API endpoint enumeration and parameter tampering
```

### Training Your Own AI Model
```bash
# Train custom AI model (requires GPU recommended)
python train_ai_model.py

# Test AI integration
python test_ai_integration.py
```

### AI Integration Benefits
- **Intelligent Targeting**: No more guesswork - AI suggests the most effective attack vectors
- **Educational Value**: Learn offensive techniques through AI-guided analysis
- **Research Enhancement**: Accelerate red teaming research with AI assistance
- **Operational Efficiency**: Reduce time spent on manual attack strategy development

## 🛰️ Technical Deep-Dive

### Smart Target Library (ID 0)
The Target Library provides **persistence** for your operations. Any host discovered via the [Network Scanner](src/attacks/scanning.py) or entered manually can be "Locked" into the library. 
- Auto-saves to `txt/locked_targets.txt`
- Quick-select IDs to avoid re-typing long URLs or IPs.
- Seamlessly integrates with all 35 attack vectors.

### Adaptive IA Flooding (ID 22)
Unlike standard flooders, the **Adaptive Flood** monitors the target's response latency. 
- If the server responds quickly, it **ramps up** thread intensity.
- If it detects a `429 Too Many Requests` or `503 Service Unavailable`, it **backs off** to preserve proxy health.
- Automatically rotates User-Agents when a WAF block (403) is detected.

### Hybrid ICMP & QUIC (IDs 19, 35)
- **ID 19**: Combines a high-velocity ICMP Echo Flood with the **Ping of Death** (oversized packet fragments) to overwhelm network stacks and firewalls simultaneously.
- **ID 35**: Specifically targets the **QUIC (HTTP/3)** protocol over UDP 443, bypassing many traditional TCP-based WAF rules.

### Botnet C2 Infrastructure (IDs 7, 18, 00)
IP-HUNTER features a built-in **Command & Control** system:
1. **Server (ID 7)**: Listen for incoming bot connections on a custom port.
2. **Client (ID 18)**: Deploy a lightweight bot that connects back to your C2 center.
3. **Interactive Shell (ID 00)**: A real-time terminal to broadcast flood commands to your entire botnet with a single "attack" command.

## 🧪 Testing State (Current)
- **Status**: ✅ All 35 attack vectors verified + AI integration complete
- **AI Integration**: ✅ Offensive strategy generation and threat intelligence enhancement
- **Target**: `http://203.154.83.24/` (Functional verification completed)
- **UI Architecture**: Enhanced Cyberpunk HUD with AI-enhanced monitoring and professional reporting
- **AI Training**: ✅ Pipeline ready with WNT3D/Ultimate-Offensive-Red-Team dataset

## 🛠️ Requirements

- **Python 3.8+**
- **Root/Administrator Privileges** (Required for Layer 4 & Amplification attacks)
- **Tor** (Optional, for identity protection in HTTP attacks)
- **Configuration**: Create a `.env` file based on `.env example`
  - `MASTER_ADMIN_KEY`: Random 32-character hex key required for C2 access.
  - `OPEN_ROUTER`: API key for AI-Adaptive logic.
- **Dependencies**:
  ```bash
  pip install -r requirements.txt
  ```
  *(Core: requests, aiohttp, scapy, psutil, rich, PySocks)*
  *(AI/ML: torch, transformers, datasets, accelerate)*

## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/JonusNattapong/IP-HUNTER.git
cd IP-HUNTER

# Setup environment
cp ".env example" .env
# Edit .env with your keys

# Install required packages
pip install -r requirements.txt

# Optional: Train AI model for enhanced intelligence (requires GPU recommended)
python train_ai_model.py

# Test AI integration
python test_ai_integration.py

# Optional: Install Tor for identity protection
# Download from: https://www.torproject.org/download/
# Run Tor Browser or tor service on default port 9050
```

## 🎮 Usage

You can launch the tool using the following methods:

**Windows:**
```powershell
.\run.bat
```

**Linux/Mac:**
```bash
python3 main.py
```

## 🔒 Identity Protection & Stealth Features

IP-HUNTER includes comprehensive identity protection and advanced stealth features to help maintain anonymity and avoid detection during security testing:

### Tor Integration (Auto-Start)
- **Automatic Tor Detection**: Tool automatically detects if Tor is running
- **Auto-Start Tor**: Automatically starts Tor service if not running (when enabled)
- **SOCKS5 Proxy Support**: Uses `socks5://127.0.0.1:9050` by default
- **CLI Integration**: Simple yes/no prompt during attack configuration

### VPN Integration
- **VPN Detection**: Automatically detects active VPN connections
- **IP Verification**: Shows current public IP when VPN is active
- **Supported Providers**: NordVPN, ExpressVPN, ProtonVPN, and other common VPNs
- **Layered Protection**: Use VPN + Tor for maximum anonymity

### Advanced Stealth Mode
- **Randomized Headers**: Generates unique, realistic browser fingerprints for each request
- **Timing Randomization**: Variable delays between requests to mimic human behavior
- **Anti-Forensic Cleanup**: Automatically removes temporary files and traces
- **Proxy Chain Support**: Multiple proxy layers for enhanced anonymity

### Proxy Chain Rotation
- **Chain Creation**: Automatically creates randomized proxy chains
- **Validation**: Tests proxy validity before use
- **Failover**: Continues with working proxies if some fail
- **Load Distribution**: Distributes traffic across multiple proxies
- **Noise Traffic Generation**: Optional background traffic to mask attack patterns

### Usage with Tor:
1. **Download Tor Browser** from https://www.torproject.org/download/
2. **Run IP-HUNTER** and select Layer 7 attack
3. **Select "y"** when asked "Use Tor for anonymity?"
4. **Select "y"** when asked "Enable stealth mode (advanced anti-trace)?"
5. **Tool automatically starts Tor** if not running
6. **All HTTP requests are anonymized** through Tor network with stealth features

### Usage with VPN:
1. **Connect to VPN** using your preferred provider (NordVPN, ExpressVPN, etc.)
2. **Run IP-HUNTER** and select Layer 7 attack
3. **Select "y"** when asked "Use VPN for additional protection?"
4. **Tool will verify VPN connection** and show your VPN IP
5. **Combine with Tor** for maximum protection: VPN → Tor → Target

### Usage with Proxy Chains:
1. **Prepare proxy list** in `proxy.txt` file (one proxy per line)
2. **Run IP-HUNTER** and select Layer 7 attack
3. **Load proxies** when prompted
4. **Select "y"** when asked "Enable proxy chain rotation?"
5. **Tool validates proxies** and creates randomized chains
6. **Traffic rotates** through different proxy combinations

### Maximum Anonymity Setup:
```
User → VPN (NordVPN) → Tor Network → Proxy Chain (3-5 proxies) → Target Website
```
1. Connect to VPN first
2. Run IP-HUNTER with Layer 7 attack
3. Enable all protection layers: Tor + Stealth Mode + VPN + Proxy Chains
4. Tool provides 5+ layers of anonymity protection

### Manual Tor Setup (Alternative):
- Install Tor Browser or standalone Tor
- Ensure Tor listens on port 9050
- Tool will detect and use existing Tor instance

## ⚠️ Important Security Notice

**NO ANONYMITY METHOD IS 100% FOOLPROOF!** While IP-HUNTER provides strong identity protection features, absolute anonymity cannot be guaranteed. Here are the limitations and additional security measures:

### Tor Limitations:
- **Entry/Exit Node Logs**: Tor entry nodes can see your real IP, exit nodes can see destination
- **Timing Attacks**: Correlation of timing patterns can deanonymize users
- **Malicious Nodes**: Compromised Tor nodes can monitor traffic
- **Browser Fingerprinting**: Websites can fingerprint your browser even through Tor
- **DNS Leaks**: DNS requests may bypass Tor if not configured properly

### What IP-HUNTER Protects Against:
✅ **Direct IP Exposure**: Your real IP is hidden from targets
✅ **Basic Network Monitoring**: ISP-level traffic analysis is harder
✅ **Simple Tracing**: Direct IP-to-identity correlation is prevented
✅ **Header Analysis**: Randomized headers prevent basic fingerprinting

### What IP-HUNTER Does NOT Protect Against:
❌ **Advanced Forensics**: Law enforcement with court orders can subpoena Tor records
❌ **Timing Correlation**: Sophisticated analysis of traffic patterns
❌ **Physical Security**: Keyloggers, cameras, or compromised devices
❌ **Social Engineering**: Human error or coercion
❌ **Legal Consequences**: Using this tool illegally will still result in prosecution

### Additional Security Recommendations:

#### 1. **Use in Combination** (Defense in Depth):
```bash
# Use Tor + VPN together for better protection
VPN → Tor → Target
```
- Connect to VPN first, then use Tor through VPN
- Or use Tor over VPN for different protection layers

#### 2. **System Hardening**:
- Use Tails OS (amnesic live system)
- Disable JavaScript in Tor Browser
- Use NoScript extension
- Avoid logging into personal accounts
- Use encrypted DNS (DNSCrypt or DNS over HTTPS)

#### 3. **Operational Security (OPSEC)**:
- Never use real personal information
- Avoid patterns that can be correlated
- Use different Tor circuits for different targets
- Don't mix anonymous and non-anonymous activities
- Use bridges if Tor is blocked in your region

#### 4. **Legal Awareness**:
- **This tool is for EDUCATIONAL PURPOSES ONLY**
- Unauthorized network attacks are illegal worldwide
- Even with anonymity tools, intent and actions can be prosecuted
- Always obtain explicit written permission before testing

### Best Practice Workflow:
1. **Research Target**: Ensure you have legal authorization
2. **Setup Anonymity**: VPN → Tor → IP-HUNTER
3. **Test Safely**: Use controlled environments
4. **Clean Up**: Clear logs, restart systems
5. **Document Everything**: Keep records of authorization

**Remember: The best anonymity comes from not needing it in the first place. Always act ethically and legally.**
## 📜 License & Copyright (ลิขสิทธิ์และข้อตกลงการใช้งาน)

**Copyright © 2026 Nattapong Tapachoom. All Rights Reserved.**

ซอฟต์แวร์นี้เป็นลิขสิทธิ์ของ **ณัฐพงศ์ ตะปะชุม** ห้ามมิให้ผู้ใดทำการคัดลอก ทำซ้ำ ดัดแปลง แก้ไข เผยแพร่ หรือแจกจ่ายส่วนหนึ่งส่วนใดหรือทั้งหมดของซอฟต์แวร์นี้โดยไม่ได้รับอนุญาตเป็นลายลักษณ์อักษรโดยเด็ดขาด

**เงื่อนไขและข้อตกลงสำคัญ (Full Proprietary Disclosure):**

1.  **Strict Non-Redistribution**: ห้ามแจกจ่ายไฟล์ต้นฉบับหรือไฟล์ที่ผ่านการคอมไพล์แล้วไปยังแพลตฟอร์มสาธารณะใดๆ หากตรวจพบข้อมูลรั่วไหลจากผู้ใช้คนใด จะมีการระงับสิทธิ์และดำเนินคดีทันที
2.  **No Liability Claim**: ผู้พัฒนาจะไม่รับผิดชอบต่อความเสียหาย การถูกระงับบัญชี หรือการถูกดำเนินคดีทางกฎหมายใดๆ ที่เกิดขึ้นจากการนำเครื่องมือนี้ไปใช้ในทางที่ผิดกฎหมาย (ผู้ใช้ต้องแบกรับความเสี่ยงเอง 100%)
3.  **Built-in Auditing**: ซอฟต์แวร์มีการใช้ระบบตรวจสอบการเข้าถึง (Telemetry) เพื่อบันทึกข้อมูลการรันโปรแกรมพื้นฐาน เพื่อป้องกันการนำโค้ดไปดัดแปลงหรือขายต่อโดยมิชอบ
4.  **Copyright Protection**: รหัสต้นฉบับ ลอจิกการโจมตี และโครงสร้างโปรแกรมทั้งหมดได้รับการคุ้มครองภายใต้ **พ.ร.บ. ลิขสิทธิ์ และ พ.ร.บ. คอมพิวเตอร์**
5.  **Maximum Prosecution**: หากมีการตรวจพบว่ามีการนำไป ดัดแปลง แจกจ่าย หรือใช้งานโดยมิได้รับอนุญาต เจ้าของลิขสิทธิ์จะ**ดำเนินคดีตามกฎหมายสูงสุดทั้งทางแพ่งและทางอาญาให้ถึงที่สุด** โดยยึดตามเขตอำนาจศาลในประเทศไทย

---

**IP-HUNTER - Advanced Defense & Recon Toolkit**

<!-- markdownlint-disable search-replace -->

Thank you for using GitHub! We're happy you're here. Please read this Terms of Service agreement carefully before accessing or using GitHub. Because it is such an important contract between us and our users, we have tried to make it as clear as possible. For your convenience, we have presented these terms in a short non-binding summary followed by the full legal terms.

## Summary

| Section                                                                          | What can you find there?                                                                                                                                                                                                                   |
| -------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [A. Definitions](#a-definitions)                                                 | Some basic terms, defined in a way that will help you understand this agreement. Refer back up to this section for clarification.                                                                                                          |
| [B. Account Terms](#b-account-terms)                                             | These are the basic requirements of having an Account on GitHub.                                                                                                                                                                           |
| [C. Acceptable Use](#c-acceptable-use)                                           | These are the basic rules you must follow when using your GitHub Account.                                                                                                                                                                  |
| [D. User-Generated Content](#d-user-generated-content)                           | You own the content you post on GitHub. However, you have some responsibilities regarding it, and we ask you to grant us some rights so we can provide services to you.                                                                    |
| [E. Private Repositories](#e-private-repositories)                               | This section talks about how GitHub will treat content you post in private repositories.                                                                                                                                                   |
| [F. Copyright & DMCA Policy](#f-copyright-infringement-and-dmca-policy)          | This section talks about how GitHub will respond if you believe someone is infringing your copyrights on GitHub.                                                                                                                           |
| [G. Intellectual Property Notice](#g-intellectual-property-notice)               | This describes GitHub's rights in the website and service.                                                                                                                                                                                 |
| [H. API Terms](#h-api-terms)                                                     | These are the rules for using GitHub's APIs, whether you are using the API for development or data collection.                                                                                                                             |
| [I. Additional Product Terms](#i-github-additional-product-terms)                | We have a few specific rules for GitHub's features and products.                                                                                                                                                                           |
| [J. AI Features, Training, and Your Data](#j-ai-features-training-and-your-data) | These are the terms that apply to GitHub Copilot and other AI features, including how your data may be used for development and improvement of the artificial intelligence and machine learning models, and the controls available to you. |
| [K. Beta Previews](#k-beta-previews)                                             | These are some of the additional terms that apply to GitHub's features that are still in development.                                                                                                                                      |
| [L. Payment](#l-payment)                                                         | You are responsible for payment. We are responsible for billing you accurately.                                                                                                                                                            |
| [M. Cancellation and Termination](#m-cancellation-and-termination)               | You may cancel this agreement and close your Account at any time.                                                                                                                                                                          |
| [N. Communications with GitHub](#n-communications-with-github)                   | We only use email and other electronic means to stay in touch with our users. We do not provide phone support.                                                                                                                             |
| [O. Disclaimer of Warranties](#o-disclaimer-of-warranties)                       | We provide our service as is, and we make no promises or guarantees about this service. **Please read this section carefully; you should understand what to expect.**                                                                      |
| [P. Limitation of Liability](#p-limitation-of-liability)                         | We will not be liable for damages or losses arising from your use or inability to use the service or otherwise arising under this agreement. **Please read this section carefully; it limits our obligations to you.**                     |
| [Q. Release and Indemnification](#q-release-and-indemnification)                 | You are fully responsible for your use of the service.                                                                                                                                                                                     |
| [R. Changes to these Terms of Service](#r-changes-to-these-terms)                | We may modify this agreement, but we will give you 30 days' notice of material changes.                                                                                                                                                    |
| [S. Miscellaneous](#s-miscellaneous)                                             | Please see this section for legal details including our choice of law.                                                                                                                                                                     |

## The GitHub Terms of Service

Effective date: April 27, 2026

## A. Definitions

**Short version:** *We use these basic terms throughout the agreement, and they have specific meanings. You should know what we mean when we use each of the terms. There's not going to be a test on it, but it's still useful information.*

1. An "Account" represents your legal relationship with GitHub. A “Personal Account” represents an individual User’s authorization to log in to and use the Service and serves as a User’s identity on GitHub. “Organizations” are shared workspaces that may be associated with a single entity or with one or more Users where multiple Users can collaborate across many projects at once. A Personal Account can be a member of any number of Organizations.

2. The “Agreement” refers, collectively, to all the terms, conditions, notices contained or referenced in this document (the “Terms of Service” or the "Terms") and all other operating rules, policies (including the GitHub Privacy Statement, available at [github.com/site/privacy](https://github.com/site/privacy)) and procedures that we may publish from time to time on the Website. Most of our site policies are available at [docs.github.com/categories/site-policy](/en/site-policy).

3. "AI Feature" means any feature of GitHub or our Affiliates that uses machine learning or artificial intelligence to generate Output, including GitHub Copilot, Copilot Autofix, and any other feature identified as using machine learning or artificial intelligence in our documentation.

4. “Affiliate” means any entity that directly or indirectly controls, is controlled by, or is under common control with a party, where "control" means having more than fifty percent (50%) ownership or the right to direct the management of the entity. For the avoidance of doubt, Microsoft is an Affiliate of GitHub.

5. "Beta Previews" mean software, services, or features identified as alpha, beta, preview, early access, or evaluation, or words or phrases with similar meanings.

6. "Content" means code, text, data, documentation, images, graphics, software, packages, and other materials made available through the Service.

7. “GitHub,” “We,” and “Us” refer to GitHub, Inc., as well as our directors, subsidiaries, contractors, licensors, officers, agents, and employees.

8. “Input” means any content or context provided to an AI Feature, including prompts, attachments, code in your workspace, and conversation history.

9. "Output" means responses and suggestions, including code or other material, generated by an AI Feature.

10. The “Service” refers to the applications, software, products, and services provided by GitHub, including through the Website and any Beta Previews.

11. “User,” “You,” and “Your” refer to the individual person, company, or organization that has visited or is using the Website or Service; that accesses or uses any part of the Account; or that directs the use of the Account in the performance of its functions. A User must be at least 13 years of age. Special terms may apply for business or government Accounts (See [Section B(5): Additional Terms](#5-additional-terms)).

12. "User-Generated Content" means Content that you or other users upload, submit, or create through the Service.

13. The “Website” refers to GitHub’s website located at [github.com](https://github.com/), and all content, services, and products provided by GitHub at or through the Website. It also refers to GitHub-owned subdomains of github.com, such as [education.github.com](https://education.github.com/) and [pages.github.com](https://pages.github.com/). These Terms also govern GitHub’s conference websites, such as [githubuniverse.com](https://githubuniverse.com/), and product websites, such as [electronjs.org](https://www.electronjs.org/). Occasionally, websites owned by GitHub may provide different or additional terms of service. If those additional terms conflict with this Agreement, the more specific terms apply to the relevant page or service.

14. "Your Content" means User-Generated Content that you upload, submit, or create, including your modifications to Content you have forked or cloned. It does not include the underlying Content created by others.

## B. Account Terms

**Short version:** *Personal Accounts and Organizations have different administrative controls; a human must create your Account; you must be 13 or over; you must provide a valid email address; and you may not have more than one free Account. You alone are responsible for your Account and anything that happens while you are signed in to or using your Account. You are responsible for keeping your Account secure.*

### 1. Account Controls

* Users. Subject to these Terms, you retain ultimate administrative control over your Personal Account and the Content within it.

* Organizations. The "owner" of an Organization that was created under these Terms has ultimate administrative control over that Organization and the Content within it. Within the Service, an owner can manage User access to the Organization’s data and projects. An Organization may have multiple owners, but there must be at least one Personal Account designated as an owner of an Organization. If you are the owner of an Organization under these Terms, we consider you responsible for the actions that are performed on or through that Organization.

### 2. Required Information

You must provide a valid email address in order to complete the signup process. Any other information requested, such as your real name, is optional, unless you are accepting these terms on behalf of a legal entity (in which case we need more information about the legal entity) or if you opt for a [paid Account](#l-payment), in which case additional information will be necessary for billing purposes.

### 3. Account Requirements

We have a few simple rules for Accounts on GitHub's Service.

* You must be a human to create an Account. Accounts registered by "bots" or other automated methods are not permitted. We do permit machine accounts:
* A machine account is an Account set up by an individual human who accepts the Terms on behalf of the Account, provides a valid email address, and is responsible for its actions. A machine account is used exclusively for performing automated tasks. Multiple users may direct the actions of a machine account, but the owner of the Account is ultimately responsible for the machine's actions. You may maintain no more than one free machine account in addition to your free Personal Account.
* One person or legal entity may maintain no more than one free Account (if you choose to control a machine account as well, that's fine, but it can only be used for running a machine).
* You must be age 13 or older. While we are thrilled to see brilliant young coders get excited by learning to program, we must comply with United States law. GitHub does not target our Service to children under 13, and we do not permit any Users under 13 on our Service. If we learn of any User under the age of 13, we will [terminate that User’s Account immediately](#m-cancellation-and-termination). If you are a resident of a country outside the United States, your country’s minimum age may be older; in such a case, you are responsible for complying with your country’s laws.
* Your login may only be used by one person — i.e., a single login may not be shared by multiple people. A paid Organization may only provide access to as many Personal Accounts as your subscription allows.
* You may not use GitHub in violation of export control or sanctions laws of the United States or any other applicable jurisdiction. You may not use GitHub if you are or are working on behalf of a [Specially Designated National (SDN)](https://www.treasury.gov/resource-center/sanctions/SDN-List/Pages/default.aspx) or a person subject to similar blocking or denied party prohibitions administered by a U.S. government agency. GitHub may allow persons in certain sanctioned countries or territories to access certain GitHub services pursuant to U.S. government authorizations. For more information, please see our [Export Controls policy](/en/site-policy/other-site-policies/github-and-trade-controls).

### 4. Account Security

You are responsible for keeping your Account secure while you use our Service. We offer tools such as two-factor authentication to help you maintain your Account's security, but the content of your Account and its security are up to you.

* You are responsible for all content posted and activity that occurs under your Account (even when content is posted by others who have Accounts under your Account).
* You are responsible for maintaining the security of your Account and password. GitHub cannot and will not be liable for any loss or damage from your failure to comply with this security obligation.
* You will promptly notify GitHub by contacting us through the [GitHub Support portal](https://support.github.com/) if you become aware of any unauthorized use of, or access to, our Service through your Account, including any unauthorized use of your password or Account.

### 5. Additional Terms

In some situations, third parties' terms may apply to your use of GitHub. For example, you may be a member of an organization on GitHub with its own terms or license agreements; you may download an application that integrates with GitHub; or you may use GitHub to authenticate to another service. Please be aware that while these Terms are our full agreement with you, other parties' terms govern their relationships with you.

If you are a government User or otherwise accessing or using any GitHub Service in a government capacity, this [Government Amendment to GitHub Terms of Service](/en/site-policy/site-policy-deprecated/amendment-to-github-terms-of-service-applicable-to-us-federal-government-users) applies to you, and you agree to its provisions.

If you have signed up for GitHub Enterprise Cloud, the [Enterprise Cloud Addendum](/en/site-policy/site-policy-deprecated/github-enterprise-service-level-agreement) applies to you, and you agree to its provisions.

## C. Acceptable Use

**Short version:** *GitHub hosts a wide variety of collaborative projects from all over the world, and that collaboration only works when our users are able to work together in good faith. While using the service, you must follow the terms of this section, which include some restrictions on content you can post, conduct on the service, and other limitations. In short, be excellent to each other.*

Your use of the Website and Service must not violate any applicable laws, including copyright or trademark laws, export control or sanctions laws, or other laws in your jurisdiction. You are responsible for making sure that your use of the Service is in compliance with laws and any applicable regulations.

You agree that you will not under any circumstances violate our [Acceptable Use Policies](/en/site-policy/acceptable-use-policies/github-acceptable-use-policies) or [Community Guidelines](/en/site-policy/github-terms/github-community-guidelines).

## D. User-Generated Content

**Short version:** *You own content you create, but you allow us certain rights to it, so that we can display and share the content you post. You still have control over your content, and responsibility for it, and the rights you grant us are limited to those we need to provide the service. We have the right to remove content or close Accounts if we need to.*

### 1. Responsibility for User-Generated Content

You are responsible for Your Content and any harm resulting from it. This includes Content you post, upload, or make available through the Service. We are not responsible for any public display or misuse of Your Content.

### 2. GitHub May Remove Content

We may refuse or remove User-Generated Content that violates applicable law or our terms and policies. We access private repositories only as described in Section E. Content displayed on GitHub Mobile may be subject to app store terms.

### 3. Ownership and License Grants

You own Your Content. If you post Content you did not create, you are responsible for ensuring you have the right to post it and for complying with any applicable licenses.

You grant us and other Users the licenses in Sections D.4–D.8. These licenses apply to Your Content. If Your Content already includes a license granting us the permissions we need, no additional license is required. You will not receive payment for these rights. These licenses end when you remove Your Content, unless other Users have forked it.

### 4. License Grant to Us

You grant GitHub and our Affiliates the right to store, host, archive, parse, display, and make copies of Your Content as necessary to provide, develop, and improve the Service, including by training AI Features, and for the purpose of training, developing, and improving artificial intelligence and machine learning models and technologies of our Affiliates. This license includes the right to do things like copy it to our database and make backups; show it to you and other Users; parse it into a search index or otherwise analyze it on our servers; share it with other Users; and perform it, in case Your Content is something like music or video. For the avoidance of doubt, use of Your Content to develop, train, and improve artificial intelligence and machine learning models and technologies of GitHub and our Affiliates is within the scope of this license and does not constitute a sale or other restricted transfer of Your Content.

### 5. License Grant to Other Users

Your Content that you post publicly, including issues, comments, and contributions to other Users' repositories, may be viewed by others. By setting your repositories to be viewed publicly, you agree to allow others to view and "fork" your repositories (this means that others may make their own copies within the Service in repositories they control).

By making a repository public, you grant other Users a nonexclusive, worldwide license to use, display, perform and reproduce (by forking) Your Content through the Service as permitted by GitHub's functionality. You may grant additional rights by [adopting a license](/en/communities/setting-up-your-project-for-healthy-contributions/adding-a-license-to-a-repository#including-an-open-source-license-in-your-repository). If you post Content you did not create or own, you are responsible for ensuring it is licensed under terms that permit these uses.

### 6. Contributions Under Repository License

Whenever you add Content to a repository containing notice of a license, you license that Content under the same terms, and you agree that you have the right to license that Content under those terms. If you have a separate agreement to license that Content under different terms, such as a contributor license agreement, that agreement will supersede.

Isn't this just how it works already? Yep. This is widely accepted as the norm in the open-source community; it's commonly referred to by the shorthand "inbound=outbound". We're just making it explicit.

### 7. Moral Rights

You retain all moral rights to Your Content that you upload, publish, or submit to any part of the Service, including the rights of integrity and attribution. However, you waive these rights and agree not to assert them against us or our Affiliates, to enable GitHub and our Affiliates to reasonably exercise the rights granted in Section D.4, but not otherwise.

To the extent this agreement is not enforceable by applicable law, you grant GitHub the rights we need to use Your Content without attribution and to make reasonable adaptations of Your Content as necessary to render the Website and provide the Service.

### 8. Public Repositories and Lawful Access

By choosing to contribute Content to a public repository, you are choosing to and directing us to make such Content accessible to everyone on the internet. Unless specifically set forth herein, these Terms do not restrict lawful access to or use of the contents of public repositories by third parties, or by GitHub or its Affiliates.

### 9. Access Reciprocity

By using automated means to access, collect, or otherwise use (“Access”) any publicly accessible Content from the Service for the purpose of developing or training any commercially available artificial intelligence model, machine learning system, or similar technology (a "Commercial AI System"), you hereby waive any and all policies, terms, conditions, or contractual provisions governing products, services, websites or datasets you own or operate that would otherwise prohibit, restrict, or place conditions upon GitHub's Access to any publicly accessible data, information or content associated with your products or services, including for the purpose of developing or training any Commercial AI System. You further agree not to impose technical or other targeted measures to restrict or retaliate against such Access.

This Section D.9 does not apply to Access solely for the purpose of academic research or if, on the date you Access the Content, the number of monthly active users of the products or services made available by you is less than 700 million in the preceding calendar month. For the purposes of this Section, "you" shall refer to you and any entity that directly or indirectly controls, is controlled by, or is under common control with you (affiliates).

## E. Private Repositories

**Short version:** *We treat the content of private repositories as confidential, and we only access it as described in Section E.3 below—for security purposes, to assist the repository owner with a support matter, to maintain the integrity of the Service, to comply with our legal obligations, if we have reason to believe the contents are in violation of the law, or with your consent.*

### 1. Control of Private Repositories

Some Accounts may have private repositories, which allow the User to control access to Content.

### 2. Confidentiality of Private Repositories

GitHub considers the contents of private repositories to be confidential to you. GitHub will protect the contents of private repositories from unauthorized use, access, or disclosure in the same manner that we would use to protect our own confidential information of a similar nature and in no event with less than a reasonable degree of care.

### 3. Access

You control access to the content of your private repositories. GitHub considers the contents of private repositories to be confidential to you, as set forth in Section E.2, and GitHub personnel will not access private repository content without your consent except in the following circumstances:

* for security purposes;
* for automated scanning or manual review for known vulnerabilities, active malware, or other content known to violate our Terms of Service;
* to assist the repository owner with a support matter;
* to maintain the integrity of the Service; or
* to comply with our legal obligations if we have reason to believe the contents are in violation of the law.

You may choose to enable additional access to your private repositories. For example:

* You may enable various GitHub services or features that require additional rights to Your Content in private repositories. These rights may vary depending on the service or feature, but GitHub will continue to treat your private repository Content as confidential. If those services or features require rights in addition to those we need to provide the GitHub Service, we will provide an explanation of those rights.
* If you provide your private repository content as Input to AI Features, we may use that Input to provide, develop, train, and improve the Service, including AI Features. Your ability to opt out under [Section J.3](#3-development-and-improvement-using-your-input-and-output) applies to this use of private repository content. We will not otherwise use your private repository contents to develop or improve the Service.

Additionally, we may be [compelled by law](/en/site-policy/privacy-policies/github-general-privacy-statement#sharing-of-personal-data) to disclose the contents of your private repositories.

GitHub will provide notice regarding our access to private repository content, unless [for legal disclosure](/en/site-policy/privacy-policies/github-general-privacy-statement), to comply with our legal obligations, or where otherwise bound by requirements under law, for automated scanning, or if in response to a security threat or other risk to security.

## F. Copyright Infringement and DMCA Policy

If you believe that content on our website violates your copyright, please contact us in accordance with our [Digital Millennium Copyright Act Policy](/en/site-policy/content-removal-policies/dmca-takedown-policy). If you are a copyright owner and you believe that content on GitHub violates your rights, please contact us via [our convenient DMCA form](https://github.com/contact/dmca) or by emailing <copyright@github.com>. There may be legal consequences for sending a false or frivolous takedown notice. Before sending a takedown request, you must consider legal uses such as fair use and licensed uses.

We will terminate the Accounts of [repeat infringers](/en/site-policy/content-removal-policies/dmca-takedown-policy#f-repeated-infringement) of this policy.

## G. Intellectual Property Notice

**Short version:** *We own the service and all of our content. In order for you to use our content, we give you certain rights to it, but you may only use our content in the way we have allowed.*

### 1. GitHub's Rights to Content

GitHub and our licensors, vendors, agents, and/or our content providers retain ownership of all intellectual property rights of any kind related to the Website and Service. We reserve all rights that are not expressly granted to you under this Agreement or by law. The look and feel of the Website and Service is copyright © GitHub, Inc. All rights reserved. You may not duplicate, copy, or reuse any portion of the HTML/CSS, JavaScript, or visual design elements or concepts without express written permission from GitHub.

### 2. GitHub Trademarks and Logos

If you’d like to use GitHub’s trademarks, you must follow all of our trademark guidelines, including those on our logos page: <https://github.com/logos>.

### 3. License to GitHub Policies

This Agreement is licensed under this [Creative Commons Zero license](https://creativecommons.org/publicdomain/zero/1.0/). For details, see our [site-policy repository](https://github.com/github/site-policy#license).

## H. API Terms

**Short version:** *You agree to these Terms of Service, plus this Section H, when using any of GitHub's APIs (Application Programming Interface), including use of the API through a third party product that accesses GitHub.*

Abuse or excessively frequent requests to GitHub via the API may result in the temporary or permanent suspension of your Account's access to the API. GitHub, in our sole discretion, will determine abuse or excessive usage of the API. We will make a reasonable attempt to warn you via email prior to suspension.

You may not share API tokens to exceed GitHub's rate limitations.

You may not use the API to download data or Content from GitHub for spamming purposes, including for the purposes of selling GitHub users' personal information, such as to recruiters, headhunters, and job boards.

All use of the GitHub API is subject to these Terms of Service and the [GitHub Privacy Statement](https://github.com/site/privacy).

GitHub may offer subscription-based access to our API for those Users who require high-throughput access or access that would result in resale of GitHub's Service.

## I. GitHub Additional Product Terms

**Short version:** *You need to follow certain specific terms and conditions for GitHub's various features and products, and you agree to the Supplemental Terms and Conditions when you agree to this Agreement.*

Some Service features may be subject to additional terms specific to that feature or product as set forth in the GitHub Additional Product Terms. By accessing or using the Services, you also agree to the [GitHub Additional Product Terms](/en/site-policy/github-terms/github-terms-for-additional-products-and-features).

## J. AI Features, Training, and Your Data

### 1. Applicability

This section applies to all AI Features unless a specific feature has additional terms that expressly modify them. The training and data-use provisions in Section J.3 apply only to individual licenses. If your use of the Service is governed by a GitHub Customer Agreement or volume licensing agreement, those agreements govern the use of your data in connection with AI Features and Section J.3 does not apply to you.

### 2. Ownership

GitHub does not claim ownership of your Input or Output.

Output may contain material that resembles code or content in the model's training data or that is subject to third-party copyrights or open source license terms. You are responsible for determining whether your use of Output requires a third-party license and for complying with any such license.

### 3. Development and Improvement Using Your Input and Output

We use your Inputs to generate Outputs and provide the AI Features. You also grant GitHub and its Affiliates a license to collect and use your Inputs and Outputs to develop, train and improve artificial intelligence and machine learning models and technologies including those that power AI Features, unless (a) you opt out through your account settings, or (b) your use of the Service is governed by a GitHub Customer Agreement or volume licensing agreement. If you opt out, GitHub will not collect or use your Inputs and Outputs for the purposes described in this paragraph from the effective date of your opt-out going forward.

Unless you opt out, GitHub's Affiliates may use your Inputs and Outputs under this license in accordance with their applicable privacy and contractual obligations. This license does not, however, permit GitHub or its Affiliates to share your Inputs or Outputs with third-party AI model providers for their own independent model training purposes.

The license in this Section J.3 is in addition to, and does not limit, the rights granted to GitHub and its Affiliates under Sections D.4 and D.8. This license does not extend to Your Content stored in repositories that are not provided as Input to an AI Feature.

The opt-out right described in this section applies solely to the use of your Inputs and Outputs as described in this section, and does not apply to the license granted in Sections D.4-D.8 or to any Content that does not constitute Input or Output (including Content stored in public repositories).

### 4. Disclaimers

Output is provided "as-is" and subject to the disclaimers in Section O. Without limiting Section O: Output may be inaccurate, incomplete, or non-functional. Output may resemble third-party code, including code under open source licenses. We do not guarantee that Output is free of errors, vulnerabilities, or intellectual property claims.

You are responsible for reviewing, testing, and validating any Output before use.

### 5. Your Responsibility and Indemnity

You are responsible for your use of Output, including ensuring it complies with applicable law and does not infringe third-party rights.

Your indemnity obligations in Section Q apply to your use of AI Features and Output, including claims arising from Output you incorporate into your products or services.

## K. Beta Previews

**Short version:** *Beta Previews may not be supported or may change at any time. You may receive confidential information through those programs that must remain confidential while the program is private. We'd love your feedback to make our Beta Previews better.*

### 1. Subject to Change

Beta Previews may not be supported and may be changed at any time without notice. In addition, Beta Previews are not subject to the same security measures and auditing to which the Service has been and is subject. **By using a Beta Preview, you use it at your own risk.**

### 2. Confidentiality

As a user of Beta Previews, you may get access to special information that isn’t available to the rest of the world. Due to the sensitive nature of this information, it’s important for us to make sure that you keep that information secret.

**Confidentiality Obligations.** You agree that any non-public Beta Preview information we give you, such as information about a private Beta Preview, will be considered GitHub’s confidential information (collectively, “Confidential Information”), regardless of whether it is marked or identified as such. You agree to only use such Confidential Information for the express purpose of testing and evaluating the Beta Preview (the “Purpose”), and not for any other purpose. You should use the same degree of care as you would with your own confidential information, but no less than reasonable precautions to prevent any unauthorized use, disclosure, publication, or dissemination of our Confidential Information. You promise not to disclose, publish, or disseminate any Confidential Information to any third party, unless we don’t otherwise prohibit or restrict such disclosure (for example, you might be part of a GitHub-organized group discussion about a private Beta Preview feature).

**Exceptions.** Confidential Information will not include information that is: (a) or becomes publicly available without breach of this Agreement through no act or inaction on your part (such as when a private Beta Preview becomes a public Beta Preview); (b) known to you before we disclose it to you; (c) independently developed by you without breach of any confidentiality obligation to us or any third party; or (d) disclosed with permission from GitHub. You will not violate the terms of this Agreement if you are required to disclose Confidential Information pursuant to operation of law, provided GitHub has been given reasonable advance written notice to object, unless prohibited by law.

### 3. Feedback

We’re always trying to improve our products and services, and your feedback as a Beta Preview user will help us do that. If you choose to give us any ideas, know-how, algorithms, code contributions, suggestions, enhancement requests, recommendations or any other feedback for our products or services (collectively, “Feedback”), you acknowledge and agree that GitHub will have a royalty-free, fully paid-up, worldwide, transferable, sub-licensable, irrevocable and perpetual license to implement, use, modify, commercially exploit and/or incorporate the Feedback into our products, services, and documentation.

## L. Payment

**Short version:** *You are responsible for any fees associated with your use of GitHub. We are responsible for communicating those fees to you clearly and accurately, and letting you know well in advance if those prices change.*

### 1. Pricing

Our pricing and payment terms are available at [github.com/pricing](https://github.com/pricing). If you agree to a subscription price, that will remain your price for the duration of the payment term; however, prices are subject to change at the end of a payment term.

### 2. Upgrades, Downgrades, and Changes

* We will immediately bill you when you upgrade from the free plan to any paying plan.
* If you change from a monthly billing plan to a yearly billing plan, GitHub will bill you for a full year at the next monthly billing date.
* If you upgrade to a higher level of service, we will bill you for the upgraded plan immediately.
* You may change your level of service at any time by [choosing a plan option](https://github.com/pricing) or going into your [Billing settings](https://github.com/settings/billing). If you choose to downgrade your Account, you may lose access to Content, features, or capacity of your Account. Please see our section on [Cancellation](#m-cancellation-and-termination) for information on getting a copy of that Content.

### 3. Billing Schedule; No Refunds

**Payment Based on Plan** For monthly or yearly payment plans, the Service is billed in advance on a monthly or yearly basis respectively and is non-refundable. There will be no refunds or credits for partial months of service, downgrade refunds, or refunds for months unused with an open Account; however, the service will remain active for the length of the paid billing period. In order to treat everyone equally, no exceptions will be made.

**Payment Based on Usage** Some Service features are billed based on your usage. A limited quantity of these Service features may be included in your plan for a limited term without additional charge. If you choose to use paid Service features beyond the quantity included in your plan, you pay for those Service features based on your actual usage in the preceding month. Monthly payment for these purchases will be charged on a periodic basis in arrears. See [GitHub Additional Product Terms for Details](/en/site-policy/github-terms/github-terms-for-additional-products-and-features).

**Invoicing** For invoiced Users, User agrees to pay the fees in full, up front without deduction or setoff of any kind, in U.S. Dollars. User must pay the fees within thirty (30) days of the GitHub invoice date. Amounts payable under this Agreement are non-refundable, except as otherwise provided in this Agreement. If User fails to pay any fees on time, GitHub reserves the right, in addition to taking any other action at law or equity, to (i) charge interest on past due amounts at 1.0% per month or the highest interest rate allowed by law, whichever is less, and to charge all expenses of recovery, and (ii) terminate the applicable order form. User is solely responsible for all taxes, fees, duties and governmental assessments (except for taxes based on GitHub's net income) that are imposed or become due in connection with this Agreement.

### 4. Authorization

By agreeing to these Terms, you are giving us permission to charge your on-file credit card, PayPal account, or other approved methods of payment for fees that you authorize for GitHub.

### 5. Responsibility for Payment

You are responsible for all fees, including taxes, associated with your use of the Service. By using the Service, you agree to pay GitHub any charge incurred in connection with your use of the Service. If you dispute the matter, contact us through the [GitHub Support portal](https://support.github.com/). You are responsible for providing us with a valid means of payment for paid Accounts. Free Accounts are not required to provide payment information.

## M. Cancellation and Termination

**Short version:** *You may close your Account at any time. If you do, we'll treat your information responsibly.*

### 1. Account Cancellation

It is your responsibility to properly cancel your Account with GitHub. You can [cancel your Account at any time](/en/billing/how-tos/manage-plan-and-licenses/downgrade-plan) by going into your Settings in the global navigation bar at the top of the screen. The Account screen provides a simple, no questions asked cancellation link. We are not able to cancel Accounts in response to an email or phone request.

### 2. Upon Cancellation

We will retain and use your information as necessary to comply with our legal obligations, resolve disputes, and enforce our agreements, but barring legal requirements, we will delete your full profile and the Content of your repositories within 90 days of cancellation or termination (though some information may remain in encrypted backups). This information cannot be recovered once your Account is canceled.

We will not delete Content that you have contributed to other Users' repositories or that other Users have forked.

Upon request, we will make a reasonable effort to provide an Account owner with a copy of your lawful, non-infringing Account contents after Account cancellation, termination, or downgrade. You must make this request within 90 days of cancellation, termination, or downgrade.

### 3. GitHub May Terminate

GitHub has the right to suspend or terminate your access to all or any part of the Website at any time, with or without cause, with or without notice, effective immediately. GitHub reserves the right to refuse service to anyone for any reason at any time.

### 4. Survival

All provisions of this Agreement which, by their nature, should survive termination *will* survive termination — including, without limitation: ownership provisions, warranty disclaimers, indemnity, and limitations of liability.

## N. Communications with GitHub

**Short version:** *We use email and other electronic means to stay in touch with our users.*

### 1. Electronic Communication Required

For contractual purposes, you (1) consent to receive communications from us in an electronic form via the email address you have submitted or via the Service; and (2) agree that all Terms of Service, agreements, notices, disclosures, and other communications that we provide to you electronically satisfy any legal requirement that those communications would satisfy if they were on paper. This section does not affect your non-waivable rights.

### 2. Legal Notice to GitHub Must Be in Writing

Communications made through email or GitHub Support's messaging system will not constitute legal notice to GitHub or any of its officers, employees, agents or representatives in any situation where notice to GitHub is required by contract or any law or regulation. Legal notice to GitHub must be in writing and [served on GitHub's legal agent](/en/site-policy/other-site-policies/guidelines-for-legal-requests-of-user-data#submitting-requests).

### 3. No Phone Support

GitHub only offers support via email, in-Service communications, and electronic messages. We do not offer telephone support.

## O. Disclaimer of Warranties

**Short version:** *We provide our service as is, and we make no promises or guarantees about this service. Please read this section carefully; you should understand what to expect.*

GitHub provides the Website and the Service “as is” and “as available,” without warranty of any kind. Without limiting this, we expressly disclaim all warranties, whether express, implied or statutory, regarding the Website and the Service including without limitation any warranty of merchantability, fitness for a particular purpose, title, security, accuracy and non-infringement.

GitHub does not warrant that the Service will meet your requirements; that the Service will be uninterrupted, timely, secure, or error-free; that the information provided through the Service is accurate, reliable or correct; that any defects or errors will be corrected; that the Service will be available at any particular time or location; or that the Service is free of viruses or other harmful components. You assume full responsibility and risk of loss resulting from your downloading and/or use of files, information, content or other material obtained from the Service.

## P. Limitation of Liability

**Short version:** *We will not be liable for damages or losses arising from your use or inability to use the service or otherwise arising under this agreement. Please read this section carefully; it limits our obligations to you.*

You understand and agree that we will not be liable to you or any third party for any loss of profits, use, goodwill, or data, or for any incidental, indirect, special, consequential or exemplary damages, however arising, that result from

<!-- markdownlint-disable GHD034 -->

* the use, disclosure, or display of your User-Generated Content;
* your use or inability to use the Service;
* any modification, price change, suspension or discontinuance of the Service;
* the Service generally or the software or systems that make the Service available;
* unauthorized access to or alterations of your transmissions or data;
* statements or conduct of any third party on the Service;
* any other user interactions that you input or receive through your use of the Service; or
* any other matter relating to the Service.

<!-- markdownlint-enable GHD034 -->

Our liability is limited whether or not we have been informed of the possibility of such damages, and even if a remedy set forth in this Agreement is found to have failed of its essential purpose. We will have no liability for any failure or delay due to matters beyond our reasonable control.

## Q. Release and Indemnification

**Short version:** *You are responsible for your use of the service. If you harm someone else or get into a dispute with someone else, we will not be involved.*

If you have a dispute with one or more Users, you agree to release GitHub from any and all claims, demands and damages (actual and consequential) of every kind and nature, known and unknown, arising out of or in any way connected with such disputes.

You agree to indemnify us, defend us, and hold us harmless from and against any and all claims, liabilities, and expenses, including attorneys’ fees, arising out of your use of the Website and the Service, including but not limited to your violation of this Agreement, provided that GitHub (1) promptly gives you written notice of the claim, demand, suit or proceeding; (2) gives you sole control of the defense and settlement of the claim, demand, suit or proceeding (provided that you may not settle any claim, demand, suit or proceeding unless the settlement unconditionally releases GitHub of all liability); and (3) provides to you all reasonable assistance, at your expense.

## R. Changes to These Terms

**Short version:** *We want our users to be informed of important changes to our terms, but some changes aren't that important — we don't want to bother you every time we fix a typo. So while we may modify this agreement at any time, we will notify users of any material changes and give you time to adjust to them.*

We reserve the right, at our sole discretion, to amend these Terms of Service at any time and will update these Terms of Service in the event of any such amendments. We will notify our Users of material changes to this Agreement, such as price increases, at least 30 days prior to the change taking effect by posting a notice on our Website or sending email to the primary email address specified in your GitHub account. Customer's continued use of the Service after those 30 days constitutes agreement to those revisions of this Agreement. For any other modifications, your continued use of the Website constitutes agreement to our revisions of these Terms of Service. You can view all changes to these Terms in our [Site Policy](https://github.com/github/site-policy) repository.

We reserve the right at any time and from time to time to modify or discontinue, temporarily or permanently, the Website (or any part of it) with or without notice.

## S. Miscellaneous

### 1. Governing Law

Except to the extent applicable law provides otherwise, this Agreement between you and GitHub and any access to or use of the Website or the Service are governed by the federal laws of the United States of America and the laws of the State of California, without regard to conflict of law provisions. You and GitHub agree to submit to the exclusive jurisdiction and venue of the courts located in the City and County of San Francisco, California. However, any claim for injunctive relief with respect to a violation of section D.9 may be brought in any jurisdiction.

### 2. Non-Assignability

GitHub may assign or delegate these Terms of Service and/or the [GitHub Privacy Statement](https://github.com/site/privacy), in whole or in part, to any person or entity at any time with or without your consent, including the license grant in Section D.4. You may not assign or delegate any rights or obligations under the Terms of Service or Privacy Statement without our prior written consent, and any unauthorized assignment and delegation by you is void.

### 3. Section Headings and Summaries

Throughout this Agreement, each section includes titles and brief summaries of the following terms and conditions. These section titles and brief summaries are not legally binding.

### 4. Severability, No Waiver, and Survival

If any part of this Agreement is held invalid or unenforceable, that portion of the Agreement will be construed to reflect the parties’ original intent. The remaining portions will remain in full force and effect. Any failure on the part of GitHub to enforce any provision of this Agreement will not be considered a waiver of our right to enforce such provision. Our rights under this Agreement will survive any termination of this Agreement.

### 5. Amendments; Complete Agreement

This Agreement may only be modified by a written amendment signed by an authorized representative of GitHub, or by the posting by GitHub of a revised version in accordance with [Section R. Changes to These Terms](#r-changes-to-these-terms). These Terms of Service, together with the GitHub Privacy Statement, represent the complete and exclusive statement of the agreement between you and us. This Agreement supersedes any proposal or prior agreement oral or written, and any other communications between you and GitHub relating to the subject matter of these terms including any confidentiality or nondisclosure agreements.

### 6. Questions

Questions about the Terms of Service? Contact us through the [GitHub Support portal](https://support.github.com/).
Are you a law enforcement officer conducting an investigation that may involve user content hosted on GitHub?
Or maybe you're a privacy-conscious person who would like to know what information we share with law enforcement and under what circumstances.
Either way, you're on the right page.

In these guidelines, we provide a little background about what GitHub is, the types of data we have, and the conditions under which we will disclose private user information.
Before we get into the details, however, here are a few important details you may want to know:

* We will [**notify affected users**](#we-will-notify-any-affected-account-owners) about any requests for their account information, unless prohibited from doing so by law or court order.
* We will not disclose **location-tracking data**, such as IP address logs, without a [valid court order or search warrant](#with-a-court-order-or-a-search-warrant).
* We will not disclose any **private user content**, including the contents of private repositories, without a valid [search warrant](#only-with-a-search-warrant).

## About these guidelines

Our users trust us with their software projects and code—often some of their most valuable business or personal assets.
Maintaining that trust is essential to us, which means keeping user data safe, secure, and private.

While the overwhelming majority of our users use GitHub's services to create new businesses, build new technologies, and for the general betterment of humankind, we recognize that with millions of users spread all over the world, there are bound to be a few bad apples in the bunch.
In those cases, we want to help law enforcement serve their legitimate interest in protecting the public.

By providing guidelines for law enforcement personnel, we hope to strike a balance between the often competing interests of user privacy and justice.
We hope these guidelines will help to set expectations on both sides, as well as to add transparency to GitHub's internal processes.
Our users should know that we value their private information and that we do what we can to protect it.
At a minimum, this means only releasing data to third-parties when the appropriate legal requirements have been satisfied.
By the same token, we also hope to educate law enforcement professionals about GitHub's systems so that they can more efficiently tailor their data requests and target just that information needed to conduct their investigation.

## GitHub terminology

Before asking us to disclose data, it may be useful to understand how our system is implemented.
GitHub hosts millions of data repositories using the [Git version control system](https://git-scm.com/video/what-is-version-control).
Repositories on GitHub—which may be public or private—are most commonly used for software development projects, but are also often used to work on content of all kinds.

* [**Users**](/en/get-started/learning-about-github/github-glossary#user):
  Users are represented in our system as personal GitHub accounts.
  Each user has a personal profile, and can own multiple repositories.
  Users can create or be invited to join organizations or to collaborate on another user's repository.

* [**Collaborators**](/en/get-started/learning-about-github/github-glossary#collaborator):
  A collaborator is a user with read and write access to a repository who has been invited to contribute by the repository owner.

* [**Organizations**](/en/get-started/learning-about-github/github-glossary#organization):
  Organizations are a group of two or more users that typically mirror real-world organizations, such as businesses or projects.
  They are administered by users and can contain both repositories and teams of users.

* [**Repositories**](/en/get-started/learning-about-github/github-glossary#repository):
  A repository is one of the most basic GitHub elements.
  They may be easiest to imagine as a project's folder.
  A repository contains all of the project files (including documentation), and stores each file's revision history.
  Repositories can have multiple collaborators and, at its administrators' discretion, may be publicly viewable or not.

* [**Pages**](/en/pages/getting-started-with-github-pages/what-is-github-pages):
  GitHub Pages are public webpages freely hosted by GitHub that users can easily publish through code stored in their repositories.
  If a user or organization has a GitHub Page, it can usually be found at a URL such as `https://username.github.io` or they may have the webpage mapped to their own custom domain name.

* [**Gists**](/en/get-started/writing-on-github/editing-and-sharing-content-with-gists/creating-gists):
  Gists are snippets of source code or other text that users can use to store ideas or share with friends.
  Like regular GitHub repositories, Gists are created with Git, so they are automatically versioned, forkable and downloadable.
  Gists can either be public or secret (accessible only through a known URL). Public Gists cannot be converted into secret Gists.

## User data on GitHub.com

Here is a non-exhaustive list of the kinds of data we maintain about users and projects on GitHub.

* <a name="public-account-data"></a>
  **Public account data:**
  There is a variety of information publicly available on GitHub about users and their repositories.
  User profiles can be found at a URL such as `https://github.com/username`.
  User profiles display information about when the user created their account as well their public activity on GitHub.com and social interactions.
  Public user profiles can also include additional information that a user may have chosen to share publicly.
  All user public profiles display:
  * Username
  * The repositories that the user has starred
  * The other GitHub users the user follows
  * The users that follow them

    Optionally, a user may also choose to share the following information publicly:
  * Their real name
  * An avatar
  * An affiliated company
  * Their location
  * A public email address
  * Their personal web page
  * Organizations to which the user is a member (*depending on either the organizations' or the users' preferences*)

* <a name="private-account-data"></a>
  **Private account data:**
  GitHub also collects and maintains certain private information about users as outlined in our [Privacy Policy](/en/site-policy/privacy-policies/github-general-privacy-statement).
  This may include:
  * Private email addresses
  * Payment details
  * Security access logs
  * Data about interactions with private repositories

    To get a sense of the type of private account information that GitHub collects, you can visit your [personal dashboard](https://github.com/dashboard) and browse through the sections in the left-hand menubar.

* <a name="organization-account-data"></a>
  **Organization account data:**
  Information about organizations, their administrative users and repositories is publicly available on GitHub.
  Organization profiles can be found at a URL such as `https://github.com/organization`.
  Public organization profiles can also include additional information that the owners have chosen to share publicly.
  All organization public profiles display:
  * The organization name
  * The repositories that the owners have starred
  * All GitHub users that are owners of the organization

    Optionally, administrative users may also choose to share the following information publicly:
  * An avatar
  * An affiliated company
  * Their location
  * Direct Members and Teams
  * Collaborators

* <a name="public-repository-data"></a>
  **Public repository data:**
  GitHub is home to millions of public, open-source software projects.
  You can browse almost any public repository (for example, the [GitHub Docs](https://github.com/github/docs)) to get a sense for the information that GitHub collects and maintains about repositories.
  This can include:

  * The code itself
  * Previous versions of the code
  * Stable release versions of the project
  * Information about collaborators, contributors and repository members
  * Logs of Git operations such as commits, branching, pushing, pulling, forking and cloning
  * Conversations related to Git operations such as comments on pull requests or commits
  * Project documentation such as Issues and Wiki pages
  * Statistics and graphs showing contributions to the project and the network of contributors

* <a name="private-repository-data"></a>
  **Private repository data:**
  GitHub collects and maintains the same type of data for private repositories that can be seen for public repositories, except only specifically invited users may access private repository data.

* <a name="other-data"></a>
  **Other data:**
  Additionally, GitHub collects analytics data such as page visits and information occasionally volunteered by our users (such as communications with our support team, survey information and/or site registrations).

## We will notify any affected account owners

It is our policy to notify users about any pending requests regarding their accounts or repositories, unless we are prohibited by law or court order from doing so. Before disclosing user information, we will make a reasonable effort to notify any affected account owner(s) by sending a message to their verified email address providing them with a copy of the subpoena, court order, or warrant so that they can have an opportunity to challenge the legal process if they wish. In (rare) exigent circumstances, we may delay notification if we determine delay is necessary to prevent death or serious harm or due to an ongoing investigation.

## Disclosure of non-public information

It is our policy to disclose non-public user information in connection with a civil or criminal investigation only with user consent or upon receipt of a valid subpoena, civil investigative demand, court order, search warrant, or other similar valid legal process. In certain exigent circumstances (see below), we also may share limited information but only corresponding to the nature of the circumstances, and would require legal process for anything beyond that.
GitHub reserves the right to object to any requests for non-public information.
Where GitHub agrees to produce non-public information in response to a lawful request, we will conduct a reasonable search for the requested information.
Here are the kinds of information we will agree to produce, depending on the kind of legal process we are served with:

* <a name="with-user-consent"></a>
  **With user consent:**
  GitHub will provide private account information, if requested, directly to the user (or an owner, in the case of an organization account), or to a designated third party with the user's written consent once GitHub is satisfied that the user has verified his or her identity.

* <a name="with-a-subpoena"></a>
  **With a subpoena:**
  If served with a valid subpoena, civil investigative demand, or similar legal process issued in connection with an official criminal or civil investigation, we can provide certain non-public account information, which may include:

  * Name(s) associated with the account
  * Email address(es) associated with the account
  * Billing information
  * Registration date and termination date
  * IP address, date, and time at the time of account registration
  * IP address(es) used to access the account at a specified time or event relevant to the investigation

In the case of organization accounts, we can provide the name(s) and email address(es) of the account owner(s) as well as the date and IP address at the time of creation of the organization account. We will not produce information about other members or contributors, if any, to the organization account or any additional information regarding the identified account owner(s) without a follow-up request for those specific users.

Please note that the information available will vary from case to case. Some of the information is optional for users to provide. In other cases, we may not have collected or retained the information.

* <a name="with-a-court-order-or-a-search-warrant"></a>
  **With a court order *or* a search warrant:** We will not disclose account access logs unless compelled to do so by either
  (i) a court order issued under 18 U.S.C. Section 2703(d), upon a showing of specific and articulable facts showing that there are reasonable grounds to believe that the information sought is relevant and material to an ongoing criminal investigation; or
  (ii) a search warrant issued under the procedures described in the Federal Rules of Criminal Procedure or equivalent state warrant procedures, upon a showing of probable cause.
  In addition to the non-public account information listed above, we can provide account access logs in response to a court order or search warrant, which may include:

  * Any logs which would reveal a user's movements over a period of time
  * Account or private repository settings (for example, which users have certain permissions, etc.)
  * User- or IP-specific analytic data such as browsing history
  * Security access logs other than account creation or for a specific time and date

* <a name="only-with-a-search-warrant"></a>
  **Only with a search warrant:**
  We will not disclose the private contents of any account unless compelled to do so under a search warrant issued under the procedures described in the Federal Rules of Criminal Procedure or equivalent state warrant procedures upon a showing of probable cause.
  In addition to the non-public account information and account access logs mentioned above, we will also provide private account contents in response to a search warrant, which may include:

  * Contents of secret Gists
  * Source code or other content in private repositories
  * Contribution and collaboration records for private repositories
  * Communications or documentation (such as Issues or Wikis) in private repositories
  * Any security keys used for authentication or encryption

* <a name="in-exigent-circumstances"></a>
  **Under exigent circumstances:**
  If we receive a request for information under certain exigent circumstances (where we believe the disclosure is necessary to prevent an emergency involving danger of death or serious physical injury to a person), we may disclose limited information that we determine necessary to enable law enforcement to address the emergency. For any information beyond that, we would require a subpoena, search warrant, or court order, as described above. For example, we will not disclose contents of private repositories without a search warrant. Before disclosing information, we confirm that the request came from a law enforcement agency, an authority sent an official notice summarizing the emergency, and how the information requested will assist in addressing the emergency.

## Cost reimbursement

Under state and federal law, GitHub can seek reimbursement for costs associated with compliance with a valid legal demand, such as a subpoena, court order or search warrant. We only charge to recover some costs, and these reimbursements cover only a portion of the costs we actually incur to comply with legal orders.

While we do not charge in emergency situations or in other exigent circumstances, we seek reimbursement for all other legal requests in accordance with the following schedule, unless otherwise required by law:

* Initial search of up to 25 identifiers: Free
* Production of subscriber information/data for up to 5 accounts: Free
* Production of subscriber information/data for more than 5 accounts: $20 per account
* Secondary searches: $10 per search

## Data preservation

We will take steps to preserve account records for up to 90 days upon formal request from U.S. law enforcement in connection with official criminal investigations, and pending the issuance of a court order or other process.

## Submitting requests

Please serve requests to:

```text
GitHub, Inc.
c/o Corporation Service Company
2710 Gateway Oaks Drive, Suite 150N
Sacramento, CA 95833-3505
```

Courtesy copies may be emailed to <legal-support@github.com>

Please make your requests as specific and narrow as possible, including the following information:

* Full information about authority issuing the request for information
* The name and badge/ID of the responsible agent
* An official email address and contact phone number
* The user, organization, repository name(s) of interest
* The URLs of any pages, gists or files of interest
* The description of the types of records you need

Please allow at least two weeks for us to be able to look into your request.

### California Assembly Bill 1242 Notice

By submitting legal process to GitHub, you attest that the legal process does not relate to the violation of any law that creates liability for abortion-related conduct that is lawful in California.

## Requests from foreign law enforcement

As a United States company based in California, GitHub is not required to provide data to foreign governments in response to legal process issued by foreign authorities.
Foreign law enforcement officials wishing to request information from GitHub should contact the United States Department of Justice Criminal Division's Office of International Affairs.
GitHub will promptly respond to requests that are issued via U.S. court by way of a mutual legal assistance treaty (“MLAT”) or letter rogatory.

## Questions

Do you have other questions, comments or suggestions? Please contact us through the [GitHub Support portal](https://support.github.com).
เกี่ยวกับ git-scm.com
ไซต์นี้เป็นโอเพ่นซอร์สและดูแลโดยสมาชิกของ Git ชุมชน เรายินดีรับแพตช์ คําแนะนํา และการแก้ไข
โอเพ่นซอร์ส
เนื้อหาบนเว็บไซต์นี้ถูกดึงมาจากหลายแหล่ง มันเป็น มีจําหน่ายภายใต้ใบอนุญาตต่างๆ และควรมีการกํากับรายงานข้อบกพร่อง ไปยังที่เก็บที่เหมาะสม:
เนื้อหาไซต์ "ฐาน" ส่วนใหญ่โฮสต์อยู่ใน git/git-scm.com พื้นที่เก็บข้อมูลที่ GitHub ที่รวมทุกหน้ายกเว้นหนังสือและ manpages พร้อมด้วยการออกแบบทั่วไปของไซต์ เนื้อหานี้ มีจําหน่ายภายใต้ ใบอนุญาตเอ็มไอที● รายงานข้อบกพร่องและข้อเสนอแนะอาจจัดทําขึ้นในพื้นที่เก็บข้อมูลนั้น
เนื้อหาจากหนังสือ ProGit นําเข้าจาก โปรแกรม/โปรแกรม2 พื้นที่เก็บข้อมูลซึ่งมีอยู่ภายใต้ Creative Commons CC-BY-NC-SA ใบอนุญาต, ตามที่ระบุไว้ในพื้นที่เก็บข้อมูล progit2● รายงานข้อผิดพลาดและ ข้อเสนอแนะเกี่ยวกับเนื้อหาทางเทคนิคหรือเวอร์ชันภาษาอังกฤษของ ควรจัดทําหนังสือเล่มนี้ในพื้นที่เก็บข้อมูล progit2 แก้ไขสําหรับ หนังสือฉบับแปลควรจัดทําไว้ที่ พื้นที่เก็บข้อมูลเฉพาะภาษาที่เหมาะสม●
คู่มืออ้างอิงนําเข้าจากโครงการ Git และเป็น มีจําหน่ายภายใต้ จีพีแอล● ควรจัดทํารายงานข้อบกพร่องและข้อเสนอแนะไปยังต้นน้ํา ชุมชนคอมไพล์●
ข้อบกพร่องในซอฟต์แวร์ Git ควรไปที่ ชุมชนคอมไพล์●
ผู้เขียน
ไซต์นี้เดิมคิดและเขียนโดย สกอตต์ ชาคอน● การออกแบบภาพในปัจจุบันส่วนใหญ่เป็นผลงานของ เจสัน ลอง● ปัจจุบันไซต์นี้ได้รับการดูแลร่วมกันใน git-scm.com พื้นที่เก็บข้อมูลที่ GitHub

เครดิตยังตกเป็นของผู้มีส่วนร่วม นักข่าวข้อบกพร่อง และ ผู้ดูแลตลอดหลายปีที่ผ่านมาทั้งในพื้นที่เก็บข้อมูลนี้และในที่อื่น ๆ จาก ซึ่งเราดึงเนื้อหา ดูประวัติพื้นที่เก็บข้อมูลแต่ละรายการสําหรับ รายการที่สมบูรณ์

ผู้สนับสนุน
เราขอขอบคุณบริษัทที่ได้บริจาคทรัพยากรและ บริการเพื่อให้ไซต์ทํางานต่อไป ได้แก่:
FusionAuth, ซึ่งประจําปี การบริจาคให้กับโครงการ Git จะจ่ายค่าใช้จ่ายในการโฮสต์ของสิ่งนี้ เว็บไซต์
คลาวด์แฟลร์
บอนไซ
สําหรับมุมมองโดยละเอียดของเค้าโครงเครือข่ายของไซต์ โปรดดูของเรา เอกสารสถาปัตยกรรม●
