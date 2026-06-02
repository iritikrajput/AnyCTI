Supply Chain Attack Campaign

Red Hat Cloud Services Package Compromise
The Red Hat Cloud Services Package Compromise is a malicious npm supply chain incident involving compromised @redhat-cloud-services package versions that execute an obfuscated credential-harvesting payload through a preinstall hook during npm install. The payload targets developer workstations and CI/CD environments, collecting GitHub Actions secrets, npm tokens, cloud credentials, Kubernetes and Vault material, SSH keys, and other sensitive files, with exfiltration through encrypted outbound channels and GitHub-based dead-drop mechanisms. The malicious versions appear to have been published through trusted upstream CI/CD publishing infrastructure, turning legitimate Red Hat Cloud Services packages into install-time credential theft and potential supply-chain propagation vehicles.

Ecosystems: npm

First discovered
2026-06-01
Last activity
2026-06-01
Affected Package Artifacts
95
Package Artifacts Last 7 Days
95
vs previous 7 days
Affected packages
Package Artifact	Published	Detected ▼
npm
@redhat-cloud-services/vulnerabilities-client
2.1.11

2026-06-01 14:24:19 UTC	2026-06-01 15:21:59 UTC
npm
@redhat-cloud-services/vulnerabilities-client
2.1.9

2026-06-01 13:46:27 UTC	2026-06-01 15:21:59 UTC
npm
@redhat-cloud-services/tsc-transform-imports
1.2.4

2026-06-01 13:45:14 UTC	2026-06-01 15:21:59 UTC
npm
@redhat-cloud-services/topological-inventory-client
3.0.13

2026-06-01 14:24:29 UTC	2026-06-01 15:21:59 UTC
npm
@redhat-cloud-services/topological-inventory-client
3.0.11

2026-06-01 13:46:30 UTC	2026-06-01 15:21:59 UTC
npm
@redhat-cloud-services/sources-client
3.0.11

2026-06-01 13:46:25 UTC	2026-06-01 15:21:58 UTC
npm
@redhat-cloud-services/rule-components
4.7.5

2026-06-01 14:23:16 UTC	2026-06-01 15:21:58 UTC
npm
@redhat-cloud-services/rule-components
4.7.3

2026-06-01 13:45:26 UTC	2026-06-01 15:21:58 UTC
npm
@redhat-cloud-services/remediations-client
4.0.7

2026-06-01 14:24:22 UTC	2026-06-01 15:21:58 UTC
npm
@redhat-cloud-services/remediations-client
4.0.5

2026-06-01 13:46:28 UTC	2026-06-01 15:21:58 UTC
npm
@redhat-cloud-services/rbac-client
9.0.6

2026-06-01 14:24:26 UTC	2026-06-01 15:21:58 UTC
npm
@redhat-cloud-services/rbac-client
9.0.4

2026-06-01 13:46:28 UTC	2026-06-01 15:21:58 UTC
npm
@redhat-cloud-services/quickstarts-client
4.0.14

2026-06-01 14:24:12 UTC	2026-06-01 15:21:57 UTC
npm
@redhat-cloud-services/quickstarts-client
4.0.12

2026-06-01 13:46:14 UTC	2026-06-01 15:21:57 UTC
npm
@redhat-cloud-services/patch-client
4.0.7

2026-06-01 14:24:22 UTC	2026-06-01 15:21:57 UTC
npm
@redhat-cloud-services/patch-client
4.0.5

2026-06-01 13:46:25 UTC	2026-06-01 15:21:57 UTC
npm
@redhat-cloud-services/notifications-client
6.1.7

2026-06-01 14:24:18 UTC	2026-06-01 15:21:57 UTC
npm
@redhat-cloud-services/notifications-client
6.1.5

2026-06-01 13:46:24 UTC	2026-06-01 15:21:57 UTC
npm
@redhat-cloud-services/javascript-clients-shared
2.0.11

2026-06-01 14:24:09 UTC	2026-06-01 15:21:57 UTC
npm
@redhat-cloud-services/javascript-clients-shared
2.0.9

2026-06-01 13:46:17 UTC	2026-06-01 15:21:57 UTC
npm
@redhat-cloud-services/integrations-client
6.0.7

2026-06-01 14:24:12 UTC	2026-06-01 15:21:57 UTC
npm
@redhat-cloud-services/integrations-client
6.0.5

2026-06-01 13:46:16 UTC	2026-06-01 15:21:57 UTC
npm
@redhat-cloud-services/insights-client
4.0.7

2026-06-01 14:24:26 UTC	2026-06-01 15:21:56 UTC
npm
@redhat-cloud-services/insights-client
4.0.5

2026-06-01 13:46:29 UTC	2026-06-01 15:21:56 UTC
npm
@redhat-cloud-services/host-inventory-client
5.0.6

2026-06-01 14:24:22 UTC	2026-06-01 15:21:56 UTC
npm
@redhat-cloud-services/host-inventory-client
5.0.4

2026-06-01 13:46:25 UTC	2026-06-01 15:21:56 UTC
npm
@redhat-cloud-services/hcc-pf-mcp
0.6.4

2026-06-01 14:25:10 UTC	2026-06-01 15:21:56 UTC
npm
@redhat-cloud-services/hcc-pf-mcp
0.6.2

2026-06-01 13:47:11 UTC	2026-06-01 15:21:56 UTC
npm
@redhat-cloud-services/hcc-kessel-mcp
0.3.4

2026-06-01 14:25:11 UTC	2026-06-01 15:21:56 UTC
npm
@redhat-cloud-services/hcc-kessel-mcp
0.3.2

2026-06-01 13:47:10 UTC	2026-06-01 15:21:56 UTC
npm
@redhat-cloud-services/hcc-feo-mcp
0.3.4

2026-06-01 14:25:10 UTC	2026-06-01 15:21:55 UTC
npm
@redhat-cloud-services/hcc-feo-mcp
0.3.2

2026-06-01 13:47:14 UTC	2026-06-01 15:21:55 UTC
npm
@redhat-cloud-services/frontend-components-utilities
7.4.4

2026-06-01 14:23:17 UTC	2026-06-01 15:21:55 UTC
npm
@redhat-cloud-services/frontend-components-utilities
7.4.2

2026-06-01 13:45:27 UTC	2026-06-01 15:21:55 UTC
npm
@redhat-cloud-services/frontend-components-translations
4.4.4

2026-06-01 14:23:15 UTC	2026-06-01 15:21:55 UTC
npm
@redhat-cloud-services/frontend-components-translations
4.4.2

2026-06-01 13:45:25 UTC	2026-06-01 15:21:55 UTC
npm
@redhat-cloud-services/frontend-components-testing
1.2.2

2026-06-01 13:45:19 UTC	2026-06-01 15:21:55 UTC
npm
@redhat-cloud-services/frontend-components-remediations
4.9.5

2026-06-01 14:23:08 UTC	2026-06-01 15:21:55 UTC
npm
@redhat-cloud-services/frontend-components-remediations
4.9.3

2026-06-01 13:45:19 UTC	2026-06-01 15:21:54 UTC
npm
@redhat-cloud-services/frontend-components-notifications
6.9.5

2026-06-01 14:23:16 UTC	2026-06-01 15:21:54 UTC
npm
@redhat-cloud-services/frontend-components-notifications
6.9.3

2026-06-01 13:45:25 UTC	2026-06-01 15:21:54 UTC
npm
@redhat-cloud-services/frontend-components-config-utilities
4.11.5

2026-06-01 14:23:09 UTC	2026-06-01 15:21:54 UTC
npm
@redhat-cloud-services/frontend-components-config-utilities
4.11.3

2026-06-01 13:45:22 UTC	2026-06-01 15:21:54 UTC
npm
@redhat-cloud-services/frontend-components-config
6.11.6

2026-06-01 14:23:09 UTC	2026-06-01 15:21:54 UTC
npm
@redhat-cloud-services/frontend-components-config
6.11.4

2026-06-01 13:45:20 UTC	2026-06-01 15:21:54 UTC
npm
@redhat-cloud-services/frontend-components-advisor-components
3.8.6

2026-06-01 14:23:17 UTC	2026-06-01 15:21:54 UTC
npm
@redhat-cloud-services/frontend-components-advisor-components
3.8.4

2026-06-01 13:45:26 UTC	2026-06-01 15:21:54 UTC
npm
@redhat-cloud-services/frontend-components
7.7.5

2026-06-01 14:23:18 UTC	2026-06-01 15:21:53 UTC
npm
@redhat-cloud-services/frontend-components
7.7.3

2026-06-01 13:45:29 UTC	2026-06-01 15:21:53 UTC
npm
@redhat-cloud-services/eslint-config-redhat-cloud-services
3.2.4

2026-06-01 14:23:04 UTC	2026-06-01 15:21:53 UTC
npm
@redhat-cloud-services/eslint-config-redhat-cloud-services
3.2.2

2026-06-01 13:45:18 UTC	2026-06-01 15:21:53 UTC
npm
@redhat-cloud-services/entitlements-client
4.0.12

2026-06-01 13:46:13 UTC	2026-06-01 15:21:53 UTC
npm
@redhat-cloud-services/config-manager-client
5.0.7

2026-06-01 14:24:08 UTC	2026-06-01 15:21:53 UTC
npm
@redhat-cloud-services/config-manager-client
5.0.5

2026-06-01 13:46:13 UTC	2026-06-01 15:21:53 UTC
npm
@redhat-cloud-services/compliance-client
4.0.6

2026-06-01 14:24:26 UTC	2026-06-01 15:21:53 UTC
npm
@redhat-cloud-services/compliance-client
4.0.4

2026-06-01 13:46:29 UTC	2026-06-01 15:21:53 UTC
npm
@redhat-cloud-services/entitlements-client
4.0.14

2026-06-01 14:24:09 UTC	2026-06-01 15:17:14 UTC
npm
@redhat-cloud-services/chrome
2.3.4

2026-06-01 14:23:11 UTC	2026-06-01 15:15:51 UTC
npm
@redhat-cloud-services/chrome
2.3.2

2026-06-01 13:45:23 UTC	2026-06-01 15:15:51 UTC
npm
@redhat-cloud-services/types
3.6.2

2026-06-01 13:45:15 UTC	2026-06-01 15:12:24 UTC
npm
@redhat-cloud-services/tsc-transform-imports
1.2.6

2026-06-01 14:23:03 UTC	2026-06-01 14:55:33 UTC
npm
@redhat-cloud-services/sources-client
3.0.13

2026-06-01 14:24:22 UTC	2026-06-01 14:31:15 UTC
npm
@redhat-cloud-services/types
3.6.4

2026-06-01 14:23:03 UTC	2026-06-01 14:29:20 UTC
npm
@redhat-cloud-services/host-inventory-client
5.0.3

2026-06-01 10:55:09 UTC	2026-06-01 11:06:04 UTC
npm
@redhat-cloud-services/topological-inventory-client
3.0.10

2026-06-01 10:55:23 UTC	2026-06-01 11:02:04 UTC
npm
@redhat-cloud-services/notifications-client
6.1.4

2026-06-01 10:54:58 UTC	2026-06-01 11:01:50 UTC
npm
@redhat-cloud-services/chrome
2.3.1

2026-06-01 10:54:42 UTC	2026-06-01 11:01:45 UTC
npm
@redhat-cloud-services/frontend-components
7.7.2

2026-06-01 10:55:00 UTC	2026-06-01 11:01:44 UTC
npm
@redhat-cloud-services/integrations-client
6.0.4

2026-06-01 10:54:36 UTC	2026-06-01 11:01:44 UTC
npm
@redhat-cloud-services/patch-client
4.0.4

2026-06-01 10:55:09 UTC	2026-06-01 11:01:35 UTC
npm
@redhat-cloud-services/quickstarts-client
4.0.11

2026-06-01 10:54:31 UTC	2026-06-01 11:01:33 UTC
npm
@redhat-cloud-services/rule-components
4.7.2

2026-06-01 10:54:59 UTC	2026-06-01 11:01:33 UTC
npm
@redhat-cloud-services/compliance-client
4.0.3

2026-06-01 10:55:21 UTC	2026-06-01 11:01:33 UTC
npm
@redhat-cloud-services/hcc-feo-mcp
0.3.1

2026-06-01 10:54:27 UTC	2026-06-01 11:01:31 UTC
npm
@redhat-cloud-services/vulnerabilities-client
2.1.8

2026-06-01 10:55:10 UTC	2026-06-01 11:01:30 UTC
npm
@redhat-cloud-services/frontend-components-translations
4.4.1

2026-06-01 10:54:47 UTC	2026-06-01 11:01:30 UTC
npm
@redhat-cloud-services/remediations-client
4.0.4

2026-06-01 10:54:59 UTC	2026-06-01 11:01:29 UTC
npm
@redhat-cloud-services/hcc-pf-mcp
0.6.1

2026-06-01 10:54:27 UTC	2026-06-01 11:01:28 UTC
npm
@redhat-cloud-services/frontend-components-remediations
4.9.2

2026-06-01 10:54:26 UTC	2026-06-01 11:01:26 UTC
npm
@redhat-cloud-services/javascript-clients-shared
2.0.8

2026-06-01 10:54:26 UTC	2026-06-01 11:01:25 UTC
npm
@redhat-cloud-services/frontend-components-config-utilities
4.11.2

2026-06-01 10:54:36 UTC	2026-06-01 11:01:25 UTC
npm
@redhat-cloud-services/sources-client
3.0.10

2026-06-01 10:55:04 UTC	2026-06-01 11:01:25 UTC
npm
@redhat-cloud-services/insights-client
4.0.4

2026-06-01 10:55:21 UTC	2026-06-01 11:01:24 UTC
npm
@redhat-cloud-services/rbac-client
9.0.3

2026-06-01 10:55:21 UTC	2026-06-01 11:01:24 UTC
npm
@redhat-cloud-services/frontend-components-notifications
6.9.2

2026-06-01 10:54:53 UTC	2026-06-01 11:01:24 UTC
npm
@redhat-cloud-services/frontend-components-advisor-components
3.8.2

2026-06-01 10:54:58 UTC	2026-06-01 11:01:23 UTC
npm
@redhat-cloud-services/hcc-kessel-mcp
0.3.1

2026-06-01 10:54:26 UTC	2026-06-01 11:01:22 UTC
npm
@redhat-cloud-services/config-manager-client
5.0.4

2026-06-01 10:54:25 UTC	2026-06-01 11:01:22 UTC
npm
@redhat-cloud-services/frontend-components-utilities
7.4.1

2026-06-01 10:54:59 UTC	2026-06-01 11:01:22 UTC
npm
@redhat-cloud-services/frontend-components-config
6.11.3

2026-06-01 10:54:36 UTC	2026-06-01 11:01:20 UTC
npm
@redhat-cloud-services/tsc-transform-imports
1.2.2

2026-06-01 10:54:15 UTC	2026-06-01 11:00:40 UTC
npm
@redhat-cloud-services/eslint-config-redhat-cloud-services
3.2.1

2026-06-01 10:54:20 UTC	2026-06-01 11:00:35 UTC
npm
@redhat-cloud-services/frontend-components-testing
1.2.1

2026-06-01 10:54:21 UTC	2026-06-01 11:00:33 UTC
npm
@redhat-cloud-services/types
3.6.1

2026-06-01 10:54:09 UTC	2026-06-01 11:00:31 UTC
npm
@redhat-cloud-services/entitlements-client
4.0.11

2026-06-01 10:54:20 UTC	2026-06-01 11:00:22 UTC


--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Attack chain:

npm install
    │
    ▼
preinstall → node index.js
    │
    ▼
ROT/Caesar + eval() decoding
    │
    ▼
AES-GCM decrypts payloads
    │
    ▼
Downloads Bun runtime (if missing)
    │
    ▼
Writes payload to /tmp/p[random].js
    │
    ▼
Executes payload
    │
    ▼
Deletes payload file
    │
    ▼
Credential harvesting
    │
    ▼
Encrypted exfiltration
    │
    ▼
GitHub fallback exfiltration

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Based on the analyzed malware behavior, here's a structured **MITRE ATT&CK Mapping** organized by **Tactic → Technique → Evidence**.

# Initial Access

| Technique                        | ID        | Evidence                                                                 |
| -------------------------------- | --------- | ------------------------------------------------------------------------ |
| Compromise Software Supply Chain | T1195.001 | Malicious code embedded in trusted `@redhat-cloud-services` npm packages |
| Trusted Relationship             | T1199     | Abuse of trust in Red Hat Cloud Services package namespace               |

---

# Execution

| Technique                                     | ID        | Evidence                                                |
| --------------------------------------------- | --------- | ------------------------------------------------------- |
| Command and Scripting Interpreter: JavaScript | T1059.007 | `node index.js`, `eval()`, decrypted JS execution       |
| Event Triggered Execution                     | T1546     | npm `preinstall` hook automatically executes malware    |
| System Binary Proxy Execution                 | T1218     | Uses legitimate `node`, `bun`, `curl`, `unzip` binaries |
| User Execution: Malicious File                | T1204.002 | Triggered when developer runs `npm install`             |

---

# Defense Evasion

| Technique                               | ID        | Evidence                                                                |
| --------------------------------------- | --------- | ----------------------------------------------------------------------- |
| Obfuscated Files or Information         | T1027     | Char arrays, ROT/Caesar cipher, encrypted blobs                         |
| Deobfuscate/Decode Files or Information | T1140     | Runtime decoding and AES decryption                                     |
| Masquerading                            | T1036     | Legitimate-looking package and ESM code hiding malicious CommonJS entry |
| Indicator Removal on Host               | T1070.004 | Deletes `/tmp/p*.js` after execution                                    |
| Virtualization/Sandbox Evasion          | T1497     | Russian locale checks may indicate selective execution                  |
| Hide Artifacts                          | T1564     | Runtime-generated temporary payload files                               |

---

# Discovery

| Technique                      | ID        | Evidence                                         |
| ------------------------------ | --------- | ------------------------------------------------ |
| System Information Discovery   | T1082     | Collects hostname, username, OS information      |
| Environment Variable Discovery | T1082     | Dumps `process.env`                              |
| Cloud Service Discovery        | T1526     | Searches AWS, Azure, GCP, Kubernetes configs     |
| System Language Discovery      | T1614.001 | Detects Russian locale/language                  |
| File and Directory Discovery   | T1083     | Searches credential hotspots and token locations |

---

# Credential Access

| Technique                              | ID        | Evidence                                    |
| -------------------------------------- | --------- | ------------------------------------------- |
| Credentials from Files                 | T1552.001 | `.npmrc`, `.git-credentials`, cloud configs |
| Private Keys                           | T1552.004 | SSH keys (`id_rsa`, `id_ed25519`)           |
| Credentials from Password Stores       | T1555     | GitHub CLI token collection                 |
| Unsecured Credentials                  | T1552     | npm tokens, Git credentials                 |
| Cloud Account Credentials              | T1528     | AWS, Azure, GCP credentials                 |
| Steal Application Access Token         | T1528     | GitHub PATs, GitHub Actions tokens          |
| Credentials from Environment Variables | T1552.001 | Captures secrets from CI/CD environments    |

---

# Collection

| Technique                          | ID    | Evidence                                                 |
| ---------------------------------- | ----- | -------------------------------------------------------- |
| Data from Local System             | T1005 | Reads local credential files                             |
| Data from Information Repositories | T1213 | Git configs, cloud configs, registry configs             |
| Automated Collection               | T1119 | Scans predefined credential hotspots                     |
| Data from Cloud Storage Objects    | T1530 | Cloud credential collection may enable cloud data access |

---

# Persistence

| Technique                                           | ID    | Evidence                                                   |
| --------------------------------------------------- | ----- | ---------------------------------------------------------- |
| Boot or Logon Autostart Execution (partial)         | T1547 | Not directly observed, but daemonization extends execution |
| Process Injection/Background Execution (behavioral) | T1055 | Detached child process execution                           |
| Create or Modify System Process                     | T1543 | Background daemon-style process creation                   |

*Persistence evidence is weaker than other tactics and should be considered medium confidence.*

---

# Privilege Escalation

| Technique                         | ID    | Evidence                                                     |
| --------------------------------- | ----- | ------------------------------------------------------------ |
| Abuse Elevation Control Mechanism | T1548 | Attempts privileged execution using `sudo` on GitHub runners |

---

# Command and Control

| Technique                                 | ID        | Evidence                         |
| ----------------------------------------- | --------- | -------------------------------- |
| Web Service                               | T1102     | GitHub API communications        |
| Web Service: Bidirectional Communication  | T1102.001 | GitHub-based fallback channel    |
| Application Layer Protocol: Web Protocols | T1071.001 | HTTPS communication              |
| Ingress Tool Transfer                     | T1105     | Downloads Bun runtime            |
| Encrypted Channel                         | T1573     | AES + RSA protected exfiltration |

---

# Exfiltration

| Technique                          | ID                  | Evidence                                              |
| ---------------------------------- | ------------------- | ----------------------------------------------------- |
| Exfiltration Over Web Service      | T1567               | HTTPS POST exfiltration                               |
| Exfiltration to Cloud Storage      | T1567.002           | GitHub repository commits used as fallback            |
| Archive Collected Data             | T1560               | Gzip compression before exfiltration                  |
| Encrypt Data for Impact/Protection | T1486 (partial use) | AES-GCM encryption of stolen data before transmission |

---

# Impact

| Technique                                              | ID        | Evidence                                                 |
| ------------------------------------------------------ | --------- | -------------------------------------------------------- |
| Resource Hijacking                                     | T1496     | Potential abuse of compromised CI/CD environments        |
| Compromise Software Dependencies and Development Tools | T1195.002 | Targets developers and package publishing infrastructure |
| Compromise CI/CD Pipeline                              | T1195.001 | GitHub Actions runner targeting                          |
| Supply Chain Compromise                                | T1195     | Primary objective appears to be downstream propagation   |

---

# ATT&CK Tactics Coverage Summary

| Tactic               | Coverage       |
| -------------------- | ---------------|
| Initial Access       | ✅ Strong      |
| Execution            | ✅ Strong      |
| Persistence          | ⚠️ Moderate    |
| Privilege Escalation | ⚠️ Moderate    |
| Defense Evasion      | ✅ Strong      |
| Credential Access    | ✅ Very Strong |
| Discovery            | ✅ Strong      |
| Collection           | ✅ Strong      |
| Command & Control    | ✅ Strong      |
| Exfiltration         | ✅ Very Strong |
| Impact               | ✅ Strong      |

# Most Significant ATT&CK Techniques

These are the techniques that best characterize the campaign:

* **T1195.001** – Compromise Software Supply Chain
* **T1546** – Event Triggered Execution (npm preinstall)
* **T1059.007** – JavaScript Execution
* **T1027** – Obfuscated Files or Information
* **T1140** – Deobfuscate/Decode Files
* **T1552.001** – Credentials from Files
* **T1555** – Credentials from Password Stores
* **T1528** – Steal Application Access Tokens
* **T1102.001** – GitHub Web Service Communication
* **T1567** – Exfiltration Over Web Service
* **T1573** – Encrypted Channel
* **T1195.002** – Compromise Software Dependencies & Development Tools

