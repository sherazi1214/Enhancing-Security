# Enhancing-Security

**English:**
Enhancing security means applying defense-in-depth controls that reduce risks and protect against threats. It covers prevention, detection, and response strategies like web filtering, FIM, and EDR.

**Urdu:**
Yani layers of protection add karna taake system zyada strong aur safe ho jaye.

## Web Filtering

**English:**
Web Filtering is the process of controlling and monitoring access to websites and online content based on policies. It helps prevent malware infections, phishing, and productivity loss.

**Urdu:**
Yani users ko dangerous ya inappropriate websites par jane se rokna.

Web Filtering Components

**English:**

**URL Filtering** → Blocks/Allows websites based on categories (e.g., gambling, adult, social media).

**Content Filtering** → Analyzes actual webpage content (keywords, images, scripts).

**Application Filtering** → Controls access to web-based apps (YouTube, Facebook, Dropbox).

**SSL Inspection** → Decrypts HTTPS traffic to check malicious sites.

**Policy Engine** → Defines rules (who can access what, when).

**Reporting & Alerts** → Logs user activity for auditing.

**Urdu:**
Ye components mil kar decide karte hain kon si site block hogi aur kon si allow.

## Web Filtering Implementation

**English:**

**Gateway-based (Network Level):** Implemented on firewalls, secure web gateways, or proxies.

**Endpoint-based (Host Level):** Installed as an agent/software on user machines.

**Cloud-based Filtering:** Uses DNS or SaaS services (e.g., Cisco Umbrella, Zscaler).

**Hybrid Approach:** Mix of endpoint + network + cloud filtering.

**Urdu:**
Ya to network par central filter lagao, ya end-user machine pe agent, ya phir cloud DNS service use karo.

## File Integrity Monitoring (FIM)

**English:**
FIM continuously checks important system files, configs, and logs to ensure they are not altered unexpectedly. It detects tampering, insider threats, and malware.

**Urdu:**
Agar koi critical file change ho jaye bina authorization ke, FIM alert deta hai.

## FIM Components

**English:**

**Baseline Database:** Stores the original known-good state of files.

**Monitoring Agent:** Tracks changes in file size, hash, permissions, or ownership.

**Hashing Algorithms:** (MD5, SHA-256) to verify file integrity.

**Alerting System:** Notifies security teams if unauthorized changes occur.

**Reporting Dashboard:** Shows compliance & audit results.

**Urdu:**
Ek taraf original snapshot hota hai, aur agent continuously check karta hai ke koi file badli hai ya nahi.

## Endpoint Detection and Response (EDR)

**English:**
EDR is a security solution for endpoints (PCs, laptops, servers) that continuously monitors, detects, investigates, and responds to cyber threats. It provides deep visibility into endpoint activities.

**Urdu:**
Yani har computer aur device ka guard jo detect aur respond karta hai agar attack ho.

## EDR Key Features:

**Real-time Monitoring** → Tracks processes, files, registry, and memory.

**Threat Detection** → Uses signatures + behavioral analysis.

**Incident Response** → Isolates compromised endpoints, stops malicious processes.

**Forensics & Investigation** → Provides timeline of attack.

**Integration** → Works with SIEM, SOAR, and threat intelligence feeds.

**Examples:** CrowdStrike Falcon, Microsoft Defender for Endpoint, SentinelOne.

## Summary

**Web Filtering** = block bad sites.

**FIM** = protect files from tampering.

**EDR** = detect & respond on endpoints.
Together they enhance security by preventing, detecting, and responding to threats.
